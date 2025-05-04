# Machine-Learning-Fake-News-Detection-
Detecting fake news in texts using SVMand logistic regression model and comparing both using different vectorizers 

# Fake News Detection Using Machine Learning

This project implements a machine learning approach to detect fake news articles. Utilizing Support Vector Machine (SVM) and Logistic Regression classifiers, it compares their performance using different vectorization techniques like Count Vectorizer and TF-IDF Vectorizer.

##  Project Structure

* **ML\_project.ipynb**: Jupyter Notebook containing data preprocessing, model training, evaluation, and comparison.
* **README.md**: Project documentation.

##  Dataset

The dataset comprises news articles labeled as real or fake. It includes features such as:

* **Title**: The headline of the news article.
* **Text**: The full content of the news article.
* **Label**: Binary indicator where 1 denotes fake news and 0 denotes real news.

*Note: Ensure the dataset is available in the working directory or update the path accordingly in the notebook.*

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Muskancodes21/Machine-Learning-Fake-News-Detection-.git
   cd Machine-Learning-Fake-News-Detection-
   ```

2. **Create a virtual environment (optional but recommended)**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages**:

   ```bash
   pip install -r requirements.txt
   ```

   *If `requirements.txt` is not provided, install the following packages manually:*

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

##  Usage

1. **Open the Jupyter Notebook**:

   ```bash
   jupyter notebook ML_project.ipynb
   ```

2. **Follow the steps in the notebook**:

   * Load and preprocess the dataset.
   * Vectorize the text data using Count Vectorizer and TF-IDF Vectorizer.
   * Train SVM and Logistic Regression models.
   * Evaluate and compare model performances using metrics like accuracy, precision, recall, and F1-score.

## Results

The models are evaluated based on their performance metrics. The comparison helps in understanding which combination of vectorizer and classifier yields better results in detecting fake news.

*Note: Detailed results and visualizations are available in the Jupyter Notebook.*


