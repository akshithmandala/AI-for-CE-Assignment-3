# Assignment 3 — CE 639: AI for Civil Engineering

This repository contains two notebooks for Assignment 3:
- `Problem_1/Assignment3_Task1_Task2_CNN.ipynb`
- `Problem_2/Assignment3_Task3_Task4_RNN_LSTM.ipynb`

## Notebooks

| Task | Notebook | Colab Link | Local Path |
|------|----------|------------|------------|
| Task 1 & Task 2 | CNN for facade defect classification | [Open in Colab](https://colab.research.google.com/drive/1Dp8EJEzjqv_eTeFZcpA0z_9txdZwjA4d?usp=sharing) | `Problem_1/Assignment3_Task1_Task2_CNN.ipynb` |
| Task 3 & Task 4 | RNN + LSTM streamflow forecasting | [Open in Colab](https://colab.research.google.com/drive/1idmCmu7Ah3LRCpxNA9xgEuA4tnkxIkrz?usp=sharing) | `Problem_2/Assignment3_Task3_Task4_RNN_LSTM.ipynb` |

## Run in Google Colab

1. Click the notebook link in the table above.
2. In Colab, go to `Runtime` → `Run all`.
3. If asked, connect to a GPU runtime for faster training.

## Run locally in VS Code or Jupyter

1. Open this repository in VS Code or Jupyter Notebook/Lab.
2. Install Python packages if needed:

```bash
pip install numpy pandas torch matplotlib scikit-learn
```

3. Open the notebook you want to run.
4. For Problem 1, confirm:
   - `DATA_DIR = './FBD-Dataset-main/train-test-split'`
5. For Problem 2, confirm:
   - `DATA_PATH = './HydroLSTM-main/data/521_data.csv'`
6. Run all cells sequentially.

## Dataset Download

- FBD dataset: download from the FBD GitHub repository:
  - https://github.com/Malga-Vision/FBD-Dataset.git
  - Place the extracted folder at: `Problem_1/FBD-Dataset-main`
- HydroLSTM data: download from the HydroLSTM GitHub repository:
  - https://github.com/uihilab/HydroLSTM.git
  - Place `521_data.csv` at: `Problem_2/HydroLSTM-main/data/521_data.csv`


## Notes

- The notebooks save figures locally in their respective folders.
- If a GPU is available, PyTorch will use it automatically.
