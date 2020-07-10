# NetRep
# Language: R
# Input: TXT
# Output: PREFIX
# Tested with: PluMA 1.1, R 4.0.0
# Dependencies: NetRep_1.2.1

PluMA plugin to check amount of data preserved between two datasets using NetRep (Ritchie et al, 2016).

The plugin accepts as input a TXT file of keyword-value pairs, tab-delimited:
data1: dataset 1
data2: dataset 2
corr1: correlations of dataset 1
corr2: correlations of dataset 2
network1: network of dataset 1
network2: network of dataset 2
modulelabels: node names

It will produce two output files using the user-specified prefix:
prefix.observed.csv: Observed preservation values
prefix.pvalue.csv: Corresponding pvalues
