# Few-shot Intrusion Detection Dataset (FSIDS-IoT)
This is a Few-shot dataset that extracted from five data sets (CIC-DDoS2019, CIC-IDS2017, CSE-CIC-IDS2018, NSL-KDD, UNSW-NB15)
We have already partially processed the data.

This Dataset has been used in the paper "A Few-shot Based Model-Agnostic Meta-Learning for Intrusion Detection in Security of Internet of Things"

## FSIDS_Original
This is a .csv dataset. A maximum of 5000 samples are randomly selected from each category of each dataset.

## R-FSIDS_84_84_RGB
This is an image dataset. 20 samples are randomly selected from each category of FSIDS_Original, and then we use matrix processing method to convert csv data to image data.

## Use case:
https://github.com/Chaomeng-Lu/MAML-CNN-FSIDS-IoT

For more information please see: https://doi.org/10.1109/JIOT.2023.3283408.
