# An efficient method to remove contaminants from a genome assembly of small eukaryotic organisms: in a case of Tigriopus kingsejongensis genome assembly. 
Hui-su Kim* 

## Abstract
### Background
With advances in sequencing technologies, the cost and technical barriers for genome projects have been lowered. From this perspective, genome projects of small eukaryotic organisms can now be approached easily and shared resources can be utilized by science researchers. However, small eukaryotic organisms such as copepods and rotifers often do not yield sufficient amounts of DNA from a single individual. As a result, extracting DNA from the whole bodies of multiple individuals is necessary for genome sequencing. However, this can lead to contamination of sequencing data with viruses and bacteria from the sample's gut or skin, which can result in misassemblies. In this study, I introduce an efficient pipeline to remove contaminants from both short- and long-read sequencing data. As a case study, I applied the pipeline to clean short- and long-read data from a small copepod, Tigriopus kingsejongensis, and assembled its genome.

### Results
This pipeline removed 21% and 16% of contaminated short- and long-reads, respectively, from T. kingsejongensis sequencing. Using the cleaned reads, we assembled de novo assemblies of short-reads and long-reads separately. As a result, the de novo assembly of short-reads resulted in a total length of 196 Mb with an N50 of 819 Kb. The result of the long-reads assembly showed a total length of 227 Mb with an N50 of 2.7 Mb. The lengths of both assemblies were approximately the same as the estimated genome size according to k-mer analysis. From a quality assessment using BUSCO, this study acquired 11.3% complete genes with a bacterial OrthoDB (OrthoDB) and 97.6% complete genes with an Arthropoda OrthoDB. Without removing contaminants from the raw data, the Tk genome assembly acquired 150% of the length of the estimated genome size and 100% of the complete genes with a bacterial OrthoDB from the BUSCO analysis.

### Conclusion
I present a pipeline for removing contaminants from sequencing data and a case study for small copepods. It will support construction of more accurate genome assemblies for small eukaryotic organisms. 

### Keywords: removing contaminants; short-read genome sequencing, long-read genome sequencing, Tigriopus kingsejongensis
 
