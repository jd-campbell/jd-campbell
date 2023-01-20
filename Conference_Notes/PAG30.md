PAG30: Jan 13-18, 2023
======================

Table of contents

  * [My Notes](##My-Notes)
     - [Funding Opportunites Panel](###Funding-Opportunites-Panel)
  * [Notes that other people took](##Notes-that-other-people-took)

## My Notes

### **January 14, 2023**

### __Funding Opportunities Panel__

### **January 15, 2023**

### __Computational Gene Discovery workshop__

1. __Mihaela Pertea: Efficient and Robust Transcriptome Reconstruction from Hybrid RNA-Seq Data__

     * StringTie2 using hybrid (long and short read) data helps clear up messy gene calls.
     * Hybrid data with using the annotation guide helps with the genome annotation. Simulated data shows that even using a little bit of isoseq is helpful for gene calls. [Research paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009730)

2. __TB: GeneMark-ETP__

     * GeneMark-ETP Prediction of gene transcripts and modeling training using the high confidence genes for final gene prediction. Gene clustering is a new feature of [GeneMark-ETP](https://t.co/vN28juc0yO)
     * GeneMark-ETP is fully automatic and utilize serval sources for prediction [Research paper](https://academic.oup.com/nargab/article/2/2/lqaa026/5836691?login=false)

3. __Lars Gabriel: BRAKER3__

     * Gene annotation is the task of finding protein coding genes and predict their gene structure using predictive and extrinsic evidence (ex. reads).
     * BRAKER is a pipeline with three inputs: Softmasked genome, Protein database and short read data. Uses both short read data and protein data and combines the data to make a more accurate gene calls.
     * BRAKER3 is available on [Github](https://github.com/Gaius-Augustus/BRAKER/tree/braker3) And most importantly they have created a container for BRAKER with all the dependancies so now BRAKER is easier to install!

4. __Stephane Rombauts: Object-Based Pan-Genome for Improving and Exploring Genomes__

      * Why Pangenomes? A single genome is a limited amount of data where a PanGenome is the sum of many genomes from the same species.
      * Object-based (eg. nodes) is anything that is anchored to a genomic region. The database uses [Vaticle Schema](https://docs.vaticle.com/docs/schema/overview)
     * Object-based pan-genomes defined syntentic regions and gene families and look closely at regions of interest.  System is focusing at the higher level. The database is still under development - visualization is also development.
     * SoyBase and LegumeInfo have a very similar Object-Based Pan-Genome Viewer called Genome Context Viewer (GCV)
      - [SoyBase GCV](https://gcv.soybase.org/instructions)
      - [LegumeInfo GCV](https://gcv.legumeinfo.org/gcv2/instructions)

5. __Roderic Guigo: Rapid Annotation of Protein-Coding Genes across the Tree of Life__

     * A large fraction of transcriptional output is isoforms and rationle to develop methods to predict a single protein coding isoform per gene. Develop the program called geneid in 2018. [Research paper](https://currentprotocols.onlinelibrary.wiley.com/doi/abs/10.1002/cpbi.56)
     * Now developing a new program called GeneidX. [GitHub](https://github.com/guigolab/geneidx)
     * GeneidX provides a fast annotation of the protein-coding genes in an eukaryotic genome taking as input the genome assembly and the taxonomic ID of the species to annotate.
     * GeneidX is easy to install using either Nextflow or Docker. Coming soon: a geneid [online portal](https://genome.crg.cat/geneid-predictions/#/)
 

### __Beyond the National Plant Genome Initiative workshop__

1. __Introduction__
     * The Beyond the National Plant Genome Initiative workshop is a forum for the plant genomics & genetics research community to reconnect & meet with representatives from the NSF, DOE, & USDA. 
     * NSF has a great way to search & find funding opportunities. [website](https://beta.nsf.gov/funding/opportunities)
     * Highly recommend that you send a one page summary about the project/idea & do not be afraid to contact the program officer (PO). The PO wants to help you get funded.
     * The DOE has a number of funding opportunities. DOE does support basic science as long it fits in the mission within DOE. [website](https://science.osti.gov/ber/Funding-Opportunities)
     * USDA-NIFA has a number of Program Officers (PO) attending and are here to talk to you and help fund your research.  NIFA has 82 different funding lines including ARFI, education, food science. [website](https://www.nifa.usda.gov/grants/programs)

2. __Richard Flavell: International germplasm improvement in the International Wheat Yield Partnership (IWYP)__

  * [Website](iwyp.org)
  * Hubs around the world drive technologies from state-of-the-art discovery into applied breeding programs, public and private. Hubs are interconnected to develop both Spring and Winter wheat.
  * The IWYP program has brought: 
     - More multi-disciplinary research w/ new ideas
     - Discoveries integrated w/ other discoveries around the world
  * But what is next? 
     - Scale of complexities w/ genomes and phenotype is vital for plant breeding 
     - Need more Digital support tools
     - Need to design and create new alleles/markers to make plant breeding more efficient
  * The purpose of crop and animal research is not to keep the data in a journal article. It is essential that the science get out to the public and private breeding programs. Getting the science out to the people is important.

3. __Ed Buckler: Wrangling Food System Nitrogen__

  * We need to start thinking about the entire system. Where is the nitrogen and Green House Gas (GHG) coming from in agriculture?
  * What to do about the atmospheric nitrogen? We have a leaky pipeline.
  * Developed the CERCA Circular Economy that Reimagines Corn Agriculture [website](https://maizegenetics.net)
  * CERCA strategies: Breeding for more nitrogen efficiency in root systems
  * Nutrient recycling: 
      - Season shifting it would be great if one day corn could be tolerant enough to be similar to winter wheat
      - Need to develop novel nitrogen  application system
  * Carbon Farming webinar from last year [slides](https://arpa-e.energy.gov/sites/default/files/2A_Panel_EB_KH_AK_SB_0.pdf)

4. __Jan Leach: Embracing the Complexity of the Phytobiome__

  * There are some troublesome trends in agriculture and we scientists need to think of novel ways to help food security. Interactions with the Phytobiome are dynamic and complex. [Research paper](https://nph.onlinelibrary.wiley.com/doi/full/10.1111/nph.17319)
  * To exploit the phytobiome when need to understand they system: How do plants sense stress? How do the microbes sense stress? Studies have shown that plants "cry for help" in response to stress and microbes come to the rescue. [Research paper](https://www.nature.com/articles/s41477-021-00967-1)
  * __How do we keep going forward?__ We need to embrace the complexity! Continued advancement in technologies in culturing, prediction modeling and simulations and synthetic biology Need many tools to validate and evaluate at a large scale.
  * Wish list:
     - Move beyond correlation to causation - to get to the mechanism 
     - Develop globally accepted standards for plant associate microbial #metadata
     - Train the next generation of scientist!


### __Manage your Big Data Workshop__

1. __Fiona McCarthy: __

2. __Matheus Krause__
  * Scanning PDF files from the USDA from 1941-2022 with more than 80 years of #Soybean trail data 
  * Challenges faced in data curation and cleaning:
     - Converting PDF files to standard format was difficult because of non-standard formats across the 80 years
     - Lots of Typos, genotypes and location names
     - One soybean line had 8 different names
     - Please don’t use special characters in the files.
  * [SoyURT package](https://cran.r-project.org/web/packages/SoyURT/SoyURT.pdf) and the data is available on [SoyBase.org](SoyBase.org)

3. __Chris Elsik: FAANGMine__
  * [FAANGMine](https://faangmine.elsiklab.missouri.edu)

4.  __Alenka Hafner: Data reuse and how it can benefit researchers__

  * Data reuse helps in preventing information/data loss, expanding scientific knowledge and benefits for authors. And now showing how data reuse is helpful in her current research. [Research paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7518187/)

5. __Monica Poelchau: Big Data Lifecycle in the USDA-ARS__

  * Provides long term storage for data and code and [Ag Data Commons](https://data.nal.usda.gov) provides a DOI for ease of finding.

### January 16, 2023

### __Tools and Resources workshop__

2. __Ana Conesa: Paintomics, a Tool for the Integrative Analysis and Visualization of Multi-Omics Data__

  * [Website](https://www.paintomics.org)
  * [Paper](https://academic.oup.com/nar/article/50/W1/W551/6591534?login=false)
  * [GitHub](https://github.com/ConesaLab/paintomics4)
  * Video tutorials available online

3. __Deborah A. Triant: MaizeMine A New Tools for Zea Mays Pangene Data Mining__

  * Recommend to log in because you can save the searches you conducted new data on MaizeMine from 25 NAM founder inbread lines; Pan-gene data; Search Tools; Query Builder; Create Lists.
  * [MaizeMine](https://maizemine.rnet.missouri.edu/maizemine/begin.do) has a column manager to add and remove columns to the search output. You can same the lists you created if you make an account. MaizeMine can enrich the list you create with ontology, publication and more.
  * You can used the save list to search the NAM lines and pan-genes in MaizeMine. Singleton Pan-gene templates can use the lists you created. When creating lists you can tag the list with keywords.
  * MaizeMine has multiple templates for searching multiple subjects for the NAM line founders. Data on MaizeMine to free to download. The community is free to contact MaizeMine for new query templates.

4. __Raghav Kataria: Weconet A Host–Pathogen Interactome Database for Deciphering Crucial Molecular Networks of Wheat-Common Bunt Cross-Talk Mechanisms__
  * [Research paper](https://plantmethods.biomedcentral.com/articles/10.1186/s13007-022-00897-9)
  * [Website](http://bioinfo.usu.edu/weconet/)

### __Data Resource Sustainability & Funding Workshop__ 

1. __Kenji K. Kojima: Repbase and the transition to subscription model__

  * "Online tools are becoming ever more important to biology, but financial support is unstable." Databases are important but finding is hard to come by and maintain. [Research paper](https://www.nature.com/articles/489019a)
  * Manual curation is important to maintain to high quality database like [RepBase](girinst.org/repbase/). Increase in data, increase in users, increase in downloads *BUT* decrease in funding. Now uses a fixed subscription model similar to TAIR to maintain database funding.
  * Challenges encountered
     - Keep eyes on unauthorized redistribution of data (often outdated data)
     - Often users need only a subset of RepBase
     - Manual curation needs time and expertise and can't keep up with the pace of data generation.
  * Efforts to face these challenges:RepBase is working towards the "gold standard" for repeat datasets; Increase the number of entries in RepBase.

2. __Mark Miller: Sustainability Strategies for the CIPRES Science Gateway__

  *  [CIPRES Science Gateway](https://phylo.org) was made help research get access to large HPC including Xsede. CIPRES helps researchers work on side projects by getting access to data resources. 
  *  CIPRES Science Gateway makes HPC available for biologist and research that do not have the access or expertise to complete large phylogenetic trees. [White paper](http://www.phylo.org/sub_sections/portal/sc2010_paper.pdf)

3. __Eric Lyons: CyVerse's Path to Financial Sustainability__

  * CyVerse helps with every step of the data collection, data management, and data analysis. Using other resources including iRODs, Jupyter, and R. CyVerse also workshops for education.
  * After federal grant funding decreased for CyVerse - Got help from many but the main take home message was: You can not do it and Focus on your main mission.
  * Three pathways for funding:
     - "Powered by CyVerse" Partnered with others
     - CyVerse Professional Services
     - [CyVerse subscriptions](https://cyverse.org/subscribe)

4. __Dorrie Main: Sustainability Efforts of NRSP-10 Crop Community Databases and Tripal Project__

  * [NRSP-10](nrsp10.org) is another major project that has been funded by federal funding for 10 years but now funding is decreasing and need to think about other sources of funding. NRSP10 is also getting funding from the industry and commodity groups.
  * Why are Crop Community Database important
     - Provide access to integrated, curated data and analysis tools
     - Promote data sharing and community building
     - Enable genomics, genetics and breeding.
  * As genomic, genetic and breeding data generation grew exponentially year by year and so does the number of people that use the database. 
 

### January 17, 2023

### __Soybean Genomics Workshop__

1. __Jianxin Ma: Rapid Evolution of Disease Resistance Genes in Soybean__

  * Soybean rot and stem rot causes an annual yield loss of $250 million USD and more than 1 million USD worldwide. Important to identify novel Rps because a number of known Rps genes have become partially effective or completely ineffective.
  * Rps1-k has lost resistance to the pathogen in Indiana. Using landrace #soybean for new source for resistance and IDed over 100 varieties that are resistance. And 23 soybean landraces found to be resistant to multiple pathogens.
  * PI 594527 carries an excellent resistance to P. sojae Mapped to Gm07 on Wm82. [Research paper](https://pubmed.ncbi.nlm.nih.gov/26660465/)

2. __Kyung Do Kim: Development of Molecular Marker Linked to White Soybean Cyst Nematode (Heterodera sojae) Resistance in Soybean__

  * GWAS studies for resistant to new cyst nematode species H. sojae (WSCN) in soybean - which is found in Korea, Japan and China. But H. glycine (SCN) is a problem around the world. [Research paper](https://apsjournals.apsnet.org/doi/full/10.1094/PHP-10-20-0094-BR)
  * Expansion of WSCN in Korea [Research paper](https://apsjournals.apsnet.org/doi/full/10.1094/PDIS-09-19-1932-SC)
  * Management of SCN by creating new resistance varieties [News Report](https://crops.extension.iastate.edu/cropnews/2021/10/scn-resistant-soybean-varieties-iowa-2022)
  * For WSCN GWAS study used the Koran core soybean collection. GWAS results showed 9 significant peaks 
6 significant SNPs found on Gm01 and candidate genes within Gm01 region expression was found in the roots. This could be a new resistance source 3 significant SNPs also found in the Rgh1 region on Gm18 [Research paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0224074)

3. __Aaron Lorenz: Developing Resources to advance genetic prediction soybean__ 

  * Using North Uniform Soybean Trail (NUST) data and it is available on [SoyBase.org](SoyBase.og) and [SoybeanBase] (https://soybeanbase.breedinginsight.net). 
  * For breeders Genomic selection (GS) can fast forward the breeding pipeline. GS saves
     - 4 years saved in parent section
     - 2 years saved in variety releases
     - Saves over $70,000 in land use.
  * Genomic prediction accuracy in SoyNAM variey from 20% to 50%. Genomic selection performs as effectively as phenotypic selection for increasing seed yield in soybean. [Research paper](https://acsess.onlinelibrary.wiley.com/doi/full/10.1002/tpg2.20285)
  * Challenges for academic breeding programs
     - Cost of genotyping
     - Turnaround time and Human resources (PostDocs and Graduate students + Temporary workers)
     - Risk of failure. 
  * Efforts to help the challenges -> Database development and training material
  
  * [SOYGEN](https://ncsrp.com/wp-content/uploads/2022/02/NCSRP-2021-Genetic-Gain.pdf): Science Optimized Yield Gains across ENvironments
  * SOYGEN using the NUST past and present data - again available on both [SoyBase.org](SoyBase.og) and [SoybeanBase] (https://soybeanbase.breedinginsight.net). 
  * Data from NUST is publicly available and the phenotypic data is available on [SoyBase](https://soybase.org/ncsrp/queryportal/)
  * More info about the NUST can be found [here](https://www.ars.usda.gov/ARSUSERFILES/50200500/NUST/2020%20NUST.PDF)

4. __Katy Martin Rainey: Genetic Improvement of Complex Traits in Soybean: Insights into Selection for Yield, Maturity and Seed Quality__

  * Using the well documented public #soybean resources at [SoyBase.org](SoyBase.org) including the SoySNP50K and SoyNAM.
  * Impact of increased sucrose content on overall seed quality in soybean Increasing sucrose content would likely lead to protein content sacrifices. Paper in review/No pre-print.

5. __Yong-Qiang (Charles) An:  Toward Understanding Molecular Basis of Seed Protein and Oil in Soybean Domestication and Improvement through an Integrative Data Driven Approach__

  * Introgression and/or improvements combination to increase desired traits. Embracing the BigData and integrative approach for breeding (alleles, functional markers, Germplasm) Focusing on soybean germplasm diversity
  * Multiple studies still finding seed quality QTLs: 
     - POWR1 (Protein, Oil, Weight, Regulator 1) is a domestication gene pleiotropically regulating seed quality and yield in soybean [Research paper](https://www.nature.com/articles/s41467-022-30314-7)
     - Fine mapping and cloning of the major seed protein quantitative trait loci on soybean chromosome 20 [Research paper](https://pubmed.ncbi.nlm.nih.gov/34978122/)
     - QTL for GmSWEET39 for oil and protein improvement [Research paper](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1009114)


## Notes that other people took
