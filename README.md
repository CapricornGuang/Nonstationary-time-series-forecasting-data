# Diviner: Long-term time series forecasting for 5G cellular network capacity planning
![License](https://img.shields.io/badge/MIT-License-orange?style=plastic)
![ETT](https://img.shields.io/badge/ETT-red?style=plastic)
![WTH](https://img.shields.io/badge/WTH-yellow?style=plastic)
![ECL](https://img.shields.io/badge/ECL-blue?style=plastic)
![Exchange](https://img.shields.io/badge/Exchange-grey?style=plastic)






## Diviner Framework
Diviner aims at exploring the multi-scale stable regularities within time-series data, whose data distribution varies over time. To this end, we propose `Smoothing Filter Attention Mechanism` to filter out random components and adjust the feature scale layer-by-layer. Simultaneously, a `Difference Attention Module` is designed to calculate long- and short- range dependencies by capturing the stable shifts at the corresponding scale. The recipe of our work is to mine constants in change!

<p align="center">
<img src=".\.img/Framework.png" height = "320" alt="" align=center />
<br><br>
<b>Figure 1.</b> The illustration of Diviner framework.
</p>

## Data
The file folder collects the data generated our experimental results, including ETT, WTH, ECL, Solar, Traffic, and Exchange data. 
But due to the confidentiality involved in this project, the NPT dataset can not be accessed publicly. Here below we provide an illustration demo of the NPT data.

<p align="center">
<img src=".\.img/Figure1.png" height = "256" alt="" align=center />
<br><br>
<b>Figure 2.</b> An example of the NPT data.
</p>

the `dataloader` file within the `data` folder includes our pre-processing and spliting of the dataset, all data involved in this study are standardized.


## Results Visualization
<p align="center">
<img src=".\.img/wthv.gif" height = "240" alt="" align=center />
<img src=".\.img/wth_3_.gif" height = "240" alt="" align=center />
<br><br>
<b>Figure 3.</b> An illustration of WTH prediction.
</p>
<p align="center">
<img src=".\.img/network_port8_1_.gif" height = "240" alt="" align=center />
<img src=".\.img/network_port9_1_.gif" height = "240" alt="" align=center />
<br><br>
<b>Figure 4.</b> An illustration of NPT prediction.
</p>




## Contact
If you have any questions, feel free to contact YuGuang Yang through Email (moujieguang@gmail.com) or Github issues. Pull requests are highly welcomed!

## Acknowlegements![China Unicom](https://img.shields.io/badge/China%20Unicom-CC_BY--NC--SA--red.svg?color=critical)

Thanks for the NPT data collected by China United Network Communications Group Co., Ltd.<br/>
Thanks for the ETT datasets collected by https://github.com/zhouhaoyi/ETDataset.<br/>
The Solar and Traffic datasets collected by https://github.com/laiguokun/multivariate-time-series-data.<br/>
The WTH, ECL datasets collected by https://github.com/RPcb/ARNN.<br/>



At the same time, thank you all for your attention to this work! 
