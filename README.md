# Neely_et_al_2024_Royal_Open_Sci
Data and code from Neely et al. 2024. Host-associated helminth diversity and microbiome composition contribute to anti-pathogen defences in tropical frogs impacted by forest fragmentation. Royal Society Open Science https://doi.org/10.1098/rsos.240530

## Abstract
Habitat fragmentation can negatively impact wildlife populations by simplification of ecological interactions, but little is known about how these impacts extend to host-associated symbiotic communities. The symbiotic communities of amphibians play important roles in antipathogen defences, particularly against the amphibian chytrid fungus *Batrachochytrium dendrobatidis* (Bd). In this study, we analyse the role of macroparasitic helminth communities in concert with microbial communities in defending the host against Bd infection within the context of forest fragmentation. We found that skin microbial and helminth communities are disrupted at fragmented habitats, while gut microbiomes appear more resilient to environmental change. We also detected potential protective roles of helminth diversity and anti-pathogen microbial function in limiting Bd infection. Microbial network analysis revealed strong patterns of structure in both skin and gut communities, with helminths playing central roles in these networks. We reveal consistent roles of microbial and helminth diversity in driving host–pathogen interactions and the potential implications of fragmentation on host fitness.

## Description of Data
- ASV_taxonomy.csv -- This file has the taxonomy of each ASV as generated in QIIME2 using the Silva taxonomy classifier.
- Helminth_Data.csv -- This dataset contains information on each frog including sample site information, microbiome diversity metrics, and helminth diversity metrics.
- Helminth_FullASVtable.csv -- This table contains sequence reads of each ASV split by sample. Samples are repeated for each individual for the skin and gut microbiomes.
- Helminth_Taxon.csv -- This file has the taxonomy of each helminth species included in our analyses.

## Description of Code
- Helminth_Analyses.Rmd -- This rMarkdown script has the code used to wrangle data, run statistical analyses, and contruct figures in this paper.
- Network_Analysis.Rmd -- This rMarkdown script has the code use to run co-occurence network analyses. Note: I have not finished fixing this code, I still need to make this work with a single input file.
