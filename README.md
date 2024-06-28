
# Application of the Signature Method in Time Series and Financial Data Streams

This repository contains the code and data for my thesis, "Application of the Signature Method in Time Series and Financial Data Streams". The thesis explores the application of the signature method in various time series and financial data stream contexts. The repository is organized into three main applications, each contained within its own folder.

## Repository Structure

- `Application_1/`
  - `TFM_application1.ipynb`: Notebook for Application 1
- `Application_2/`
  - `TFM_application2.ipynb`: Notebook for Application 2
  - `DAT_ASCII_WTIUSD_M1_2021.csv`: Data file for crude oil prices in 2021
  - `DAT_ASCII_WTIUSD_M1_2022.csv`: Data file for crude oil prices in 2022
  - `DAT_ASCII_WTIUSD_M1_2023.csv`: Data file for crude oil prices in 2023
- `Application_3/`
  - `TFM_application3.ipynb`: Notebook for Application 3

## Applications

### Application 1: Model Classification

In this application, we compare traditional Autoregressive (AR), Autoregressive Moving Average (ARMA), and Autoregressive Integrated Moving Average (ARIMA) models using signature-based features. The goal is to classify models and assess the performance improvements brought by using signature features.

### Application 2: Temporal Segmentation

This application focuses on classifying crude oil data streams based on 30-minute intervals using signature features. The objective is to demonstrate the method's applicability in temporal segmentation tasks. The necessary data files (`DAT_ASCII_WTIUSD_M1_2021.csv`, `DAT_ASCII_WTIUSD_M1_2022.csv`, `DAT_ASCII_WTIUSD_M1_2023.csv`) are provided within the `application_2` folder.

### Application 3: Equivalence Demonstration

In this application, we investigate how AR models can be viewed as a special case within the broader framework of Expected Signature (ES) models. This highlights the versatility of the signature method in capturing varied model structures.

