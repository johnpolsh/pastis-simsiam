### README

# Introduction

This repository contains Jupyter notebooks and scripts focused on the application of self-supervised learning (SSL) techniques, specifically SimSiam, for agricultural analysis using remote sensing imagery.

## Repository Structure

- **PASTIS_SimSiam.ipynb**: Contains the code for pre-training and fine-tuning a SimSiam model on the PASTIS dataset, used for crop classification.
- **UCMerced_SimSiam.ipynb**: Similar to the above, this notebook handles the UCMerced dataset, another benchmark dataset for remote sensing tasks.
- **Cloud_analysis.ipynb**: Performs cloud detection and analysis on the PASTIS dataset, addressing issues of cloud cover in satellite imagery.
- **Generate_parcels.ipynb**: Contains code to generate parcels (segments) for training from PASTIS, critical for ensuring meaningful input samples in the crop classification task.
- **/etc**: Contains other supporting studies and analyses of the datasets, expanding on additional preprocessing techniques and dataset explorations.

## Objective

The aim of this work is to evaluate the effectiveness of SSL methods in agricultural contexts, addressing the challenge of limited labeled data and enhancing the classification accuracy of satellite imagery for crop monitoring.
