# *Orbicella faveolata* PacBio Genome and Transcriptome
All analysis scripts for genome and transcriptome assembly of Orbicella faveolata using PacBio long read sequencing. 

NCBI Project - https://www.ncbi.nlm.nih.gov/bioproject/PRJNA970355  
Manuscript Link - https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-024-10092-w  
Zenodo repository - https://zenodo.org/records/10151798 
  
*ofav_genome_pipeline.Rmd* - full pipeline for genome assembly, transcriptome assembly, and annotation. 

![12864_2024_10092_Fig4_HTML](https://github.com/user-attachments/assets/d268f9a7-5461-427a-82f1-c9b4213c98db)
Visualization of scaffolded genome assembly of Orbicella faveolata. A. GC content calculated with a sliding window of 50,000 base pairs (bp). Y-axis shows the percentage calculated for GC content over each 50,000 bp sliding window. B. Repeat content plotted using a sliding window of 50,000 base pairs and the gff output file from RepeatMasker. Y-axis shows counts of repetitive regions for each sliding window of 50,000 base pairs. C. Telomeric repeats generated with a sliding window of 50,000 base pairs and the repeat pattern of “TTAGGG”. Y-axis shows the counts of the telomeric repeat for each sliding window of 50,000 base pairs. Telomeric repeats can be identified by peaks at either the start or end of each scaffold. D. Gene density calculated with a sliding window of 50,000 base pairs and the “gene” identifiers from the gff file generated from funannotate::annotate. Y-axis shows the counts of genes for each sliding window of 50,000 base pairs
