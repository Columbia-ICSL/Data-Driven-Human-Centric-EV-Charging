# Data-Driven-Human-Centric-EV-Charging

A Data-Driven and Human-Centric EV Charging Recommendation System at City-Scale

## Introduction
![Dataset Overview](/image/Introduction.png "System Overview")
To obtain a holistic perspective, we consider four categories of data to model EV drivers and the effects of EV chargers on the grid, as shown in figure above. The four categories include:
1. Charger information (location, availability, and price) from ChargeHub, PlugShare, and NYSERDA;
2. EV information, including state of charge (SoC), car type, charging rate, and discharging rate directly collected by On-board diagnostics II (OBD-II) devices from open-source datasets or collected in this study, the EV car type distribution, and LIB SOC estimation.
3. City-scale vehicle mobility data includes the floating car data from HERE, INRIX, RITIS, and NHTSA.
4. Grid information, which contains the network hosting capacity and EV charging capacity from Con Edison.


## Dataset
There are 61,392 trips in total over 30 days (from 11/01/2022 to 11/30/2022), or approximately 2,046 trips per day. In each folder, the data is divided into each day (from day 1 to day 30). To ensure the privacy of the users, the real users and the augmented users are named after “driverX” (e.g. driver0 and driver2035). Based on the traffic information gathered from INRIX, HERE, RITIS, and NHTSA, the number of drivers is different from day to day.

*Note that, although we used per-minute granularity in the DRL framework in our paper, we are releasing the per-second data for the EV info data to provide opportunities for the research community to conduct research with higher time granularity requirements. As such, the entire dataset is over 100 GB.*

## Full Data Access
The data are not publicly available due to privacy. But we welcome all researchers and developers to contact us to request the data.
Please send us a request form (Download form here ) to this email: jn2551@columbia.edu

## Citation
If your academic work has used our dataset, please cite our paper below.

> Jingping Nie, Stephen Xia, Yanchen Liu, Shengxuan Ding, Lanxiang Hu, Minghui Zhao, Yuang Fan, Mohamed Abdel-Aty, Matthias Preindl, and Xiaofan Jiang. 2023. A Data-Driven and Human-Centric EV Charging Recommendation System at City-Scale. In The 14th ACM International Conference on Future Energy Systems (e-Energy '23), June 20--23, 2023, Orlando, FL, USA. ACM, New York, NY, USA 12 Pages. [https://doi.org/10.1145/3575813.3597350](https://doi.org/10.1145/3575813.3597350)