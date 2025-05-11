# WCDMA Performance Analysis

This project simulates WCDMA sequences of varying lengths and evaluates performance metrics like:
- Throughput
- Latency
- Signal Quality (SINR)
- Packet Loss Rate

Based on the methodology from an ECE internship project at BNMIT.

## 📊 Features
- Generates WCDMA sequences with packet loss
- Applies masking for interference modeling
- Computes and visualizes key performance metrics

## 📦 Setup

```bash
git clone https://github.com/your-username/WCDMA-Performance-Analysis.git
cd WCDMA-Performance-Analysis
pip install -r requirements.txt
```

## 🧪 Run the Notebook
```bash
cd notebooks
jupyter notebook WCDMA_Analysis.ipynb
```

## 📂 Directory Structure

- `src/` – Source code (sequence generation, metrics, plots)
- `notebooks/` – Jupyter notebook for full simulation
- `data/` – Optional: store sequences/results
