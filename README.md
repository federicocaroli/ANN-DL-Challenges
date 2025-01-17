# Artificial Neural Networks and Deep Learning Challenges - PoliMi

This repository contains the solutions and code for challenges completed as part of the **Artificial Neural Networks and Deep Learning** course at the **Polytechnic University of Milan**.

## 📚 Overview
The challenges, completed between **September and December 2023**, primarily focus on designing, training, and evaluating deep learning models to solve real-world problems, such as binary classification tasks.

The solution of the first challenge includes:
- **Preprocessing datasets**: Removing outliers, duplicates, and handling imbalances.
- **Model implementation**: ResNet, ConvNeXtBase, EfficientNet, and other state-of-the-art architectures.
- **Optimization techniques**: Transfer learning, fine-tuning, and hyperparameter tuning.
- **Performance evaluation**: Ensemble methods and error analysis.

## 📂 Repository Structure
```
|-- challenge1/
    |-- notebooks/
        |-- ResNetFromZero.ipynb          # Implementation of ResNet from scratch
        |-- ConvNextBase.ipynb            # ConvNeXtBase model training and evaluation
        |-- EfficientNetV2S.ipynb         # EfficientNetV2S model training and evaluation
        |-- DeleteShrekAndTrololoDuplicatesFromDataset.ipynb  # Dataset cleaning script
    |-- scripts/
        |-- model.py                      # Python script for ensemble model loading and prediction into Codalab web platform
    |-- Report.pdf                    # Detailed report on the challenge and solution
|-- README.md                         # Repository documentation
```

## 🚀 Key Features
- **Transfer Learning**: Leveraging pre-trained models (ImageNet) to improve performance on limited datasets.
- **Data Augmentation**: Applying techniques like rotation, flipping, and translation to enhance training robustness.
- **Ensemble Models**: Combining predictions from multiple models to improve accuracy and reduce variance.
- **Error Analysis**: Identifying and interpreting misclassified samples for insights.

## 🧑‍💻 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/federicocaroli/ANN-DL-Challenges.git
   ```
2. Explore the notebooks for detailed implementations and results.
