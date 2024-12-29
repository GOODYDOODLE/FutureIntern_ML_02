# Decision Tree Classifier using Flower Dataset

Welcome to the Decision Tree Classifier project! This repository demonstrates the implementation of a decision tree model to classify flower species based on their features using the famous Iris dataset.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Overview
This project uses a decision tree classifier to predict the species of flowers based on their features such as sepal length, sepal width, petal length, and petal width. The Iris dataset is widely used for demonstrating machine learning algorithms, making it an excellent choice for this project.

---

## Features
- **Data preprocessing**: Ensures the dataset is clean and ready for model training.
- **Decision tree implementation**: Builds and visualizes a decision tree classifier.
- **Evaluation metrics**: Calculates accuracy, precision, recall, and F1-score to evaluate model performance.
- **Visualization**: Includes a tree diagram for better interpretability of the model.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/decision-tree-flower-dataset.git
   cd decision-tree-flower-dataset
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate # On Windows use `env\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Ensure the Iris dataset is available (it is typically included in popular libraries like `sklearn`).

2. Run the script:
   ```bash
   python decision_tree_classifier.py
   ```

3. View the results, including evaluation metrics and a visualization of the decision tree.

---

## Dataset
The project uses the Iris dataset, which contains 150 samples of iris flowers from three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each sample includes the following features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

The dataset is automatically loaded using `sklearn.datasets`.

---

## Results
The decision tree classifier achieves the following metrics:
- **Accuracy**: 95% (example)
- **Precision, Recall, F1-score**: Values depend on the specific train-test split.

Example visualization:
- A decision tree diagram that illustrates the splits and decision rules.

---

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


