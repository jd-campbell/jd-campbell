# PAG30: Jan 13-18, 2023
======================

### Table of contents

  * [My Notes](#My-Notes)
     - [Funding Opportunites Panel](###Funding-Opportunites-Panel)
  * [Notes that other people took](#Notes-that-other-people-took)
     - [Notes done by Bruno Contreras Moreira](###Bruno-Contreras-Moreira)

# My Notes

### __Tripal Database Network and Initiatives__



### __Funding Opportunities Panel__

  * The discussion panel strongly encourages early career researchers to contact the program managers (PM) if you have any questions about funding or grants. It is never too early to talk to a PM and find the best funding opportunities.
  * Program Managers recommend that the researcher send a one page about the research project. With the one page document the PM will be able to find a program that fits the research better or can help fine tune the project idea for the program to get funding.
  *  NSF and other Program Managers have Virtual office hours - [sign up for updates](https://debblog.nsfbio.com/office-hours/)
       * Past virtual office hours including the power point slides  are available. For example: Virtual Office Hours Recap – [How to Write a Great Proposal](https://debblog.nsfbio.com/2022/10/27/10-17-22-virtual-office-hours-recap-how-to-write-a-great-proposal/)
  * Developing & executing successful broader impacts 
       * Advancing Research Impact in Society [(ARIS)](https://researchinsociety.org) is a great resource and ask for help or connect you to people for helping with broader impacts
       * ARIS has a [Broader Impacts Toolkit](https://aris.marine.rutgers.edu/wizard/index.php)
       * When developing a broader impact connect the community at the beginning of the proposal you will have a greater impact.
  * NEW NSF initiative: Growing Research Access for Nationally Transformative Equity and Diversity (GRANTED)
       * GRANTED focuses on addressing systemic barriers within the nation’s research enterprise by improving research support and service

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
    * How do we keep going forward?
        - We need to embrace the complexity! Continued advancement in technologies in culturing, prediction modeling and simulations and synthetic biology Need many tools to validate and evaluate at a large scale.
    * Wish list:
         - Move beyond correlation to causation - to get to the mechanism 
         - Develop globally accepted standards for plant associate microbial #metadata
        - Train the next generation of scientist!


### __Manage your Big Data Workshop__

1. __Fiona McCarthy__

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

     * [CIPRES Science Gateway](https://phylo.org) was made help research get access to large HPC including Xsede. CIPRES helps researchers work on side projects by getting access to data resources. 
     * CIPRES Science Gateway makes HPC available for biologist and research that do not have the access or expertise to complete large phylogenetic trees. [White paper](http://www.phylo.org/sub_sections/portal/sc2010_paper.pdf)

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

### __Bruno Contreras Moreira__ 
(Research focus: Computational biology and plant genomics)

   * [Saturday, Jan 14, 2023](https://bioinfoperl.blogspot.com/2023/01/notes-on-plant-and-animal-genomes.html)
   * [Sunday, Jan 15, 2023](https://bioinfoperl.blogspot.com/2023/01/notes-on-plant-and-animal-genomes2.html)
   * [Monday, Jan 16, 2023](https://bioinfoperl.blogspot.com/2023/01/notes-on-plant-and-animal-genomes3.html.html)
   * [Tuesday, Jan 17, 2023](https://bioinfoperl.blogspot.com/2023/01/notes-on-plant-and-animal-genomes4.html)
   * [Wednesday, Jan 18, 2023](https://bioinfoperl.blogspot.com/2023/01/notes-on-plant-and-animal-genomes5.html)


### __Hyunoh Lee__
(Research focus: Computational biology, legumes, disease traits)

##################
##### Legume #####
##################
## The circadian clock in the control of flowering regulation in soybean
- How to change gene regulatory network level
- Approach 
    Network discovery based on RNA-seq: change various temperature against G. max and G. soja
    Photoperiod affects flowering genes significantly
    Temperatures affect some flowering genes
    inferred network using CausNet program and oCES algorithm
    ==> Temperatures affect inferred networks more thang photoperiod
- Experimental verification
    qPCR
    Mutagenized using CRISPR-Cas9
    ChIP-qPCR and ChIP-exo seq
    GmPRR5/9-3 is upregulate
    GmLCL3 upregulate GmPRR3
    ==> PRR5/9-3 is promoter of PRR3 and PRR5/9 genes
- Poster
    PE0324 and PO0331

## Breeding Legumes for diverse cropping system
- Diversity in time
    within growing season
    Multi-year rotation
- Diversity in source
    Field-scale diversity
    Landscape-scale diversity
- Declining diversity of US cropland
- Increasing spatial concentration of US crop production
- Designing for diversity
    Depending on time and space
- Poster
    PO0426: Genetics environment and GxE of cover crop
- Planting date for winter survival
    NY, MN, ND
    Mid to late September planting produced greatest spring biomass
- Red clover inter seeding
- Alfalfa perennial grain system

## Opportunities to implement genomics-assisted breeding in a common bean breeding program
- common bead / dry bean / dry edible bean
    dry bean has complex evolutionary and domestication history
    has two gene pools
- canning quality
    Phenotype
- Genome prediction: motivation & justification
    can reduce cost of phenotyping
    reference population is key
    (Black, navy, red)
    then, evaluating genomic prediction: yield, canning quality, white mold
- SNF (Symbiotic nitrogen fixation)
    can decrease the dependency on organic and synthetic fertilizer
- Engineering microbiomes to improve plant and animal health - French collaborator

## Breaking a bottleneck to biological nitrogen fixation in soybean: potential plant reward mechanism for beneficial rhizobia
- Contribution of biological N fixation to plant N uptake might be lower in high yielding environment
- Potential solution: Enhance colonization by high efficiency rhizobia
- rhizobia strain: USDA110 (high N-fixation) / USDA126 (low N-fixation)
- Early USDA110 inoculation increased chlorophyll content, Co2 fixation shoot dry weight
- Earlier colonization by USDA126 is a carbon drag
- Autoregulation of nodulation pathway in soybean

## Prospects for increasing rates of genetic gain in pulse crops
- Field pea, dry pea, chickpea, lentil
- Pulse crops and soybean are evolutionary related but have distinct lineages (warm-season, cool-season legume)
- Pulse crops were mainly produced at North Dakota and Montana 
- High throughput phenotyping (HTP): drone(canopy traits), photo booth(assign seed quality), rover
    Maturity date, diseases
- Aphanomyces root rot is a devastating disease
- Are the HTP indices biologically meaningful? => Yes,
- HTP applied to predict new breeding line (resistance line)

#################################
##### Comparative genomics #####
#################################
## Exploitation of multiple facets of comparative genomics in the study of non-model crops
- Previous: RFLP, crop circles (1995 pag meeting)
- flowering time QTL in switchgrass (PvHd1 = ortholog Hd1 in rice)
- CER6, wax QTL
- finger millet: blast disease in rice
    PWL1, PWL2 genes cl control resistance
- Discovery of conservation of gene orders => major milestone

## Evolving at a rapid Clp: using correlated rate of evolution in plant genomes to detect genetic interactions - Dan Sloan
- The plastid caseinolytic protease (Clp) complex
- Coevolution produces correlations
- Correlated accelerations in Angiosperm Clp neclear genes
- Identification of novel Clp complex interaction based on protein-protein interaction

## Evolution of the small but metabolically mighty pretty spurge genome
- Euphorbia peplus (biofuels, rubber, medicines)
- HiFi, Hi-C, 267.2 Mbp, 25,471 genes
- E. peplus has 8 Chr, E. lathyris has 10
    => Aneuploidy is quite effective in speciation
- Chromosome fragmentation, not duplication & diploidization
- E. peplus has low transposon elements
    Ty3s are low across evolutionary time
- Diterpenoid biosynthetic cluster
    Two cluster independently identified using BAC library
    Two clusters are contiguous
- eFP expression browser

## The barley pangenome
- Previous: 2012, 2017
- Hulless barley: SV at the Nud locus
- Pangenome is consist of core, shell, cloud
- How to pick genotype to represent a pangenome?
    It's up to your purpose
- Barley pan genome (20 genomes) v1 (2020)
    40,176 orthologous group of genes
- Barley pan genome v2
    20x Hifi + Hi-C
    76 genotypes (including 20 genotypes of v1)
    Large Sv are a frequent feature in the barley genome
- Single copy pan-genome of domesticated barleys
- Further
    PACBIO Revio + Novaseq X
    Do we need more genotype?

## Comparative genomics of Einkorn wheat
- 2n = 2x = 14, domesticated around 1000 years ago
- introgression account for around 1% of the bread wheat genome

####################################################################
##### Crop evolution & genomics future agricultural production #####
####################################################################
## Unraveling the genetic provides insights into the early history of domesticated wheat (Muru)
- optimize of cost-effective genotyping-by-sequencing (GBS)
- up to 2,000 accession -> Genebank genomics & pangenomics

##############################
##### Cool season legume #####
##############################
## Running wild: Assembly and comparative analysis of Lentil and wild relative genome
- ~50x ONT, Hi-C, genetic map
- Improved assembly
    ~25x HiFi, 1635 contigs, about 3.8Gbp
- Chr 7
    break linkage

## innovative genotyping of the large & repetitive lentil genome
- Characterization of large genetic resource of four food-legume
- GBS - [iGENOMX]- WGS
- iGenomx 
    Higher number if common genotypable position
    including repeats
- Depletion of repeats by CRSPR/Cas9
- Increased number of identified variants upon Cas9 repeat-depletion

## Uncovering the genetic basis of domestication traits in Cicer hybrid using nested association mapping
- Prolonged selection has shrunk the genetic diversity in cultivated chickpeas by ~98%
- 8 continuous and 8 categorical traits
    Traits show strong pairwise correlation
- GWAS model: farmCPU

## Multiple genome assemblies of Cicer wild species provides insights into chickpea pangenome dynamics and their evolution
- 2n=16
- Chickpea pangenome reported at 2021 (Varshney et al.)
- Toward genus level pangenome and super-pangenome
- Whole genome alignments of Cicer wild genomes against cultivated genome
- Pangenome
    530 Mbp
    25008 gene families
        core: 14,748
        soft core: 2958
- CicerPanDB
- Improvement in the graph-genome approach will help to integrate more variations from different species

########################################
##### Computational gene discovery #####
########################################

## End to End learning of evolutionary models to find coding regions in genome alignments (ClaMSA)
- Phylogenic model
    continues tune markov chain
    case 1: PAML (codeml)
    case 2: phyloCSD
- Aim: discriminative, arbitrary number of full rate matrices, drop independence of site assumption, sequence model
- ClaMSA - machine learning of continuous-time markov chains
    new ML TensorFlow layer: pruning algorithm
    [CTMS layer] codon alignmentX -> [prediction layers] recurrent neural net -> fully connected MN
    phreshold  > 50% 
    => fewer false classification than others (93.6 % in vert / 92.3 % in fly)
    => more accurate
    => performs well cross-clade
    => accuracy largely attributable to a evolutionary model
- mext set[: discover new coding sequences, AUGUSTU-CGP connection, evolutionary signal finding

## Efficient and robust transcriptome reconstruction from hybrid RNA-seq data
- previous: cufflinks, stringtie, stringtie2 (supported long-read)
- Limitations of long-read RNA-seq
    much higher error rates
    much lower throughput makes quantification of all (impossible highest-expressed gene)
- Long read error correction WITH [TALC]
- StringTie2
    more efficient bit-vector representation of splice-graph
    filter low-quality alignments
    corrects errors
- Hybrid assembly is much better

## GenMark ETP: automatic gene finding in eukaryotic genome
- RNA evidence protein evidence, intrinsic evidence (ab initio)
- training of a genomic GHMM model
    high confidence (HC) gene -> training -> map to genome -> low GC / medium GC / high GC -> predict genes in the non-HC
- even though GC-heterogeneous genomes, GeneMark-ETP is more accurate than previous version (any combination)
- Comparison
    TSEBRA (BRAKER1, 2)
- positive
    fully automatic, simultaneously utilize several sources of extrinsic evidence, more accurate

## The BRAKER3 genome annotation pipeline
- evidence: nucleotide, RNA-seq reads, homologous proteins
- previous: BRAKER
    prediction tools: genemark, augustus
- TSEBRA: combiner tool for BRAKER predictions
    transcript selector for BRAKER
- BRAKER3
    integrate RNA-seq, protein into prediction
- HALBA
    genome.fa + protein.fa -> miniorit -> augustus -> augustus.gtf
- summary
    BRAKER 1 and 2 are depending on available extrinsic evidence, executes one of three pipelines
    BRAKER3: much higher accuracy

## Object-based pangenome for improving exploring genomes
- object-graph
- database input: node. links (relative chromosome position, synteny..)
- bubbles
    consider a query extracting the (whole) synteny-graph, look for patterns of interest
- conclusion
    build hairball (graph database) -> visualize properly -> investigate areas of interest -> detailed view vcf

##########################
##### Abiotic stress #####
##########################
## genomic and epigenomic novelties for adaptive traits in rice
-transgressive segregation is a source of phenotypic novelties through natural evolution and plant breeding
- fundamental questions
    Genome shock
        disturbances to the genome brought about by allopolyploidy
    epigenome landscape of the resulting recombination?
- FL5110 is the most hypomethylated (CHG, CHH) relative to the parents
- Hi-C suggests a more relaxed configuration in certain regions of FL510 genome
- FL510 is more uniform and even distribution of TAD
=> epigenome appears to have an important role in transgressive segregation

## Gene-to-filed characterization of WLT1 in waterlogging tolerance and yiel protection in soybean
- waterlogging stress: saturation of water in soil
- two QTLs were detected on a cross of S99-2281 x PI 561271
    qWT_Gm03 is major QTL
        regulates root growth and plasticity
- Fine mapping (map-based gene cloning)
- WLT1 preferentially expresses in roots and induced by waterlogging
    whereas wtl1 is not due to variation of promoter

- R-motif works together with uORFs to regulate mRNA translation
    have to find detail mechanism (cell specific. conditional, biological replications...)
- Tolerant allele WLT1-1
    tends to accumulate in the wet regions
    improves yield
    helps nutrient uptake

## Drought adaptation in chickpea: the mystery of "QTL-hotspot" explained
- deeper roots increase water uptake
- QTL-hotspot regions were identified through MABC
    12% increase in yield
- Fine mapping using KASP marker
- Three candidate genes
    CaTSJT1, CaARD1, CaTIFY4b
- QTL hotspots improve yield performance (seed weight and root architecture)) under rainfed field condition

## Identification of genotypic variation for diurnal and development stage-specific transpiration pattern under drought stress conditions in wheat
- Drought tolerance is context-dependent
- VPD (vapor pressure deficit)
    driving force on transpiration
    water is saved & available during anthesis & grain filling -> higher yield
- Genotype ranking for TE changed in different developmental stage
- Transpiration response to high VPD and VPD related to other traits
- delayed senescence in genotypes with late but strong restriction of transpiration rate -> Higher TGW

## Designer crops for future environments
- speed up the development of climate resilient crops
    use genome editing
- Engineering roots to improve water and nutrient uptake
    novel root traits in Medicago and Arabidopsis
    low-cost rhizobox
- Accelerated breeding to modify root traits
    modified root angle and biomass in wheat
    using KASP marker for root biomass QTL
    intro-selection line displayed altered root distributions
    UAV canopy phenotyping
=> we need to fine-tune trait expression

##############################################
##### Polyploidy across the tree of life #####
##############################################
## Co-occurrence of diploid, tetraploid genotypes and their SNP alignments in the Chrysanthemum arcticum species complex
- C. arcticum, C. a. subsp. arcticum, C. a. subsp. polare
- Reference: C. nankigense (2n=2x=18)
- In case of C. a., 119/234 (about 50%) genotypes did not fall within diploid~pentaploid
- C. a. complex has a rege of ploidy

## Pangenomic variation across autotetraploidy Vaccinium corymbosum (blueberry)
- 12 northern + 12 southern + 12 cranberry -> assembly -> annotation -> progressive Cactus whole genome alignment + orthofinder2
- Blueberries
    Ploidy (3~4 copies)
- W85
    Diploid

##################################
##### Domestication genomics #####
##################################
## The evolutionary history of Phaseolus vulgaris as revealed by chloroplast and nuclear genome
- 2n=2x=22
- Pool
    Mesoamerican, north Peru & Ecuador, Andean
- Goal: to clarify the phylogeny using nuclear and chloroplast DNA
- Nuclear level
    10 accessions were distinguished three wild gene pools
    phylogeny of Chr 1 and 3 were not enough to make inference about the origin
- Chloroplast level
    70 wild accessions
    represented BAPS structure, MDS, Haplotype network
    assembled 37 cp genomes
- P. vulgaris is Mesoamerican origin

##########################################################
##### Next generation genome annotation and analysis #####
##########################################################
## Using representative gene sets to validate gene models in legume annotations (Fabaceae)
- conserved gene sets are used for validate genome
    regardless if genome is under-studied
- Even high quality assembly, there are annotation errors

#########################################################################
##### Genomics for sustainable agriculture and global food security #####
#########################################################################
- climate change, over-population
- Green revolution: increased cereal yield 241 %
- Global fertilizer consumption 
- Legumes are important crops for diversification and sustainability of cropping system
    Chickpea, Pigeon pea, groundnut
- Improved legume genomes
- Pangenome -> super pan genome
- Germplasm sequencing
- Global chickpea variation map using 3,366 genomes
    21.33 Tb of WGS
    3.94M SNP in 3,171 cultivate and 19.57 M SNPs in 195 wild accessions
    592Mb
- Genotyping platforms
    SSR, DArT, KASPar, GBS, SNPs array, WGRS, SNPs penel, SNps array
- High Through-Put Genotyping (HTPG) project
- Trained breeders in GAB
- Tropical legume project
- Future
    Haplotype-based breeding, Spatial transcriptomics

Affinity optimizing enhancer variants disrupt development and drive disease

- Enhancers act as switches to turn transcription on and off thus directing the program of development
- Single bp changes within enhancers have dramatic effects
    disease and developmental defects
    evolutionary adaptations
    malaria susceptibility
- Are there overarching rules governing how enhancers encode tissue specific expression?
- Low-affinity ETS sites are necessary for heart expression
- optimizing the affinity of the ETS sites leads to loss of tissue specificity
    single base pair changes cause
        increase affinity
        ectopic expression
        migration defects



Actionable genomics at scale

1. HiFi sequencing
    Revio
        100M ZMW/run, 4 independent stages
        25-hr
        360 Gb
    - Genome annotation with Iso-Seq
        IsoPhase (SNPs only), DeepVariant (SNPs & indels)
    - Methylation detection
        PRIMROSE: HiFi-bssed methylation calling
    - 5-base HiFi sequencing in plant
    - Single-molecule, long0range chromatin architecture
    - cell atlas, single-cell sequencing
        MAS-Seq: high-throughput, full-length single-cell sequencing
    - short reads are no longer needed for cell type clustering
    - Can do GBS, gene editing specificity analysis

- SBB sequencing
    Onso

2. Ultra-high throughput workflow for agronomic application (CORTEVA)
- Genomics enabled germplasm characterization
- Revio HiFi data quality is equivalent or better than SQlle data

3. Conserving Californiaâ€™s biodiversity with genomics
- Neutral variation unforms us about population structure, gene flow, hybridization, demography, standing variation (genetic health/resilience)
- genes under selection inform us about adaptation

4. New breeding technologies to deliver better Sorghum could possibly go wrong?
- pan-genome
    PAV
- manipulating (transformation)
    protein digestibility, content, grain size
- bootsting editing efficiencied in sorghum, barley, maize
- focus: grain quality
- Foldase knockout lines maintained high protein and grain size in the filed
    GGC1: high protein and grain size
    GGC2: variable
    GGC3: poor heat tolerance during gain fill
- Poultry (chickens)
    the fastest growing protein phenomenon
- beta-kafrin KO triggers increases in gamma-kafirin
    when we get gamma-kafirin -> higher protein digestibility

5. Digging for DNA: archaeological sediments as a source of ancient animal and plant genomes
- Ancient environmental DNA
    past biodiversity
    first/last appearance dates
    insights on human behavior
- Characterizing ancient DNA
    modern DNA / ancient DNA: C to U change
- mtDNA in sediments
- Nuclear DNA


__Soybean Genomics__

1. Rapid Evolution of Disease Resistance Genes in Soybean
- phytophthora root and stem rot is one of the most destructive disease
- Rps1-k has lost resistance to the predominant P. sojae isolate in indiana
- 23 new resistance accessions
- PI 593527 carries excellent resistance to P. sojae (including indiana)
    new Rps gene, designated Rps11
    there are gaps and wrong assemblies of the mapped region in the reference genome
    R1 to R12 identified by Wm82 PacBio de novo
    Fine mapping
        genotyping: 2643 F3, 7680 F4, 6730 F4
    very big size about ~29 kb
- Rps 11
    origin: Chr07
    belong to giant NLR cluster
    intra and intergenic recombination, resulting in promoter fusion and LRR domain expansion
    Segmental duplication
    Haplotypic variation in copy number and structure of NLR genes: 1 to 4 groups
        RPS11 is group II

2. Genome-Wide Association Study for Resistant to New Cyst Nematode Species Heterodera Sojae in Soybean
- Soybean cyst nematode
- H. sojae is closer to rice cyst nematode
- H. glycines resistant genotypes
    Peking-type
    PI88788-type
- GWAS
    Chr 07
- Candidate genes adjacent to significant SNPs
    Chr 01 and 18
- KASP markers linked to H. sojae resistance are developed
- Candidate genes found on Chr1 can be a new resistance H. sojae

3. Developing Resources to Advance Implementation of Genomic Prediction in Soybean
- Genomic prediction accuracy in SoyNAM (40 biparental pops)
    not always great
- Enhance capability of putting genomic selection in practice for public university soybean breeding programs
- SOYGEN
    elevate collaborative filed trials
    evaluation and comparison of GAB
    develop and test methods
- Publicly available data - NUST
    Soybase, SoybeanBase

4. Genetic Improvement of Complex Traits in Soybean: Insights into Selection for Yield, Maturity and Seed Quality
- increased sucrose content
    quantitatively increasing sucrose content would likely lead to protein content sacrifices.
    Tradeoffs of sucrose with protein and oil with protein hamper efforts to improve seed quality
    not correlated with seed size
    correlation with protein and seed size are primarily driven by their additive genetic correlations
    lowest h2 with population and environment specific determination
- Identifying small effect QTL for time to flowering, maturity, and reproductive, length
    Rationale
    E1 to E4 explain 62-66% of the flowering time
- Spatially adjusted traits (SP) and canopy coverage data (canopy) were the more effective sources of information for selecting high yielding lines

5. Toward Understanding Molecular Basis of Seed Protein and Oil in Soybean Domestication and Improvement through an Integrative Data Driven Approach
- Three major QTL: Chr 15. Chr20A and B
- Whole genome re-sequences of 1,500 accessions
- TE insertion in a CTT-domain gene underlying QTL on Chr20B
- TE truncates CCT domain with no or little expression
- POWR1 (seed protein, oil, weight, and yield regulator 1) is domestication gene


     
