# Customer Sentiment Analysis with OpenAI & Pandas

## 📌 Overview
This project is an **AI-powered Sentiment Analysis** tool designed to classify customer feedback as "Positive" or "Negative" automatically.

By leveraging **OpenAI's GPT-3.5-turbo** and **Prompt Engineering** techniques, the system processes batches of reviews from a dataset (JSON/CSV) and returns structured sentiment data. This approach demonstrates how Large Language Models (LLMs) can be integrated into data pipelines for efficient text analysis.

## 🚀 Key Features
* **Prompt Engineering:** Utilizes optimized system prompts and batch processing to analyze multiple reviews in a single API call (Cost & Time efficient).
* **Data Processing:** Uses **Pandas** to manage datasets and handle JSON/CSV formats seamlessly.
* **Sentiment Classification:** Accurately detects sentiment polarity (Positive/Negative) from customer reviews.
* **Security:** Implements secure API key handling using `getpass` to prevent key leakage in public repositories.

## 🛠️ Tech Stack
* **Python 3.x**
* **OpenAI API** (GPT Models)
* **Pandas** (Data Analysis)
* **Jupyter Notebook**

## 📂 Data Structure
The project accepts data containing a `review` column. Example of the input data:

| id | review |
|----|--------|
| 1  | The service was excellent and fast, highly recommended. |
| 2  | Bad experience, support was late to reply. |

## ⚙️ How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Your-Repo-Name.git](https://github.com/YourUsername/Your-Repo-Name.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install openai pandas python-dotenv
    ```
3.  **Run the Notebook:**
    Open `Prompt_Engineering.ipynb` in Jupyter.
4.  **Enter API Key:**
    When prompted, securely enter your OpenAI API key.

## 📈 Results
The model appends a new column to the DataFrame with the predicted sentiment, allowing for easy comparison and analysis.

---
*Created by Azzam Alotaibi*
