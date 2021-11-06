---
layout: post
title: "Lab notebook guidelines"
description: "Principles and guidelines for electronic lab notebook entries and organization"
about: true
author_handle: richa
tags: [labmanual, wetlab]
---
{% include JB/setup %}

* TOC
{:toc}

# Why lab notebooks are important

Good record-keeping is an essential part of good work:

- Your lab notebook helps you to remember what you did and why.
- Your lab notebook is the best way to communicate activity and data around the lab.
- Keeping good records is a legal and funder requirement.

The lab notebook belongs to the institution, not to you personally.
Keeping it up to date is a responsibility to yourself, to our research group, and to the institution.

Some scenarios where good lab notebook entries are useful:

- You need to show your last month's data to the PI or a colleague.
- You need to repeat an experiment you last did a year ago.
- A new lab member is comparing two approaches to an experiment, their pros and cons, to plan a new version.
- An experiment that used to work has stopped working, and we need to go over the details of reagents and what has changed.
- You are writing up the methods section of your PhD thesis or paper.
- The reviewers for your paper ask to see other items of raw data.

In all these cases, if you have kept good lab notebooks you and your colleagues will be grateful to past you. You might think you will remember the details, but you won't.
Without good notebook entries, important points will be forgotten, your or someone else's time will be wasted, and you risk accusations of misconduct.

In summary, the lab notebook is a tool to do good work, that is practically useful for you. Keeping your lab notebook up to date is a non-negotiable requirement for students and staff who work in the lab.


# Principles for lab notebooks

*Your experiment is not "done" until it is written up in your lab notebook.*

Your lab notebook should:

- Index each experiment clearly, with dates, and include, or link to, data and metadata
- Describe your work in enough detail to reproduce it.
- Place your work in the context of larger goals and projects.
- Be updated within a week.

A useful test is, would you be able to reproduce the experiment in a year's time working from the lab notebook entry? Would someone else be able to reproduce it, a year after that?

You need to set aside both time and mental energy to write the lab notebook.
Good habits help.
For example, you can set up templates for entries for standard experiments that you do.
You can set aside regular time to update the notebook, including with other lab members to create some accountability.

## Work should be FAIR: Findable, Accessible, Interoperable, and Reusable

It is helpful to consider the [FAIR principles for scientific data management](https://www.go-fair.org/fair-principles/), which also apply to protocols, analysis, and methods.

- *Findable:* The first step in (re)using data and protocols is to find them. Your lab notebook entries should be findable by "metadata", for example project, protocol, strain or oligo identifier, or date of creation.
- *Accessible:* Once the user finds the required data you should be able to access it. So if the lab notebook entry mentions a dataset elsewhere (e.g. datastore, lab notebook page), link to it with accession information.
- *Interoperable:* The data usually need to be integrated with other data, and to interoperate with applications or workflows for analysis, storage, and processing. Use standard file formats.
- *Reusable:* The ultimate goal is to optimise the reuse of data, protocols, and methods. You and others should be able to reuse what you have done, to a high standard, and efficiently.


# Examples of what to include and what not

Basically everything that is easy and/or important to include in your lab notebook should be in there. Information doesn't need to be repeated in multiple notebook entries, because you can hyperlink between entries; as a guide, everything directly relevant to the experiment should be findable (linked to, named, file location described, etc) within 5 minutes.

To inform the judgment call of what to include and what not:

- *Index* your experiments- for example, using an excel sheet with the brief description of the experiment, and where the details can be found will save you a lot of time later.
- *Handwritten notes* are fine to include, just take a photo of it and include in with enough typed searchable metadata that you can find it again.
- *Bullet points* are fine, you do not need to write in paragraphs. It's more important to have a terse account that is written quickly than beautiful prose.
- *Say why* you are doing the experiment - briefly state the aim of the experiment and connect/link it to the larger project. You might have a project or subproject aims page you can link to, or a "parts guide" for a group of related strains/plasmids that gets updated as specific parts are made and verified.
- *Conclude* what you learned and what you need to do next, however briefly.
- *Things don't have to work,* include data from all experiments, "successful" or otherwise. 
- *Strains* you use should list the lab strain ID number, along with a brief description of the key genotype of the strain.
- *Oligos* include the oligo name/ID and a brief descriptor of the oligo.
- *Designs* for plasmids, inserts, cloning, etc, should be included in the relevant notebook entries. Usually the design would be in snapgene, genbank, or fasta format, 
- *Plasmids* once confirmed by diagnostic restriction digestion and sequencing should be assigned a lab plasmid ID number. The plasmids should also be transformed in appropriate bacterial competent cells, and saved as glycerol stocks. In the notes, plasmids should be refered to wiht the ID number and a brief description.
- *Photos* of tubes, equipment, pipetting layouts, etc - it's also easy to take a photo and shove it in your notebook, why not do that. These photos help address the situation where you leave the lab and think "oh goodness, did I have the samples in the right order?"
- *PCR*, record the date, purpose, template, oligos, expected sizes, enzymes, buffers, cycling parameters, photos of the gel. 
- *Reagents should be recorded precisely including manufacturer's part number*, and ideally batch number, when saving lab stock aliquots of shared reagents. Use the label printer to print the information rather than writing it on each tube. The information should include concentration, solvent, manufacturer, lot and batch number, (pH, sterilization info as appropriate), date, and your initials. 
- *Strange observations* should be included, for example "a very hot day in lab and my experiment unexpectedly failed, maybe it's the temperature?"


# Raw unedited data must be included

Raw unmodified data must be included or linked to, without exception. Usually larger files will be kept on the online lab storage space and linked to, or provide exact information where to find it. Include enough descriptors in your metadata files so you can easily ascribe the files to specific samples/ conditions.


# Processed and summarized data must also be included

Yes, this means that most notebook entries will include both raw and processed data.
This kind of near-repetition is ok. If you processed or obtained data via a website (e.g. gene ontology analysis, RNA folding, qPCR primer design), give enough information to be able to repeat it.


# Give your files good names

Starting the filename with a data in standard format `yyyy-mm-dd` means that you can unambiguously link the data to the day it is collected and can be easily ordered.
For example `20211030-facs-Mup1-gfp.xls` tells us that these are data from FACS experiment, looking at Mup1-GFP, on 10th Och 2021, which can easily then be linked to the lab notebook entry for the same date.
For more, see [Jenny Bryan's amazing presentation on naming things](https://speakerdeck.com/jennybc/how-to-name-files).

You may come up with better ways to name and keep track of files.
Remember the FAIR principles: organize the files so you can find them, access them, interoperate with other pieces of data, and generally reuse the data.


# Guidelines for electronic lab notebook entries and organization.

You are encouraged to use any of the following electronic notebooks:

[Labarchives- Electronic digital notebook](https://teaching.cornell.edu/learning-technologies/collaboration-tools/electronic-lab-notebooks-labarchives)- You will use your Cornell netID to login to access Labarchives.
[Microsoft One note](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006918)
[Benchling](https://www.benchling.com/academic/)

If we decide on aparticular lab notebook, there are some practices that we could adopt to streamline our notetaking, such as set up templates for common lab book entries.

## Have two kinds of tables of contents, one by date and one by project or experiment type

We have found it seriously helpful to have one table of contents of activity by date, and another by project. That way you can search either by when it happened or by what it connects to, helping with the principle "Place your work in the context of larger goals and projects.". 
You'll find some templates that will help in starting to index your work.

