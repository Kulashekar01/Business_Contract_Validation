# Business_Contract_Validation
This app is developed to parse the documents so that have a structure to them. Determine the key details within the contract document. Every contract has clauses and sub-clauses. Typically, a contract has an associated template to it, and it is important to determine the deviations from that template and highlight them.

# Overview
This project develops a web application to validate business contracts by uploading, processing, and analyzing contract texts. It utilizes natural language processing (NLP) techniques, entity recognition, and template comparison to provide insights into contract clauses and deviations.

# Features
Upload and process contracts in PDF format
Clean and normalize contract text using NLP
Identify entities and clauses in contract text
Compare contract text with selected templates
Highlight keywords and generate contract summaries
Visualize contract insights using Streamlit
# Steps to Use the Project
# Forking the Repository
Fork the repository: Click the "Fork" button on the top-right corner of the GitHub page
Clone your forked repository: git clone `https://github.com/your-username/business_contract_validation.git`
Create a new branch: git checkout -b your-feature-branch
# GitHub
Install dependencies: pip install -r requirements.txt
Run the application: streamlit run app.py
# Docker
Pull the Docker image: docker pull `asiyamohammad/business_contract_validation`
Run the Docker container: `docker run -p 8501:8501 asiyamohammad/business_contract_validation`
Access the web application:` http://localhost:8501`
# Usage
Upload a contract PDF file
Select a template for comparison
View contract insights, highlighted text, and summary
