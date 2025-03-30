# research-paper
Enhancing Network Security through Optimized Classification Models


# Abstact
This study examines the efficacy of advanced classification models using the UNSW-NB15 and CICIDS2017 datasets to enhance Network Intrusion Detection Systems (NIDS).
We employ a combination of Random Forest, KNN, DT, XG Boost Logistic Regression, and Multi-Layer Perceptron (MLP) models, optimized through various hyperparameter tuning to identify and classify network threats more accurately.
Results demonstrate that our integrated approach, particularly the Random Forest significantly outperforms conventional detection systems, achieving 90% and 100% accuracy for UNSW-NB15 and CICIDS2017 datasets in identifying diverse cyber threats.
These findings underscore the critical role of machine learning in advancing the reliability and effectiveness of cybersecurity measures against evolving digital threats.

https://scholarworks.calstate.edu/concern/theses/pn89df73b

# Machine Learning for Network Traffic Classification

## Overview
This repository contains implementation and evaluation of various machine learning models for network traffic classification using the UNSW-NB15 and CICIDS2017 datasets. The project demonstrates how different classifiers perform in identifying network traffic patterns for cybersecurity applications.

## Key Features
- Comprehensive data preprocessing pipeline
- Implementation of multiple machine learning classifiers (Random Forest, MLP, Logistic Regression, etc.)
- Hyperparameter optimization for model performance
- Comparative analysis across two standard network security datasets
- Evaluation metrics including accuracy, precision, recall, and execution time

## Results
Random Forest emerged as the top performer:
- UNSW-NB15: 90% accuracy (63 seconds execution time)
- CICIDS2017: 99.99% accuracy (103 seconds execution time)

## Dataset Information
- [UNSW-NB15](https://research.unsw.edu.au/projects/unsw-nb15-dataset): A comprehensive network traffic dataset containing normal and attack traffic
- [CICIDS2017](https://www.unb.ca/cic/datasets/ids-2017.html): Contains benign and the most up-to-date common attacks traffic data

## Requirements
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn

## Usage
```bash
# Clone the repository
git clone https://github.com/yourusername/ml-network-traffic-classification.git

# Install dependencies
pip install -r requirements.txt

# Run the main analysis
python main.py
```

## Citation
If you use this code or findings in your research, please cite:
```
@article{yourlastname2025,
  title={Machine Learning Techniques for Network Traffic Classification},
  author={Your Name},
  year={2025}
}
```

## License
MIT
