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

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |
