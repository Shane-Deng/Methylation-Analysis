# Methylation_project overview

## Aim
This project is designed to advance our understanding of methylation patterns across genomes, specifically focusing on distinguishing between normal and cancerous methylation. The primary goal is to extract methylation locations from genetic data and utilize a machine-learning model to differentiate between normal and cancerous methylation states.

## Components
The project consists of two main programs and some small programs:
1. **Methylation Location Extraction (unt_trimmed_bin_analysis_bam_v1.9.py)**: A program developed to accurately identify and extract methylation sites from genetic sequences. This involves analyzing genetic data to pinpoint specific methylation locations, which are crucial for understanding gene expression and regulation.

2. **Machine Learning Model for Methylation Analysis (machine_methyl.py)**: A sophisticated machine learning algorithm trained to differentiate between normal and cancerous methylation patterns. By learning from a dataset of known methylation states, the model can classify new, unseen methylation sites, aiding in early detection and research of cancer.

## Language, input, and output of this program,
- We use Python3 as the programming language.
- You have to download the accesstion list from NCBI (https://www.ncbi.nlm.nih.gov/sra) that contains the string starting with "SRR" or "ERR".
- You will get the .csv output, which is a sheet of the location of the methylation 

## Acknowledgments
- We would like to express our gratitude to Dr. Robert Aguilar for his foundational work on the SNP analysis program, our project builds upon his original code: https://github.com/crisprmax/SNP-identifier-Python

## License
This project is licensed under MIT License: 

MIT License

Copyright (c) 2024 Shane Deng & Victor Wang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

