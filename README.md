# Artificial Neural Networks and Deep Learning Challenges - PoliMi

This repository contains the solutions and code for challenges completed as part of the **Artificial Neural Networks and Deep Learning** course at the **Polytechnic University of Milan**.

## 📚 Overview
The goal of these challenges, completed between **September and December 2023**, was to design and implement deep learning models to solve a variety of tasks, including **binary classification of plant health** based on image datasets and **forecasting future samples in uncorrelated time series**. The challenges emphasized building effective models, optimizing their performance, and analyzing errors to gain insights.

### Challenge 1: Binary Classification of Plant Health
The solutions include:

- **Preprocessing datasets**: Removing outliers, duplicates, and handling imbalances.
- **Model implementation**: ResNet, ConvNeXtBase, EfficientNet, and other state-of-the-art architectures.
- **Optimization techniques**: Transfer learning, fine-tuning, and hyperparameter tuning.
- **Performance evaluation**: Ensemble methods and error analysis.

### Challenge 2: Time Series Forecasting
In this challenge, the task was to predict future samples of uncorrelated time series based on past observations. The solutions include:

- **Data preprocessing**: Removing padding, handling variable time series lengths, and categorizing datasets.
- **Model implementation**: Bidirectional LSTM networks with masking layers for sequence-to-vector predictions.
- **Feature engineering**: Building and expanding sequences using custom algorithms.
- **Performance evaluation**: Validation through Mean Squared Error (MSE) and ensemble methods for improved generalization.

## 📂 Repository Structure
```
|-- challenge1/
    |-- notebooks/
        |-- ResNetFromZero.ipynb          # Implementation of ResNet from scratch
        |-- ConvNextBase.ipynb            # ConvNeXtBase model training and evaluation
        |-- EfficientNetV2S.ipynb         # EfficientNetV2S model training and evaluation
        |-- DeleteShrekAndTrololoDuplicatesFromDataset.ipynb  # Dataset cleaning script
    |-- scripts/
        |-- model.py                      # Python script for ensemble model loading and prediction
    |-- Report.pdf                        # Detailed report on the challenge and solutions
|-- challenge2/
    |-- notebooks/
        |-- one_dimensional_convolutiol_network.ipynb  # Implementation of 1D convolutional models
        |-- recurrent_network.ipynb                  # Implementation of recurrent models
        |-- official_data_preprocessing.ipynb        # Data preprocessing and sequence generation
    |-- Report.pdf                                    # Detailed report on the time series challenge
|-- README.md                                         # Repository documentation
```

## 🚀 Key Features
### Challenge 1
- **Transfer Learning**: Leveraging pre-trained models (ImageNet) to improve performance on limited datasets.
- **Data Augmentation**: Applying techniques like rotation, flipping, and translation to enhance training robustness.
- **Ensemble Models**: Combining predictions from multiple models to improve accuracy and reduce variance.
- **Error Analysis**: Identifying and interpreting misclassified samples for insights.

### Challenge 2
- **Bidirectional LSTMs**: Using sequence-to-vector networks for robust forecasting.
- **Feature Engineering**: Expanding time series data through sequence generation.
- **Trend and Seasonality Analysis**: Handling non-stationary time series by removing trends and periodic components.
- **Ensemble Models**: Combining models trained on different splits for better generalization.

## 🧑‍💻 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ANN-DL-Challenges.git
   ```
2. Explore the notebooks for detailed implementations and results.

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy coding! 🎉
