# Quantum Machine Learning
This is an exploration using synthetic data in CSV format to apply QML models for the sake of binary classification. You can find here three different approaches. Two with Qiskit (VQC and QK/SVC) and one with Pennylane (QVC).

## Caveats

1. No EDA was applied into the notebooks. I highly recommend that if you are going to use other CSVs, please take the time to review your data and put a lot of focus in the pre-processing stage of your architecture.
2. The synthetic data was public and extracted from Kaggle here: https://www.kaggle.com/datasets/mohammadarashi/synthetic-binary-classification
3. If you use your data I recommend also to explore a custom feature map (in the case of Qiskit) or encoding (in the case of Pennylane). The results of the models depends a lot on that.
