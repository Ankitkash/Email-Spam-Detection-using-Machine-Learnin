# Email Spam Detection using Machine Learning

## Project Overview

This project is an implementation of an **Email Spam Detector** using **Machine Learning**. It classifies emails as either **Spam** or **Ham** (not spam) using **Logistic Regression** and **TF-IDF (Term Frequency - Inverse Document Frequency) Vectorization**.

## Dataset

The dataset used in this project contains **5,572 emails** with the following columns:

- **Category**: Specifies whether the email is spam or ham.
- **Message**: The actual content of the email.

## Project Workflow

1. **Data Preprocessing**:
   - Load the dataset.
   - Handle missing values.
   - Convert categorical labels (spam/ham) into numerical values.
2. **Feature Extraction**:
   - Use **TF-IDF Vectorization** to convert text into numerical features.
3. **Model Training**:
   - Train a **Logistic Regression model** on the processed data.
4. **Model Evaluation**:
   - Calculate **accuracy** to assess model performance.

## Technologies Used

- **Python**
- **Pandas** (Data processing)
- **Scikit-learn** (Machine learning & evaluation)
- **TF-IDF Vectorizer** (Feature extraction)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ankitkash/email-spam-detector.git
   cd email-spam-detector
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook ML_Project_Spam_Ham.ipynb
   ```

## Results

The model achieves a high **accuracy score**, effectively distinguishing spam from non-spam emails.


