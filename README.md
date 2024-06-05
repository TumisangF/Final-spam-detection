# 📧 Spam Detection NLP Project
![spam-detection](https://miro.medium.com/v2/resize:fit:800/1*8eJhfKzFb_0yg61H4Bq5EA.jpeg)

     ![Spam Detection](https://img.shields.io/badge/Spam%20Detection-NLP-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8+-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🚀 Project Overview

Welcome to the Spam Detection NLP Project! This project aims to build a robust spam detection system using Natural Language Processing (NLP) techniques. The goal is to accurately classify messages as spam or not spam, helping to filter unwanted messages.

This project is part of NLP project course in the Bachelor's program of Artificial Intelligence at IU International University of Applied Sciences.

## 📜 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Dataset](#-dataset)
- [Model](#-model)
- [Results](#-results)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

## ✨ Features

- System for fetching latest dataset automatically
- Data Exploration
- Preprocessing of text data (tokenization, stemming, etc.)
- Feature Engineering
- Implementation of various NLP models (e.g., Naive Bayes, SVM, LSTM)
- Model evaluation and performance metrics
- Visualization of results

## 🛠️ Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/TumisangF/Final-spam-detection
    ```

2. **Create a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

## 📝 Usage

To train the model and detect spam, follow these steps:

1. **Run the Jupyter notebook**
    ```sh
    jupyter notebook nlp-project.ipynb
    ```

## 📚 Dataset

The dataset used for this project is [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/94/spambase). Make sure to download and place it in the `data` directory.

## 🧠 Model

This project implements several models, including:
- Random Forest
- Support Vector Machines (SVM)
- Logistic Regression
- Gradient Boosting

## 📈 Results

| Model                | Accuracy | Precision | Recall | F1 Score |
|----------------------|----------|-----------|--------|----------|
| Random Forest        | 93.0%    | 94.2%     | 91.8%  | 93.0%    |
| SVM                  | 93.1%    | 95.1%     | 92.3%  | 93.2%    |
| Logistic Regression  | 92.6%    | 96.4%     | 92.5%  | 92.7%    |
| Gradient Boosting    | 93.0%    | 96.4%     | 91.9%  | 93.0%    |

## 🤝 Contributing

contributions are welcomed to this project! If you have suggestions or improvements, please:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/94/spambase)
- [Scikit-learn](https://scikit-learn.org/)
- [TensorFlow](https://www.tensorflow.org/)
