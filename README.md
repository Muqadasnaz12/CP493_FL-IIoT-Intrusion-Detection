# CP493_FL-IIoT-Intrusion-Detection
Comparative study of centralized Random Forest and Federated Learning for intrusion detection using the CIC-IIoT-2025 dataset.

# Author 
Muqadas Nazif, 169061218, nazi1218@mylaurier.ca

# Dataset
This project uses the **CIC-IIoT-2025 (DataSense)** dataset.
The dataset is downloaded automatically using the `kagglehub` package. Before running the notebook, ensure you have access to Kaggle and have configured your Kaggle API credentials if required.

If automatic download is unavailable, the dataset can also be obtained from:
- Kaggle: https://www.kaggle.com/
- Canadian Institute for Cybersecurity (CIC): https://www.unb.ca/cic/datasets/

# Running the Project
1. Download the CIC-IIoT-2025 dataset.
2. Update the dataset path in the notebook if necessary.
3. Open `FL_PAPER.ipynb`.
4. Run all cells sequentially to reproduce the experiments.

# Experimental Configuration
- Dataset: CIC-IIoT-2025
- Total Samples: 685,671
- Features: 84
- Training/Test Split: 80% / 20%
- Centralized Model: Random Forest
- Federated Model: Neural Network
- Number of Clients: 5
- Communication Rounds: 5
- Local Epochs: 1
- Aggregation Algorithm: Federated Averaging (FedAvg)

# Results
The experimental results demonstrate that Federated Learning achieves competitive intrusion detection performance while preserving data privacy by keeping training data decentralized.
