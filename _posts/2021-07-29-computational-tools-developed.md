---
title: Computational Tools We’ve Developed
subtitle: ""
date: 2018-06-06 00:00:00
description: Click here to learn more.
featured_image: /images/research/computational-tools-developed/innatedb.png
---

# Computational Tools We’ve Developed

*All tools are freely available under an open source license.*

![PSORTb](/images/research/computational-tools-developed/psortb.png){: .image--float--right}

**PSORTb:** Used to investigate the subcellular localization of proteins from bacteria and archaea. This resource, plus PSORTdb, is available from our [psort.org](http://www.psort.org/) portal for prediction of protein subcellular localization.

**PSORTdb:** PSORTdb is a database of bacterial and archaeal protein subcellular localization that includes both known proteins and those that have been computationally predicted. It is available as part of the [psort.org](http://www.psort.org/) family of resources. It features a web-based interface and the source code or data dumps are made freely available.

**Ortholuge and OrtholugeDB:** Ortholuge is a computational method that can generate precise ortholog predictions between two species on a genome-wide scale (using additional outgroup data for reference). It can either evaluate a previously constructed set of orthologs or it can generate an initial tentative set of orthologs that are subsequently evaluated. Precise ortholog prediction is important for a variety of analyses that utilize comparative genomics. OrtholugeDB provides pre-computed Ortholuge-based orthology predictions for completely sequenced bacterial and archaeal genomes. It is also a resource for reciprocal best BLAST-based ortholog predictions, in-paralog predictions (recently duplicated genes) and ortholog groups in Bacteria and Archaea. See the [OrtholugeDB](http://www.pathogenomics.sfu.ca/ortholugedb/) website and associated publications for more details.

**IslandViewer:** Facilitates the identification of “genomic islands” of genes in bacterial and archaeal genomes that may have horizontal origins, through a whole-genome graphical display of genomic island predictions from the most accurate genomic island prediction methods (including our IslandPath and IslandPick methods). See [http://www.pathogenomics.sfu.ca/islandviewer](http://www.pathogenomics.sfu.ca/islandviewer)

![IslandPath](/images/research/computational-tools-developed/islandpath.png){: .image--float--right}

**IslandPath:** Facilitates the identification of genomic islands in prokaryotic genomes that may have horizontal origins, through a whole-genome graphical display of dinucleotide bias of gene clusters, %G+C ratio genes, and other features relevant to the identification of pathogenicity islands (and other genomic islands). Island predictions, using the IslandPath-DIMOB method, are available through [IslandViewer](http://www.pathogenomics.sfu.ca/islandviewer).

**IslandPick:** Facilitates the identification of genomic islands in microbial genomes that may have horizontal origins, through a comparative genomics approach. Island predictions, using default criteria that compares against genomes of suitable phylogenetic distance, are available through [IslandViewer](http://www.pathogenomics.sfu.ca/islandviewer). Also through IslandViewer, one can choose which comparative genomes to compare with two identify islands specific to a particular species, or other collection of taxa.

**Pseudomonas Genome Database:** The current Pseudomonas Genome Database at [www.pseudomonas.com](http://www.pseudomonas.com/) has been expanded to allow continual updates and more flexible queries of the data, along with a Gbrowse view of the genome data, which provides links to other data sources and distributed annotation system (DAS) capabilities. Multiple genomes and SNPs may now be viewed to faciliate comparisons. This database contains genome data for all Pseudomonas genomes, though it is primarily focused on Pseudomonas aeruginosa and providing a high quality resource to aid research for improved methods of controling this important Cystic Fibrosis pathogen.

**Burkholderia Genome Database:** The [Burkholderia Genome Database](http://www.burkholderia.com/) is a sister database to the Pseudomonas Genome Database, with a similar interface and functionality to facilitate analysis of Burkholderia species of interest as additional important Cystic Fibrosis pathogens.

![InnateDB](/images/research/computational-tools-developed/innatedb.png){: .image--float--left}

**InnateDB:** Facilitating systems based analysis of Innate Immunity and beyond, [InnateDB](http://www.innatedb.com/) is a publicly available database of the genes, proteins, experimentally-verified interactions and signaling pathways involved in the innate immune response of humans and mice to microbial infection. The database captures an improved coverage of the innate immunity interactome by integrating known interactions and pathways from major public databases together with manually-curated data into a centralised resource. The database can be mined as a knowledgebase or used with our integrated bioinformatics and visualization tools for the systems level analysis of the innate immune response or any other response. This resource is being expanded to also incorporate related, curated information about Allergy and Asthma.

**Microarray Analysis Software:** [ArrayPipe](http://www.pathogenomics.ca/arraypipe/index.html) and [ProbeLynx](http://www.pathogenomics.ca/probelynx/index.html) were developed for the Genome Canada [Pathogenomics Project](http://www.pathogenomics.ca/). ArrayPipe provides a flexible approach to microarray analysis that is parralellizable, web-based or command-line based, and is freely available under an open source licence. ProbeLynx allows you to update annotations for your microarray probes, using sequence data that is also investigated for its potential for cross-hybridization. [InnateDB](http://www.innatedb.com/) mentioned above, can also provide tools to aid microarray analysis of diverse human and mouse gene datasets, since the database is not limited to just containing Innate Immunity genes.

**Bioperl Modules:** [Bio::Tools::SubLoc](http://www.pathogenomics.sfu.ca/brinkman/code/Bio-Tools-SubLoc-0.02.tar.gz) and the associated, required [Algorithm::SVM](http://www.pathogenomics.sfu.ca/brinkman/code/Algorithm-SVM-0.02.tar.gz) module were developed for making SubLoc protein subcellular localization predictions as part of the PSORT-B project. They were developed by Cory Spencer and are also available from any CPAN mirror. For more information about SubLoc, which was developed by S Hua and Z Sun, see their [paper in Bioinformatics (2001. 17:721-728)](http://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=Retrieve&db=PubMed&list_uids=11524373&dopt=Abstract).
