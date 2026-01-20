# Loan-Eligibility-Checker-Python
The Loan Eligibility Checker is a Python-based mini project that automates bank loan approval decisions. It evaluates age, income, credit score, and employment status using conditional logic to approve or reject loans and classify approved loans as Premium or Standard.
# 🏦 Loan Eligibility Checker (Python)

## 📌 Project Description
The **Loan Eligibility Checker** is a Python-based mini project that automates bank loan approval decisions. It evaluates age, income, credit score, and employment status using conditional logic to approve or reject loans and classify approved loans as Premium or Standard.

## 🎯 Problem Statement
Banks often require a structured process to assess loan eligibility. Manually evaluating applications can be time-consuming and error-prone. This project aims to simplify that process by automating eligibility checks using predefined business rules.

## 🛠 Tools & Technologies
* **Programming Language:** Python 3
* **IDE / Editor:** VS Code / Jupyter notebook
* **Version Control:** Git
* **Platform:** GitHub

## 📂 Project Structure
loan-eligibility-checker/
│
├── loan_eligibility.py   # Main Python script
├── README.md             # Project documentation

## ✨ Features Implemented
* Collects user input for: Age, Monthly income, Credit score, Employment status
* Validates eligibility based on business rules
* Displays clear rejection reasons if criteria are not met
* Approves loan only when all conditions are satisfied
* Classifies approved loans into:
  * **Premium Loan** (Credit score ≥ 750)
  * **Standard Loan** (Credit score between 650–749)

## 🧠 Eligibility Rules
The loan decision is made using the following conditions:
1. Age must be **21 years or above**
2. Monthly income must be **₹20,000 or more**
3. Credit score must be **650 or above**
4. Applicant must be **employed**

## 📊 Decision Logic
*  All conditions satisfied → **Loan Approved**
*  Age < 21 → *Loan Rejected: Age criteria not met*
*  Income < ₹20,000 → *Loan Rejected: Insufficient income*
*  Credit score < 650 → *Loan Rejected: Low credit score*
*  Unemployed → *Loan Rejected: Employment required*

## 📈 Findings & Learnings
* Conditional statements are powerful tools for implementing real-world business logic
* Clear and specific rejection messages improve user understanding
* Input validation and logical order of conditions are crucial for correct decisions
* This project simulates how basic banking decision systems work

## 🔮 Future Enhancements
* Add input validation for incorrect or empty inputs
* Convert the script into a function-based or OOP design
* Store applicant details in a file or database
* Build a simple GUI or web interface

## 🧾 Conclusion
The **Loan Eligibility Checker** successfully demonstrates how Python can be used to automate decision-making processes in the banking domain. By applying simple `if–elif–else` logic, the project ensures transparency, accuracy, and consistency in loan approval decisions. This project serves as a strong foundation for beginners and can be extended into more advanced financial applications.
