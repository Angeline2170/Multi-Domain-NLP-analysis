# Multi-Domain-NLP-analysis
An NLP project to classify sentiment and product domains from customer reviews using Python, scikit-learn, and SpaCy.
# Multi-Domain Text Analysis of Customer Feedback



### Project Objective
This project focuses on building a complete Natural Language Processing (NLP) system to analyze and extract insights from customer reviews across multiple product domains. The system performs three key tasks: sentiment analysis, domain classification, and named entity recognition.

---

### Dataset
The project utilizes the **Johns Hopkins Multi-Domain Sentiment Dataset**, which contains product reviews for four distinct categories: Books, DVDs, Electronics, and Kitchen Appliances.

---

### Key Features & Tasks

* **Text Preprocessing:** A comprehensive pipeline to clean raw text data using NLTK, involving lowercasing, stop-word removal, and lemmatization to prepare the corpus for modeling.
* **Domain Classification:** A machine learning model built with scikit-learn that accurately predicts the product domain (e.g., Electronics, Books) of a given review.
* **Sentiment Analysis:** A logistic regression model trained to classify customer reviews as either Positive or Negative.
* **Named Entity Recognition (NER):** Implementation of SpaCy's pre-trained models to automatically identify and extract key entities like brand names, products, and organizations from unstructured text.

---

### Tech Stack & Libraries

* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Text Processing:** NLTK, SpaCy
* **Machine Learning:** scikit-learn


---

### How to Run This Project

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/](https://github.com/)[Angeline2170]/multi-domain-nlp-analysis.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd multi-domain-nlp-analysis
    ```
3.  **Install the required packages:**
    (First, you should create a `requirements.txt` file by running `pip freeze > requirements.txt` in your terminal)
    ```sh
    pip install -r requirements.txt
    ```
4.  **Run the Jupyter Notebook:**
    ```sh
    jupyter notebook your_project_notebook.ipynb
    ```

---

### Model Performance

Here you can showcase your results. For example:

**Domain Classification Model:**
*Achieved an overall accuracy of 94%.*

| Domain      | Precision | Recall | F1-Score |
|-------------|-----------|--------|----------|
| Books       | 0.92      | 0.93   | 0.92     |
| Electronics | 0.95      | 0.96   | 0.95     |
| ...         | ...       | ...    | ...      |

**Sentiment Analysis Model:**
*Achieved an overall accuracy of 91%.*

---

### Contact

Angeline Feliciana Lewis - [linkedin.com/in/angeline-lewis-567660356](https://linkedin.com/in/angeline-lewis-567660356)
