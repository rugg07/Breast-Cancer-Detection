# Breast Cancer Detection

Welcome to the **Breast Cancer Detection** repository. This project leverages machine learning techniques to develop a predictive model for breast cancer diagnosis using clinical and diagnostic data. The primary objective is to assist medical professionals by providing a reliable computational tool for early detection and diagnosis of breast cancer.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Workflow](#project-workflow)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Model Performance](#model-performance)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

---

## Introduction

Breast cancer is one of the most common forms of cancer globally. Early detection significantly increases the chances of successful treatment and survival. This project employs machine learning algorithms to classify tumor samples as **malignant** or **benign**, using features extracted from medical data such as:

- Mean radius, texture, perimeter, and area of cells.
- Compactness, symmetry, and other diagnostic measurements.

---

## Dataset

The dataset used for this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

### Key Features:
- **Number of Samples:** 569
- **Features:** 30 (e.g., radius, texture, area, smoothness)
- **Target Labels:** Malignant (1), Benign (0)

---

## Project Workflow

1. **Exploratory Data Analysis (EDA):**
   - Visualized data distributions and relationships among features.
   - Checked for missing values and performed data cleaning.

2. **Feature Engineering:**
   - Selected significant features using statistical methods.
   - Scaled features for consistent model performance.

3. **Model Development:**
   - Trained and evaluated several machine learning models, including:
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Random Forest
     - Gradient Boosting
   - Optimized hyperparameters for the best performance.

4. **Evaluation:**
   - Assessed models using metrics like accuracy, precision, recall, and F1-score.

5. **Deployment:**
   - Provided a streamlined process to make predictions on new data.

---

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/rugg07/Breast-Cancer-Detection.git
   cd Breast-Cancer-Detection
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Ensure the dataset is available in the specified folder (see project structure).
2. Run the Jupyter Notebook to train models or make predictions:
   ```bash
   jupyter notebook
   ```
3. Open the `BreastCancerDetection.ipynb` file and execute the cells step by step.

For predictions, you can also use the `predict.py` script:
```bash
python predict.py --input_path <path_to_input_file>
```

---

## Model Performance

The final model achieved the following metrics on the test dataset:

| Metric          | Score  |
|-----------------|--------|
| Accuracy        | 98.5%  |
| Precision       | 97.8%  |
| Recall          | 98.2%  |
| F1-score        | 98.0%  |

---

## Contributing

Contributions are welcome! If you have suggestions for improvement or want to add features, feel free to:

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

If you have any questions or suggestions, feel free to contact me:

- **Name:** Hrugved Pawar
- **Email:** ruggvedp@gmail.com
- **GitHub:** [@rugg07](https://github.com/rugg07)

---

Thank you for checking out this project! Your feedback is invaluable.

