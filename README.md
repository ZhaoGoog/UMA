## Prepare Data

We evaluate our method on public benchmark datasets across four time series analysis tasks: **forecasting, imputation, anomaly detection, and classification**.

To facilitate reproducibility, we provide some datasets directly in the `./dataset` directory, including the forecasting datasets and a subset of the anomaly detection datasets. The remaining datasets can be obtained from the following sources. Please download the required datasets and organize them according to the directory structure and preprocessing format expected by our implementation.

- **MSL and SMAP:** [Telemanom](https://github.com/khundman/telemanom)
- **PSM:** [RANSynCoders](https://github.com/eBay/RANSynCoders/tree/main/data)
- **SMD:** [OmniAnomaly](https://github.com/NetManAIOps/OmniAnomaly/tree/master/ServerMachineDataset)
- **SWaT:** [iTrust Dataset Portal](https://itrust.sutd.edu.sg/itrust-labs_datasets/)
- **Electricity, Exchange Rate, and Solar:** [Multivariate Time Series Datasets](https://github.com/laiguokun/multivariate-time-series-data)
- **ETT-small:** [ETDataset](https://github.com/zhouhaoyi/ETDataset)
- **Weather:** [Jena Weather Data](https://weather.bgc-jena.mpg.de/weather_data.html)
- **UEA Time Series Classification Archive:** [Official Website](https://www.timeseriesclassification.com/)
- **Flight:** Provided in the `./dataset` directory of this repository.

**Note:** Access to the SWaT dataset is subject to the access procedures and usage terms specified by iTrust. Please obtain and use this dataset in accordance with its requirements.
