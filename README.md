Group 3 ABCC Reproducing a RiboSeq Pipeline

cat > README.md << 'EOF'
# Group 3 ABCC Reproducing a RiboSeq Pipeline


## Overview
Aims to reproduce the RiboSeq analysis pipeline (Radhakrishan et al., Cell 2016) using Python 3.8 and modern software versions
Assess reproducibility of pipelines and worklow 
Document challenges encountered

## 2 Pipeline
### 1. Data Processing, QC, and Metagene Analysis and Visualisation
### 2. P-Site Correction and Comparative Analysis

## Data
- **Source:** E-MATAB-6938 (ArrayExpress)
- **Samples:** 8 FASTQ files
- **Organism:** *Saccharomyces cerevisiae*

## Software Versions 
- Python 3.8
- Cudatadapt 4.9
- Hisat2 2.2.1
- Bowtie2 2.4.5
- Samtools 1.17

## Challenges fixed - see **challenges.md** for a detailed documentation

## To use
'''bash
conda activate riboseq
python Pipeline_part_1.py
python Pipeline_part_2.py

## Results

