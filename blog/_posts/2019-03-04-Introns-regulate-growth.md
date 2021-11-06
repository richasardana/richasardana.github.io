---
layout: post
title: "Introns and growth"
description: ""
author_handle: richa
category: blog
tags: [journal club, TORC1, introns, yeast]

---
*Research Paper Highlight:*
 **Excised linear introns regulate growth in yeast.**

Morgan et. al., [Nature volume 565, pages606–611 (2019)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6464110/)

<!--more-->

Introns are generally thought of as a waste by-product of RNA processing and molecules that are rapidly degraded soon after they are produced.They are assumed to be very short lived species- once the spliceosome joins the two exons, the spliceosome disassembles and the intron (lariat structure which looks like a lasso) is released. It is very quickly debranched by Dbr1, polyadenylated by the TRAMP complex and degraded by the nuclear exosome. Most introns don't accumulate or seem to have any phenotype in log phase cultures in rich media.

The authors perform RNA seq in log phase vs saturated cultures, and show that some of the introns (their best examples are ECM33 and SAC6) are dramatically stablized in saturated cultures. In fact they show by RNA seq and Northern blots that the mature RNA for these is completely non-detectable in saturated cultures but the intron is really stable. They also show that the stability is intrinsic to the intron, and not dependent on the host gene, i.e, moving the intron into a completely different context (in a URA3 reporter), still phenocopies the intron stability phenotype in saturated cultures. Yet, the sequence does not show any conserved motif or RNA structural motif. They observe that the distance between the branch point and the 3' splice site tends to be shorter for stable introns as opposed to introns that are not stable, and they nicely test that if they extend the length of this distance, the ECM33 intron is no longer stable or if they shorten the length in an otherwise non-stable intron of ACT1, the intron is now stable. They also attempt to understand how these introns are accumulating, and are only slightly successful in understanding it at all. The introns are stabilized after prolonged treatment (4h) with Rapamycin, DTT and tunicamycin but not short treatments (1h). The effect does not depend on a specific nutrient starvation but general secretory stress (not IRE1 dependent, so not UPR), nor mediated by Tor1 effectors, Sch9 or Tap42. So conclusions for these data are, not surprisingly, a bit hand-wavy. 

They conclude by showing that accumulation of stable introns is advantageous to cellular fitness in stationary phase, but detrimental during rapid log phase growth. Their model is that TORC1 inhibition results in accumulation of these introns, these introns engage and titrate away the spliceosomal machinery, preventing them from too much splicing (esp ribosomal genes which are particularly enriched in introns), thus reducing the growth rate overall but allowing for better survival in limiting conditions. Overall, I think the observation of stable introns is quite striking, but it opens up so many questions than were attempted to be addressed in the work. For instance, what are the Tor1 effectors involved? Is the splicing machinery really getting titrated away? How are the stable introns specifically protected from degradation? And then, bringing into perspective that only 5% of yeast contain introns, as compared to roughly 95% of human genes. If this is indeed a conserved response, this should have a really important contribution to growth signaling in mammalian cells. But that will be for a later time.


