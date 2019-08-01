# 2019_SDASD

The codes to process and analyze FASTQ files obtained from the MS2 pulldown ribosome profiling, standard ribosome profiling, and RNAseq in “A Genome-Wide Analysis of the Role of Shine-Dalgarno Sequences in Promoting Translation in E. coli”. First run codes for data processing codes, then run codes for data analysis.

### Dependencies:
Tally
skewer-0.2.2
seqtk-1.0-r31
bowtie-1.1.2
free_align
python 2.7’
Anaconda2-5.0.1
Jupyter notebook
pickle
numpy
scipy
pandas
matplotlib
seaborn
R
xtail


### Data processing 
Each note book contains codes which performe UMI screening and trimming, linker trimming, chromsome mapping, calculation of RPM, RPKM.
	•	For ribosome profiling libraries with UMI, run “Skewer_Bowtie_Density_RPKM.ipynb”
	•	For ribosome profiling libraries with UMI, run “Tally_Skewer_Seqtk_Bowtie_Density_RPKM.ipynb”
	•	For RNA-seq libraries, run “Truseq_Bowtie_Density_RPKM.ipynb”


### Data analyses
	•	Correlation analysis, run “SDASD_Correlation.ipynb”.
	•	Density plots for normal ribosome profiling, run “SDASD_DensityPlot.ipynb”.
	•	Differential SD-ASD effect in stress conditions, run “SDASD_Stresses_Xtail.ipynb” (R instead of Python) and “SDASD_Stresses_VolcanoPlot.ipynb”.
	•	Analysis of coupled features, run “SDASD_coupling_optimal.ipynb” and “SDASD_coupling_cold.ipynb”.
	•	Initiation site analysis with retapamulin, run “SDASD_RET_DensityPlot.ipynb”, “SDASD_RET_AGP.ipynb”, and “SDASD_RET_ViolinPlot”.
