# Tk genome project
Tigriopus kingsejongensis genome project
* Abstract

## Status of the project
* Tk_genome_v1 : Done and released.
* Tk_genome_v2 : Done and ready to release.

## Methods of Tk genome v2
### gDNA sequencing
* Library type : Short paired-end (PE), Long read (LR)
* Sequencing data : Illumina Miseq (KOPRI, https://www.kopri.re.kr), HiSeq 2500 (JS.Lee lab, http://tigriopus.skku.edu), PacBio Sequel CLR (JS.Lee lab)

### Preprocessing steps for raw reads
* Adapters and low quality reads removal (Trimmomatic, http://www.usadellab.org/cms/?page=trimmomatic)
* Error correction for raw reads (BBtools, JGI https://jgi.doe.gov/data-and-tools/bbtools)
* Contaminated raw reads from prokaryote and fungi (Tool : BBtools, DB : Refgen)

### **De novo** assembly
* Creating contigs (Flye assembler v2.8.1)
* Polishing the draft assembly (Pilon, https://github.com/broadinstitute/pilon)
* Read-based phasing (Whatshap v1)
* Assembly assessment (BUSCO v5, https://busco.ezlab.org/#software)

### Gene prediction and annotation
* Consturction of Repeat library (RepeatModeler : http://www.repeatmasker.org/, TEclass : http://www.compgen.uni-muenster.de/tools/teclass)
* Braker2
* Filtering annotated genes (In-house custom script)

## Results
### Statistics of the draft assembly
[stats table]

### Genome browser
* Tk v1.0 : http://210.218.217.114:8085/apollo/1/jbrowse/index.html (Powered by WebApollo & J-browser)
  * Now under maintenance.

### Download contents for Tk v1.0 gene information
* Available on the [release][release] section
* Tk v2 is in preparation and will be released soon.

[release]: https://github.com/macarima/Tk_genome_project/releases


