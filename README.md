# LycoS-Unicas-IDS2018

## Overview
LycoS-Unicas-IDS2018 is a novel dataset created using [LycoStand](https://lycos-ids.univ-lemans.fr/) [[1]](https://hal.science/hal-03563228/), a feature extractor of raw network traffic on the PCAP files of [CSE-CIC-IDS2018 dataset](https://www.unb.ca/cic/datasets/ids-2018.html). The flows are labeled according to the official attack schedule accessible via the dataset website.

<!-- To enhance the dataset quality, we discarded raw network traffic on days 28/02/2018 and 01/03/2018 containing the infiltration attack. To address class imbalance and computational complexity, we randomly subsampled this class to 1 million samples. -->

## Files and Structure
The LycoS-Unicas-IDS2018 dataset is contained in a single CSV file with the following structure:

- **File:** `LycoS18_dataset.csv`
- **Total Samples:** 13,691,268

### Features
The dataset consists of 77 features representing various aspects of network traffic flows. For a detailed description of all the features in the LycoS18 dataset, please refer to [[1]](https://hal.science/hal-03563228/). These features are accompanied by a label column indicating the class of each sample.

### Classes
There are a total of 14 different classes, with 1 class representing normal traffic and the remaining 13 classes representing different attack scenarios.

| Class Name                  | Occurrences  |
|-----------------------------|--------------|
| Benign                      |   10,000,000 |
| DoS Hulk                    |    1,802,966 |
| DDoS HOIC                   |    1,074,379 |
| DDoS LOIC-HTTP              |      289,328 |
| FTP-Patator                 |      190,300 |
| DoS Slowhttptest            |      105,550 |
| Bot                         |       96,154 |
| SSH-Patator                 |       92,648 |
| DoS GoldenEye               |       26,861 |
| DoS Slowloris               |       10,274 |
| DDoS LOIC-UDP               |        2,382 |
| Web Attack - Brute Force    |          260 |
| Web Attack - XSS            |          116 |
| Web Attack - Sql Injection  |           50 |

## Download
The dataset is available at the following [link](https://drive.google.com/file/d/12dQPcqRDJFeJGmqqshzdYN8M5t5tMXbQ/view?usp=sharing).

<!-- ## Citation

If you use the LycoS18 dataset in your research, please cite it using the following BibTeX entry: -->

## References
[1] Rosay, Arnaud, et al. "Network intrusion detection: A comprehensive analysis of CIC-IDS2017." 8th International Conference on Information Systems Security and Privacy. SCITEPRESS-Science and Technology Publications, 2022.

