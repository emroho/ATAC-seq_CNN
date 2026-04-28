# ATAC-seq_CNN

Chromatin is a mixture of DNA and proteins that make up a chromosome. The DNA winds around proteins and forms a line of clusters. ATAC-seq is a technique used to evaluate the chromatin availability in DNA, referring to the spaces between the clusters. These spaces are often associated with active genes, and these figurations play a role in gene expression. 


The process is performed by tagging DNA with Tn5 transposase which will bind to the open spaces. After the insertion, the strands will be sequenced to figure out how open the chromatin is. The DNA will be purified and amplified for PCR analysis, where researchers can find out more about the chromatin structure. ATAC-seq is a good method because it doesn’t require as many cells in order to gain detailed results. It has high sensitivity and produces results quickly. It is definitely a good method to use.


Despite the advantages that ATAC-seq carries, there are major limitations to the method to be wary of. The Tn5 transposase can sometimes bind the same adapter to both sides of the DNA, making it unusable for analysis as it cannot be sequenced. This results in a loss of data and varying coverage of the genome. The PCR amplification can also be quite hard for larger strands of DNA. The sensitivity of the amount of data poses challenges as there might not be enough to produce good results or there might be too much noise that clouds up the results. There are also issues with ATAC-seq where most tools in bioinformatics have been designed for other methods for chromatin availability, making it harder to access.


Using CNN will allow the machine learning model to look at the DNA strands and more easily make connections through layers and predict where more will be. There will be peaks in the ATAC-seq signal that will let us know where the chromatin availability lies. This data is useful for training a predictive model to locate the spaces. Being able to read ATAC-seq results without needing any extra tools will cut down time and resources for researchers and will provide a more universal method for analysis. One of the limitations of ATAC-seq was tool availability, and this reduces that problem.
