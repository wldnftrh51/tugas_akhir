# Deteksi Anomali Data Multivariat Time-Series pada Sistem Multiphase Menggunakan Long Short-Term Memory Autoencoder

## Sumber Dataset
 
Dataset yang digunakan berasal dari eksperimen sistem multiphase simulasi transportasi minyak dan gas, dideskripsikan dalam:
 
Mazzuto, G., Pietrangeli, I., Ortenzi, M., Foti, V., Ciarapica, F. E., & Bevilacqua, M. (2025). A collection of experimental data from a multiphase plant simulating oil and gas transport. *Data in Brief, 62*, 112038. 
 
- Paper (Data in Brief, ScienceDirect): https://www.sciencedirect.com/science/article/pii/S2352340925007607
- Repositori dataset (Zenodo): https://zenodo.org/records/16978349

## Daftar File

- **`parsing_json_working_condition_oil_and_gas.ipynb`** — Parsing data JSON kondisi operasi normal (`working_condition/`) menjadi dataframe tabular.
- **`parsing_json_anomaly_oil_and_gas.ipynb`** — Parsing data JSON kondisi anomali (`test_with_anomaly/`) menjadi dataframe tabular beserta label anomali.
- **`eda.ipynb`** — Exploratory Data Analysis pada data hasil parsing.
- **`model_deteksi_anomali.ipynb`** — Pemodelan LSTM Autoencoder.
