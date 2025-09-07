# ADM - Algorithmics for Data Mining

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-green.svg)](https://scikit-learn.org)

Academic projects for the **Algorithmics for Data Mining** course at **UPC (Universitat Politècnica de Catalunya)**.

This repository contains comprehensive implementations and analysis of two fundamental data mining approaches, combining theoretical foundations with practical applications on real-world datasets.

## 🎯 Projects Overview

### 1. Tree-Based Methods for Data Mining
**Use Case**: Heart Attack Prediction

- **Implementation**: Ensemble methods including Decision Trees, Random Forests, AdaBoost, and Gradient Boosting
- **Dataset**: Heart disease dataset with balanced target distribution
- **Key Features**:
  - Feature importance analysis and selection
  - Hyperparameter optimization using GridSearchCV
  - Model interpretability through tree visualization
  - Cross-validation and performance evaluation

### 2. Deep Sequence Prediction
**Use Case**: Sunspot Activity Prediction

- **Implementation**: Deep learning models for time series forecasting
- **Focus**: Sequential pattern recognition and temporal data modeling
- **Techniques**: Advanced sequence modeling approaches for predictive analytics

## 📁 Repository Structure

```
ADM/
├── 1. Tree Based Methods/
│   ├── 3_Notebook.ipynb                          # Main implementation notebook
│   ├── 1_Tree-based models for data mining.pdf  # Theoretical background
│   ├── 2_Tree_Based_Models_Practice.pdf         # Practice materials
│   └── test.sql                                  # SQL queries
│
├── 2. Sequence_prediction/
│   ├── 3_Sequence_Prediction_Practice.html      # Results and analysis
│   ├── 1_Sequence_Modeling_for_Data_Mining.pdf  # Theoretical foundations
│   └── 2_Sequence_Prediction_Practice.pdf       # Practice guide
│
├── requirements.txt                              # Python dependencies
└── README.md                                     # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/ADM.git
   cd ADM
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open and run the notebooks**
   - Navigate to `1. Tree Based Methods/3_Notebook.ipynb` for ensemble methods
   - Check `2. Sequence_prediction/3_Sequence_Prediction_Practice.html` for sequence prediction results

## 🛠️ Technologies Used

- **Data Processing**: pandas, numpy
- **Machine Learning**: scikit-learn, XGBoost
- **Visualization**: matplotlib, seaborn
- **Environment**: Jupyter Notebook

## 📊 Key Implementations

### Tree-Based Methods
- **Decision Trees** with depth optimization
- **Random Forests** with feature importance ranking
- **Gradient Boosting** (scikit-learn and XGBoost)
- **AdaBoost** for ensemble learning
- **Feature Selection** using tree-based importance scores

### Model Evaluation Techniques
- Cross-validation scoring
- Grid search hyperparameter tuning
- Confusion matrices and classification reports
- Feature importance visualization

## 📖 Academic Context

These projects were developed as part of the **Algorithmics for Data Mining** curriculum, demonstrating:

- **Theoretical Understanding**: Comprehensive study of data mining algorithms
- **Practical Application**: Real-world problem solving with healthcare and environmental data
- **Performance Analysis**: Rigorous evaluation and comparison of different approaches
- **Best Practices**: Professional data science workflow and documentation

## 🎓 Learning Outcomes

- Implementation of ensemble learning methods
- Understanding of feature selection and model interpretability
- Experience with time series prediction and sequence modeling
- Proficiency in data mining evaluation metrics and validation techniques

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Developed as part of the Data Mining curriculum at UPC - Universitat Politècnica de Catalunya*
