Subdirectory that contains all the data used during the project, as well as results.

1. Data folder - the raw data used in the project. Notice that files are compressed with zstd program. Source: https://github.com/CynthiaFlaire/USMF_Curs-Bioinformatica-2022_Datasets/tree/main/Kiril_Boiciuc
2. quants folder - stored the intermediate result obtained during the analysis of our data with the Salmon program.
3. homo.fa.gz - represents the reference fasta file of human transcriptome (cDNA) used for Quasi-mapping by the Salmon program. Source: http://ftp.ensembl.org/pub/release-106/fasta/homo_sapiens/cdna/Homo_sapiens.GRCh38.cdna.all.fa.gz
4. homo.gtf.gz - represents the gene annotation files of human transcriptome (cDNA) used for conversion of transcript name to gene name. Source: http://ftp.ensembl.org/pub/release-105/gtf/homo_sapiens/Homo_sapiens.GRCh38.105.gtf.gz
5. results.csv - the final result obtained during analysis. This file was used in the creation clustermap plot located in the figure subdirectory.
