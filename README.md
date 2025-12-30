# Automated Email Classification & Smart Response Generator

## Project Overview
This project is an AI-driven email automation system developed within the **Pydroid 3** environment. It uses **Natural Language Processing (NLP)** and **Neural Networks** to analyze incoming emails, classify them into business-specific categories (Urgent, Sales, Query), and generate professional draft responses automatically.

## Core Functionalities
* **Email Categorization:** Automatically identifies the priority and intent of the email text (e.g., distinguishing an urgent technical issue from a general inquiry).
* **Auto-Response Generation:** Based on the identified category, the system selects and prepares a professional reply template to ensure rapid communication.
* **Intelligent Inference:** Uses a confidence-based model to classify text even with varying input lengths.

## Key Technical Features
* **Model Architecture:** Implemented a **Multi-layer Perceptron (MLP)** neural network for robust text classification.
* **Feature Engineering:** Utilized **TF-IDF Vectorization** to transform raw email bodies into numerical feature vectors that highlight word importance.
* **Optimized Deployment:** Specifically engineered to run efficiently on mobile hardware using **Scikit-Learn**, bypassing the need for heavy, paid deep learning frameworks.

## Tech Stack
* **Language:** Python
* **Machine Learning:** Scikit-Learn (MLP, TfidfVectorizer)
* **Data Handling:** Pandas, NumPy
* **Platform:** Pydroid 3 (Mobile IDE)

## Usage Example
1. Run `main.py`.
2. Input the content of an email when prompted.
3. The system will output the detected category and a generated reply draft.

```text
Input: "Server is down, fix it immediately!"
Detected Category: URGENT
Generated Draft: "Subject: [Auto-Reply] Urgent Support Received. Body: Hello, our team is working on your urgent request..."
