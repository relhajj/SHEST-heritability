# A Novel Approach to Estimate Heriability 

## Secular Heriability ESTimate (SHEST) Software
This repository contains the associated code for the manuscript, `A Novel Approach to Estimate Heritability`. Heritability is the standard measure used to quantify the relative genetic contributions to various phenotypes, diseases, and conditions. In our paper, we describe a novel approach to quantitatively estimate broad sense heritability by assessing the magnitude of the secular trend in the incidence or prevalence of a specific phenotype or disease for a given population. The method, which we call “SHEST” (Secular Heritability ESTimate), is based on the premise that large-scale secular trends over a short period of time (one to two generations) are indicative of a weakly heritable condition while long-term invariant incidence or prevalence is indicative of a strongly heritable condition.

## Formatting input data:
* The expected file type format for SHEST_calculator.ipynb a comma-seperated-values file (extention: `.csv`)
* The file should have two columns. 
  * Column 1 contains the years while column 2 contains the incidence or prevalence values.
  * Rows 1 and 2 are used to store the data source(s)
* **For examples of acceptable .csv files, refer to [relhajj/SHEST-heritability/csvs](https://github.com/relhajj/SHEST-heritability/blob/92acb4219c7ee84a49af64f883985fce5f8dd3b3/csvs/cystic_fibrosis.csv) which contains the .csv files used to estimate heritability through the SHEST method introduced in our manuscript.**

`Authors: Rehab El-Hajj (rehab.elhajj@ucalgary.ca), Sarah Davis (sdavis1@ualberta.ca), David Wishart (dwishart@ualberta.ca)`
