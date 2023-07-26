# HolisticRCA Temp Data

Temp data for HolisticRCA, a framework for failure root cause analysis in cloud-native systems from a holistic perspective.

## Folder Structure

The following commands need to be input for the working folder:
````
zip temp_data_split.zip -s=0 --out temp_data.zip
unzip temp_data.zip
````

The structure of the ``temp_data`` folder is shown as follows:
````
.
├── 2022_CCF_AIOps_challenge                                     
│   ├── analysis                        essential analysis results for futher preprocess
│   │   ├── trace                       analysis results for trace
│   │   ├── metric                      analysis results for metric
│   │   └── log                         analysis results for log
│   ├── raw_data                        intermediate results
│   ├── dataset                         the generated dataset
│   │   ├── trace                       intermediate data for trace
│   │   ├── metric                      intermediate data for metric
│   │   ├── log                         intermediate data for log
│   │   ├── time_interval_and_label     intermediate data for ground truth
│   │   ├── ent_edge_index              intermediate data for resource entity relations
│   │   └── merge_multimodal            final dataset
├── 2022_ICASSP_AIOps_challenge                                     
│   ├── analysis                        essential analysis results for futher preprocess
│   ├── raw_data                        intermediate results
│   ├── dataset                         the generated dataset
│   │   ├── metric                      intermediate data for metric
│   │   ├── ent_edge_index              intermediate data for resource entity relations (only self-loops)
│   │   └── merge                       final dataset
├── 2023_Eadro_SN                                     
│   ├── analysis                        essential analysis results for futher preprocess
│   │   ├── trace                       analysis results for trace
│   │   └── log                         analysis results for log
│   ├── raw_data                        intermediate results
│   ├── dataset                         the generated dataset
│   │   ├── trace                       intermediate data for trace
│   │   ├── metric                      intermediate data for metric
│   │   ├── log                         intermediate data for log
│   │   ├── time_interval_and_label     intermediate data for ground truth
│   │   └── merge                       final dataset
````

## Raw Data

Since the raw data is too big, we list their links here, help for downloading:

- Dataset A: https://competition.aiops-challenge.com/home/competition/1496398526429724760. (Sometimes the page may be crashed, please visit https://www.bizseer.com/index.php?m=content&c=index&a=show&catid=25&id=83 for simple introduction).
- Dataset B: https://www.aiops.sribd.cn/home/introduction.
- Dataset C: https://doi.org/10.5281/zenodo.7615393.
