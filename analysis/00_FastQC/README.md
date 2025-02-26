
#code to run fastqc
fastqc /workdir/xw722/SalinityGradient_16S/data/01_DADA2/01_raw_gzipped_fastqs/*.fastq.gz --threads 5 -o /workdir//xw722/SalinityGradient_16S/analysis/00_FastQC/fastqc_report/

#code to run multiqc
multiqc fastqc_report/ -o multiqc_result/ 
