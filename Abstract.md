# An efficient method to remove contaminants from a genome assembly of small eukaryotic organisms: in a case of Tigriopus kingsejongensis genome assembly. 
Hui-su Kim* 

## Abstract
### Background
With advances of sequencing technologies, the cost and technical barriers in genome projects have been lowered. From that point of view, a genome project of small eukaryotic organisms enabled easy approach and shared useful resources to science researchers. However, small eukaryotic organisms such as copepods and rotifers often fail to supply sufficient amount of DNA from a single individual. Therefore, extracting DNA from whole body of multiple individuals should be required for genome sequencing. However, this could allow contamination of sequencing data with virus and bacteria from the sample’s gut or skin, which will result in misassemblies. In this study, I introduce an efficient pipeline to remove contaminants from both short- and long-read sequencing. For a case study of the pipeline, I cleaned short- and long-read data from a small copepod, Tigriopus kingsejongensis, and assembled its genome.

### Results
This pipeline removed 21% and 16% of contaminated short- and long- reads from T. kingsejongensis sequencing, respectively. Using cleaned reads, we assembled de novo assemblies of short-reads and long-reads, separately. As a result, the de novo assembly of short reads resulted in a total length of 196 Mb with an N50 of 819 Kb. The result of long reads assembly showed a total length of 227 Mb with an N50 of 2.7 Mb. The lengths of both assemblies represented approximately in the same estimated genome size according to k-mer analysis. From a quality assessment using BUSCO, this study acquired 11.3% complete genes with a bacterial orthologous DB (OrthoDB) and 97.6% complete genes with an Arthropoda OrthoDB. Without removing contaminants from raw data, Tk genome assembly acquired 150% length of estimated genome size and 100% of complete genes with a bacterial OrthoDB from the BUSCO analysis.

### Conclusion
I present a pipeline for removing contaminants from sequencing data and a case study for small copepods. It will support construction of more accurate genome assemblies for small eukaryotic organisms. 

### Keywords: removing contaminants; short-read genome sequencing, long-read genome sequencing, Tigriopus kingsejongensis
 
