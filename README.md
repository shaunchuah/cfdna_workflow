 To run the analysis, place the demultiplexed files in 4_identified_fastq with the SAMPLEID_PATIENTID as foldername
 Open terminal in scripts
 Change environment to nanoplot_env (conda activate nanoplot_env)
 Run command: snakemake -p
 All commands in scripts/Snakefile will execute

snakemake -np for test run without execution