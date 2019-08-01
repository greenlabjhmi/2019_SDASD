# 2019_SDASD

The codes to process and analyze FASTQ files obtained from the MS2 pulldown ribosome profiling, standard ribosome profiling, and RNAseq in “A Genome-Wide Analysis of the Role of Shine-Dalgarno Sequences in Promoting Translation in E. coli”. First run codes for data processings, then run codes for data analyses.

### Dependencies
* Tally
* skewer-0.2.2
* seqtk-1.0-r31
* bowtie-1.1.2
* free_align
* python 2.7’
* Anaconda2-5.0.1
* Jupyter notebook
* pickle
* numpy
* scipy
* pandas
* matplotlib
* seaborn
* R
* xtail

### Data processings
Each notebook contains codes which performe UMI screening and trimming, linker trimming, chromsome mapping, and calculation of RPM and RPKM.
* Skewer_Bowtie_Density_RPKM.ipynb - for ribosome profiling libraries with UMI 
* Tally_Skewer_Seqtk_Bowtie_Density_RPKM.ipynb - for ribosome profiling libraries with UMI
* Truseq_Bowtie_Density_RPKM.ipynb - for RNA-seq libraries

### Data analyses
* SDASD_Correlation.ipynb - creates scatter plots and calculates linear correlation 
* SDASD_DensityPlot.ipynb - creates density plots of normal ribosome profiling
* SDASD_Stresses_Xtail.ipynb - run xtail to compare effect of SD motifs between optimal and stress conditions
* SDASD_Stresses_VolcanoPlot.ipynb - creates volcano plots based on the results of xtail
* DASD_coupling_optimal.ipynb - 
	
	
	•	Analysis of coupled features, run “SDASD_coupling_optimal.ipynb” and “SDASD_coupling_cold.ipynb”.
	•	Initiation site analysis with retapamulin, run “SDASD_RET_DensityPlot.ipynb”, “SDASD_RET_AGP.ipynb”, and “SDASD_RET_ViolinPlot”.
