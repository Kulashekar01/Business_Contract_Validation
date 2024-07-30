
# Business Contract Validation

Welcome to the Business Contract Validation project! This web application is designed to parse, analyze, and validate business contracts by comparing them with predefined templates. It helps in identifying key details, clauses, sub-clauses, and deviations from the standard template.

## Overview

The application processes contract documents uploaded in PDF format, leveraging advanced natural language processing (NLP) techniques to clean and normalize text. It identifies entities and clauses, compares the contract with selected templates, highlights deviations, and provides insightful summaries.

## Features

- **Upload and Process Contracts:** Easily upload PDF contracts for analysis.
- **Text Normalization:** Clean and normalize contract text using NLP.
- **Clause Identification:** Detect and classify entities and clauses within the contract.
- **Template Comparison:** Compare contract text with a chosen template to find deviations.
- **Highlighting and Summarization:** Highlight key terms and generate detailed summaries.
- **Visualization:** View contract insights and analysis results through a user-friendly Streamlit interface.

## Getting Started

### Forking the Repository

1. **Fork the Repository:** Click the "Fork" button on the top-right corner of the [GitHub repository page](https://github.com/Kulashekar01/Business_Contract_Validation).
2. **Clone Your Forked Repository:** Run the following command:
   ```bash
   git clone https://github.com/your-username/business_contract_validation.git
   ```
3. **Create a New Branch:** Switch to a new branch for your changes:
   ```bash
   git checkout -b your-feature-branch
   ```

### Installation

#### GitHub

1. **Install Dependencies:** Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
2. **Run the Application:** Start the Streamlit application:
   ```bash
   streamlit run app.py
   ```

#### Docker

1. **Pull the Docker Image:** Get the latest Docker image:
   ```bash
   docker pull asiyamohammad/business_contract_validation
   ```
2. **Run the Docker Container:** Launch the container:
   ```bash
   docker run -p 8501:8501 asiyamohammad/business_contract_validation
   ```
3. **Access the Web Application:** Open your browser and navigate to:
   ```
   http://localhost:8501
   ```

## Usage

1. **Upload a Contract:** Choose and upload a PDF contract file.
2. **Select a Template:** Pick a template for comparison.
3. **View Insights:** Examine the contract insights, highlighted terms, and summary.

## Execution Video

Watch the demo of the application 

https://github.com/user-attachments/assets/39a1c1a9-e1b4-4cee-81b9-f49ce50a4c06
