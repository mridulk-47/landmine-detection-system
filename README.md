# Landmine Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.7%2B-blue) 
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)

## 📌 Overview
This project implements a machine learning-based system for detecting landmines using ground-penetrating radar (GPR) data. The system analyzes various signal features to accurately classify whether a detected object is a landmine or harmless debris, significantly improving the efficiency and safety of demining operations.

## 🚀 Features
- **Signal Processing**: Extracts key features from GPR signals
- **Data Visualization**: Interactive plots for exploratory data analysis
- **Feature Engineering**: Creates additional meaningful features for better model performance
- **Machine Learning**: Implements and compares multiple classification algorithms
- **Model Evaluation**: Comprehensive performance metrics and visualization

## 🛠️ Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/landmine-detection.git
   cd landmine-detection
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Dataset
The project uses the [Landmine Detection Dataset](https://www.kaggle.com/datasets/ritwikb3/land-mines-detection) from Kaggle, which contains GPR signal features collected from various terrains. The dataset includes multiple features extracted from radar signals and corresponding labels indicating whether a landmine is present.

## 🧠 Project Files
- `Landmine.ipynb`: Main Jupyter notebook containing the complete analysis
- `requirements.txt`: List of Python dependencies
- `data/`: Directory containing the dataset (not included in repository)

## 🚦 Usage
1. **Data Preparation**:
   - Download the dataset from [Kaggle](https://www.kaggle.com/datasets/ritwikb3/land-mines-detection)
   - Place the dataset files in the `data/` directory

2. **Running the Analysis**:
   Open and run the Jupyter Notebook `Landmine.ipynb` to:
   - Load and explore the dataset
   - Preprocess the data
   - Perform feature engineering
   - Train machine learning models
   - Evaluate model performance

## 📈 Results
The project demonstrates the effectiveness of different machine learning algorithms in detecting landmines from GPR data, with detailed analysis of:
- Model accuracy and performance metrics
- Feature importance analysis
- Confusion matrices
- ROC curves

## 🙏 Acknowledgments
- [Kaggle](https://www.kaggle.com/) for hosting the dataset
- The machine learning community for open-source tools and libraries
