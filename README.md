
# M-Bagging: Unleash the Power of Modified Bagging 🚀

M-Bagging is a groundbreaking ensemble learning technique that supercharges classification models. By fusing modified bootstrapping with heterogeneous classifiers, it achieves superior prediction accuracy.

![M-Bagging Architecture](images/architecture.png)


## Table of Contents

- [Features](#-features)
- [Installation](#️-installation)
- [Demo](#-demo)
- [Usage](#-usage)
- [Datasets & Results](#-datasets--results)
- [My research Paper](#-my-research-paper)
- [Contributing](#-contributing)
- [License & References](#-license--references)

## 🌟 Features

- **Modified Bootstrapping**: Special handling of misclassified samples and utilization of out-of-bag samples.
- **Heterogeneous Classifiers**: A blend of SVM, Naïve Bayes, KNN, Decision Trees, and Logistic Regression.
- **Improved Prediction Accuracy**: Outshines standard Bagging and rivals state-of-the-art models.
- **Adaptability**: Tailor it to various datasets and classification tasks.

## 🛠️ Installation

Get started with just a few commands:
```bash
git clone https://github.com/your-username/m-bagging.git
cd m-bagging
pip install -r requirements.txt
```

## 🎥 Demo


<p align="center">
  <img src="https://github.com/abhip2565/M-Bagging/assets/74866247/137da2ed-8f94-4a30-bb2c-6077b8c4f510" width="600" height="400">
</p>



## 🚀 Usage

Launch M-Bagging on your dataset with a single command:
```bash
python m_bagging.py --dataset path/to/dataset.csv
```

[Full Documentation & Options](docs/USAGE.md)

## 📊 Datasets & Results

Tested on diverse datasets like Diabetes, Liver Disorder, and more, M-Bagging exhibits remarkable results.


<p align="left"><img src="https://github.com/abhip2565/M-Bagging/assets/74866247/25ff2afc-dc88-44ec-a4a8-03ab70584584" width="500" height="300"></p>


[Detailed Results](docs/RESULTS.md) | [Datasets Info](docs/DATASETS.md)

## 📖 My Research Paper

**Title**: M-Bagging: A New Modified Bagging Classification Model to Improve Prediction Accuracy

In this research, I present M-Bagging, a novel model that significantly enhances traditional Bagging. The key contributions include special handling of misclassified samples, utilization of out-of-bag samples, various classifiers, and superior prediction accuracy.

For a comprehensive understanding of the methodology and results, please explore the [full research paper](link_to_paper).

![M-Bagging Conceptual Overview](path/to/m_bagging_detailed_diagram.png)


## 🤝 Contributing

Join the innovation! [Contribution Guidelines](CONTRIBUTING.md)

## 📜 License & References

- [MIT License](LICENSE.md)
- [Research & Citations](docs/REFERENCES.md)
