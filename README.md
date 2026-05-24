# Project_Research_Scientist-I-ICMR-SBST-Dr._George_Priya_Doss-06-May-2026
Explainable Artificial Intelligence (XAI) to Identify Synergistic Antimicrobial Combinations for the Treatment of Carbapenem-Resistant Acinetobacter baumannii 
https://careers.vit.ac.in/vit/jobview/project-research-scientist-i-icmr-sbst-dr-george-priya-doss-vellore-institute-of-technology-tiruvalam-road-katpadi-vellore-tamil-nadu-india-knowledge-and-experience-in-the-development-of-interpretable-machine-learning-models-with-human-understandable-features-2026050614304589

# Acinetobacter baumannii
Acinetobacter baumannii is a species of g-proteobacterium in the family Moraxellaceae.
## Taxonomy ID: 470

# 25 Hits in National Center for Biotechnology Information (NCBI)
https://www.ncbi.nlm.nih.gov/search/all/?term=Acinetobacter+baumannii
<img width="1525" height="856" alt="Acinetobacter_baumannii" src="https://github.com/user-attachments/assets/8d1108c3-ca34-4ec7-80e7-d0c8b5239a32" />

# DownLoad RefSeq Reference Genome using NCBI-datasets-CLI-tool
```
sharma@bioinformatics ~/V/p/i/2/2/prs1_georgepdas_xai6may26> datasets download genome accession GCF_009035845.1 --filename Acinetobacter_baumannii.zip

New version of client (18.28.0) available at https://ftp.ncbi.nlm.nih.gov/pub/datasets/command-line/LATEST/linux-amd64/datasets.
Collecting 1 genome record [================================================] 100% 1/1
Downloading: Acinetobacter_baumannii.zip    1.19MB valid data package
Validating package files [================================================] 100% 5/5
sharma@bioinformatics ~/V/p/i/2/2/prs1_georgepdas_xai6may26>                                                                                        (Contact0091isd9625148079)
```
# Sequence Statistics of Acinetobacter_baumannii
```
sharma@bioinformatics ~/V/p/i/2/2/prs1_georgepdas_xai6may26> unzip Acinetobacter_baumannii.zip                                                      (Contact0091isd9625148079) 
Archive:  Acinetobacter_baumannii.zip
  inflating: README.md               
  inflating: ncbi_dataset/data/assembly_data_report.jsonl  
  inflating: ncbi_dataset/data/GCF_009035845.1/GCF_009035845.1_ASM903584v1_genomic.fna  
  inflating: ncbi_dataset/data/dataset_catalog.json  
  inflating: md5sum.txt              
sharma@bioinformatics ~/V/p/i/2/2/prs1_georgepdas_xai6may26> seqkit stats GCF_009035845.1_ASM903584v1_cds_from_genomic.fna.gz                       (Contact0091isd9625148079) 
file                                                 format  type  num_seqs    sum_len  min_len  avg_len  max_len
GCF_009035845.1_ASM903584v1_cds_from_genomic.fna.gz  FASTA   DNA      3,736  3,508,575       63    939.1   18,543
sharma@bioinformatics ~/V/p/i/2/2/prs1_georgepdas_xai6may26>                                                                                        (Contact0091isd9625148079)
```
