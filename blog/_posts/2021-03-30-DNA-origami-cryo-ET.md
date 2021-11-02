---
layout: post
title: "Structuromics-Part 3"
description: ""
author_handle: richa
category: blog
tags: [journal club, Structuromics,Electron microscopy, cryo-ET, RNA aptamers, DNA origami]
---
*Research Paper Highlight:*
 **DNA origami signposts for identifying proteins on cell membranes by electron cryotomography**

Emma Silvester, Benjamin Vollmer, Vojtěch Pražák, Daven Vasishtan, Emily A Machala, Catheryne Whittle, Susan Black, Jonathan Bath, Andrew J Turberfield, Kay Grünewald, Lindsay A Baker

[Cell 2021 Feb 18;184(4):1110-1121.e16. doi: 10.1016/j.cell.2021.01.033.](https://www.sciencedirect.com/science/article/pii/S0092867421000763?via%3Dihub)



For Part 3 of the Structuromics series I am highlighting a paper that uses interesting concepts from different fields to create a cool new tool for cryo-ET. While not exactly using an omics approach, it is a pretty neat use of technology, so I decided to include it here.

See here for [Part 1]({% post_url 2021-01-30-LIP-MS-paper %}), and [Part 2]({% post_url 2021-02-20-GI-mapping-protein-structure-paper %})
 

In crowded biological environments it is often difficult to identify small features of interest or those without a distinct appearance, especially without prior structural information in cryo-ET workflows. To learn more about cryo-ET, and the history of elcetro microscopy for biological samples [see here](https://rupress.org/jcb/article/202/3/407/54592). 

The authors decided to approach this problem by designing a better tag that is suitable to use with living cells, suitable for frozen hydrated samples, does not obscure the biological sample, not rely on stains or metals (hence not scatter more than the atoms of the specimen itself), while providing precise localization with high confidence. And although there are limitations to the applications of their approach, they did come up with nice solution which I think will likely improve with time. What I found really cool about this work was how they combined ideas and tools already developed in other fields, and applied them to design a good (hopefully improved) tool for cryo-ET analysis.  


Here is what they do: They first designed a DNA origami tag, and then combined it with RNA aptamers that target a specific protein, that can then be incubated with biological samples.

Never heard of DNA origami? DNA origami is the folding of a long single stranded DNA with multiple small ‘staple’ strands to generate specifically defined 2D and 3D shapes at the nanoscale. [See the original paper here](https://www.nature.com/articles/nature04586). The advantages for using DNA to generate a cryo-ET tag are that Phosphorus (that forms the DNA backbone) scatters elastically ~4x more electrons than carbon, oxygen, or nitrogen, that can provide high enough contrast but not obscure biological structures around it in cellular tomograms. And, DNA origami has been extensively tested for use with cryoEM, so they already knew the DNA tags can handle the Cryo-ET work flow.
The DNA origami signpost nanostructure they design is built from a 7,249-nucleotide scaffold strand (single-stranded M13mp18) hybridized to 238 staple oligonucleotides to form a structure of approximately 5 MDa comprising 96 parallel helices arranged in a honeycomb lattice. 

Next trick was to target this tag to specific proteins of interest in a biological sample. For this they employed aptamers. Aptamers are RNA oligonucleotides that bind to a specific target with high affinity and specificity, similar to how an antibody binds to an antigen. Read more about aptamers [here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3627066/#:~:text=RNA%20Aptamers%20are%20defined%20as,antibody%20binds%20to%20an%20antigen). The aptamers against common fluorescent proteins such as GFP and mCherry have been previosuly characterized by some wonderful work done here at Cornell in our Provost [Mike Kotilikoff's](https://www.vet.cornell.edu/research/faculty/michael-kotlikoff-vmd-phd) lab. See that paper [here](https://academic.oup.com/nar/article/40/5/e39/1104065). So the authors decided to test their approach by using the aptamers against GFP/ mCherry to look at proteins that have been tagged with these fluorescent protein tags. In principle, if the workflow can be modified, this could also allow to correlate fluorescence signals with the tomograms. 

They then use this tag to test in three applications- to look at proteins in membrane vesicles, proteins on the viral surface, as well as cell surface proteins in mammalian cells. They show that their tag can allow more precise localization of the labeled protein
whereas immuno-gold labeling puts the gold clusters up to 20-40 nm away. Their tag was easily identifiable, and in many cases could be directly traced to protein density on the vesicle surface. The latter can be useful for purposes of manual particle picking for sub-volume averaging applications, although getting really detailed structual resolution of labeled proteins will take more work. 

That's really the heart of it! The approach is pretty cool, and does achieve many of the objectives they lay out at the beginning. It isn't perfect, for instance, it is limited by available specific aptamers, and unclear if it will work for visualization of intracellular organelle proteins rather than just those at the cell surface. But, it's pretty cool!



 



