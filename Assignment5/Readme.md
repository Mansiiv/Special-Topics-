# Comprehensive Demonstration of TimeGPT, Tabular, and Relational Deep Learning (RDL)

This repository contains detailed implementations and demonstrations for working with **TimeGPT**, **Tabular**, and **RDL with Relbench**. Each module is implemented in Google Colab and comes with clear explanations and ran artifacts for reproducibility. Below is a structured breakdown of the assignment and associated artifacts.

---

## **TimeGPT**

TimeGPT is an advanced forecasting tool designed for multivariate time series, long-horizon predictions, anomaly detection, and domain-specific forecasting tasks. This section includes the following implementations:

### a) **TimeGPT Multivariate Forecasting**
- **Colab Name**: `timegpt_multivariate_forecasting.ipynb`
- **Description**: Demonstrates multivariate forecasting using example time series data.
- **Reference**: [Nixtla Documentation - Multivariate Forecasting](https://docs.nixtla.io/docs/tutorials-multiple_series_forecasting)
- **What It Does**:
  - Loads sample multivariate time series data.
  - Preprocesses data and visualizes patterns.
  - Uses TimeGPT to forecast multiple series over different horizons.

---

### b) **Fine-Tuning TimeGPT with Custom Data**
- **Colab Name**: `timegpt_finetune_custom_data.ipynb`
- **Description**: Fine-tunes TimeGPT with a user-provided dataset for improved accuracy.
- **Reference**: [Nixtla Documentation - Fine Tuning](https://docs.nixtla.io/docs/tutorials-fine_tuning)
- **What It Does**:
  - Walks through fine-tuning steps using custom data.
  - Analyzes the effects of fine-tuning on prediction accuracy.
  - Visualizes pre-tuning vs. post-tuning results.

---

### c) **Anomaly Detection in Time Series**
- **Colab Name**: `timegpt_anomaly_detection.ipynb`
- **Description**: Implements anomaly detection using TimeGPT on time series data.
- **Reference**: [Nixtla Documentation - Anomaly Detection](https://docs.nixtla.io/docs/tutorials-anomaly_detection)
- **What It Does**:
  - Detects anomalies in given time series datasets.
  - Explains how TimeGPT identifies unexpected patterns or trends.
  - Visualizes anomalies for interpretability.

---

### d) **Energy Forecasting Using TimeGPT**
- **Colab Name**: `timegpt_energy_forecasting.ipynb`
- **Description**: Utilizes TimeGPT for forecasting energy demand.
- **Reference**: [Nixtla Documentation - Energy Demand Forecasting](https://docs.nixtla.io/docs/use-cases-forecasting_energy_demand)
- **What It Does**:
  - Processes energy demand datasets.
  - Predicts future energy requirements over short and long horizons.
  - Demonstrates practical energy applications.

---

### e) **Bitcoin Forecasting Using TimeGPT**
- **Colab Name**: `timegpt_bitcoin_forecasting.ipynb`
- **Description**: Predicts Bitcoin price trends using TimeGPT.
- **Reference**: [Nixtla Documentation - Bitcoin Price Prediction](https://docs.nixtla.io/docs/use-cases-bitcoin_price_prediction)
- **What It Does**:
  - Loads and processes Bitcoin price data.
  - Predicts price trends over different horizons.
  - Evaluates accuracy against historical data.

---

## **Tabular**

Tabular is a tool designed for generating synthetic data and performing inference tasks in tabular data scenarios.

### a) **Synthetic Data Generation**
- **Colab Name**: `tabular_synthetic_data_generation.ipynb`
- **Description**: Generates synthetic data for a real-world dataset.
- **Reference**: [Tabula Insurance Dataset Example](https://github.com/zhao-zilong/Tabula/blob/main/Tabula_on_insurance_dataset.ipynb)
- **What It Does**:
  - Demonstrates how to generate synthetic data using Tabula.
  - Compares real vs. synthetic data distributions.
  - Explains applications of synthetic data in testing and validation.

---

### b) **Inference on Tabula Model with Zero-Shot Learning**
- **Colab Name**: `tabular_inference_zero_shot.ipynb`
- **Description**: Shows how to use Tabula for zero-shot inference on tabular models.
- **Reference**: [Inference Example](https://github.com/mlfoundations/rtfm/blob/main/notebooks/inference.ipynb)
- **What It Does**:
  - Loads a pre-trained Tabula model.
  - Performs zero-shot inference tasks.
  - Evaluates model performance metrics.

---

## **Relational Deep Learning (RDL) with Relbench**

Relbench enables the application of GNN-based models for tabular prediction tasks. This section focuses on leveraging Relbench for training and evaluation.

### a) **Training a GNN-Based Model for Tabular Prediction**
- **Colab Name**: `rdl_gnn_tabular_prediction.ipynb`
- **Description**: Trains a Graph Neural Network (GNN) model for tabular prediction tasks using Relbench.
- **Reference**: [Relbench Tutorials](https://relbench.stanford.edu/start/)
- **What It Does**:
  - Prepares tabular data for GNN-based modeling.
  - Trains the GNN model and evaluates key metrics like accuracy, precision, and recall.
  - Visualizes model performance and predictions.

---

## **Deliverables**

### 1. **Google Colab Notebooks**
All Colab notebooks are available in this repository under the `notebooks/` directory:
- `timegpt_multivariate_forecasting.ipynb`
- `timegpt_finetune_custom_data.ipynb`
- `timegpt_anomaly_detection.ipynb`
- `timegpt_energy_forecasting.ipynb`
- `timegpt_bitcoin_forecasting.ipynb`
- `tabular_synthetic_data_generation.ipynb`
- `tabular_inference_zero_shot.ipynb`
- `rdl_gnn_tabular_prediction.ipynb`

### 2. [Video Presentation Link ](https://youtu.be/PWbj7NsKJZ0)
A video explaining the code, outputs, and insights from the notebooks is available. click the link above.




