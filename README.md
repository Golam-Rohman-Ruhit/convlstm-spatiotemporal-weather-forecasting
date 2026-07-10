# 🌡️ ConvLSTM — Spatiotemporal Temperature Forecasting

[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c?logo=pytorch)](https://pytorch.org/)

> Four escalating architectures for ERA5 temperature forecasting: LSTM → CNN → ConvLSTM → CNN-LSTM Hybrid. Custom ConvLSTM implemented from scratch.

## 🏗️ Architectures

| Architecture | Approach |
|-------------|----------|
| LSTM | 1D time-series forecasting |
| CNN | Face-to-Point spatial regression |
| ConvLSTM | Custom spatiotemporal cells (Conv2d-gated) |
| CNN-LSTM Hybrid | CNN spatial encoder + LSTM temporal encoder |

## 📊 Data

ERA5 NetCDF reanalysis — 5D tensor reshaping, MinMax scaling, spatial heatmap visualization.

## 👤 Author
**Golam Rohman Ruhit** — AI Engineer  
GitHub: [@Golam-Rohman-Ruhit](https://github.com/Golam-Rohman-Ruhit)
