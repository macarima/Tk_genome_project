# Tk_genome_project
Tigriopus kingsejongensis genome project

## Methods

### gDNA sequencing
* Library type : Short paired-end (PE), Long mated-pair (MP)
* Sequencing methods : Illumina Miseq, HiSeq 2500

### Preprocessing steps for raw reads
* Adapters and low quality reads removal (Trimmomatic, http://www.usadellab.org/cms/?page=trimmomatic)
* Nextera adapters removal (Skewer, https://github.com/relipmoc/skewer)
* Error correction for raw reads (BBtools, JGI https://jgi.doe.gov/data-and-tools/bbtools)
* Duplicated reads removal (FastUniq, https://sourceforge.net/projects/fastuniq) 
* Contaminated raw reads from prokaryote and fungi (Tool : BBtools, DB : Refgen)

### De novo assembly
* Creating contigs (Platanus, http://platanus.bio.titech.ac.jp/)
* Reconstruction of high polymorphic region (HaploMerger2, https://github.com/mapleforest/HaploMerger2)
* Polishing the draft assembly (Pilon, https://github.com/broadinstitute/pilon)
* Assembly assessment (BUSCO v3, https://busco.ezlab.org/#software)

### Gene prediction and annotation
* Braker1 (http://exon.gatech.edu/braker1.html)
* Maker pipeline with BUSCO, SNAP, AUGUSTUS, GeneMark
* Consturction of Repeat library (RepeatModeler : http://www.repeatmasker.org/, TEclass : http://www.compgen.uni-muenster.de/tools/teclass)
* Filtering annotated genes (In-house custom script)
* Manual annotation (Web-apollo, http://genomearchitect.org)

## Results

### Statistics of the draft assembly
| |Tk v1 assembly|
|---|---:|
|Scaffolds No. | 1,066|
|Total length (bp)| 196,471,422|
|N50 (bp)| 818,552|
|Max contig length (bp)| 4,767,029|
|Gap| 2.91%|
|GC contents| 45.87%|

### Genome browser
* Tk v1.0 : http://210.218.217.114:8085/apollo/1/jbrowse/index.html (Powered by J-browser)

### Download contents for Tk v1.0 gene information
* Available from BioDisk (KOGIC, UNIST)
[Tk_assembled_genome_sequence][Tk_assembled_genome_sequence]

* Tk v1.1 is in preparation.
[Tk_assembled_genome_sequence]: ftp://biodisk.org/BiO/Tk_polar/Tk_genome_v1.genome.fa.gz
