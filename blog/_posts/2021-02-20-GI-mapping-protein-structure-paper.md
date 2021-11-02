---
layout: post
title: "Structuromics-Part 2"
description: ""
author_handle: richa
category: blog
tags: [journal club, Structuromics, omics, Genetic Interaction mapping, GI profile, epistatic miniarray profile, integrative modeling, yeast, histones ]

---
*Research Paper Highlight:*
 **Genetic interaction mapping informs integrative structure determination of protein complexes**

Hannes Braberg, Ignacia Echeverria, Stefan Bohn, Peter Cimermancic, Anthony Shiver, Richard Alexander, Jiewei Xu, Michael Shales, Raghuvar Dronamraju, Shuangying Jiang, Gajendradhar Dwivedi, Derek Bogdanoff, Kaitlin K. Chaung, Ruth Hüttenhain, Shuyi Wang, David Mavor, Riccardo Pellarin, Dina Schneidman, Joel S. Bader, James S. Fraser, John Morris, James E. Haber, Brian D. Strahl, Carol A. Gross, Junbiao Dai, Jef D. Boeke, Andrej Sali, Nevan J. Krogan

[Science Vol. 370, Issue 6522, (2020); DOI: 10.1126/science.aaz4910](https://science.sciencemag.org/content/370/6522/eaaz4910/tab-article-info)

For Part 2 of the Structuromics series I am highlighting a paper that combines high throughout genetic interaction mapping and integrative modeling for in vivo structural profiling.  

See here for [Part 1]({% post_url 2021-01-30-LIP-MS-paper %}).  

Large scale genetic interaction (GIs) profiling in model organisms such as budding yeast has been transformative in informing us about cellular pathways and ascribing function to uncharacterized proteins. Applicability of CRISPR-Cas9 based genetic manipulation has made high-throughout genetic interaction profiling possible in mammalian cells as well as almost any model system. In this work, the authors put to test the idea whether genetic interaction profiles can be employed to determine protein structural information. 

Traditionally, genetic interaction analysis involves comparing the phenotypes when loss of the protein product of one gene is combined with the loss of another one (for digenic GIs) or multiple (for multigenic GIs). Well, how about generating a library of mutants by mutating every single residue in a protein and combining each with the gene deletion collection? The resulting (hundreds of!) GI profiles or epistatic miniarray profiles (pE-MAPs) can be compared to each other. Residues involved in the same interactions are likely to generate similar GI profiles, which may be distinct with GIs from residues involved in interactions with a different protein. The phenotypic similarities and differences can then be incorporated into integrative modeling algorithms to generate structural models for architectures of protein complexes. Its a tour de force, and the authors show it works!

The quantitative GI profile dataset can be enriched combinatorially, by measuring sensitivity to chemical datasets or by also measuring changes under different stresses. And by employing barcodes and next-gen sequencing approaches the massively-parallel screens can be performed in liquid cultures allowing cost and infrastructure reduction. What is really powerful about this approach is the ability to capture effects of transient interactions that are not otherwise possible to discern from GI datasets. In addition, the structural information infered reflects in vivo protein complex interactions providing a built-in functional readout. There are caveats of course- the choice of amino acid change can have a huge impact on protein stability or protein-protein interactions or that single amino acid changes may illicit only modest effects that may not be captured in GI interactions. The true value of analysis will likely be amplified when combining it with orthogonal approaches- such as cross-linking mass spectrometry or crystallography/ cryo-EM. Extending the analysis to disease associated alleles or for multiple components of protein complexes, too can provide valuable information. Overall, I found it is really amazing how much can be inferred by the approach. 
