# Use the official lightweight Python image.
FROM python:3.12-slim

# Set the working directory in the container.
WORKDIR /app

# Copy the requirements file into the container.
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir tensorflow 
RUN pip install --no-cache-dir tf-keras
# Install the dependencies.
RUN pip install --no-cache-dir streamlit
RUN pip install --no-cache-dir transformers
RUN pip install --no-cache-dir PyPDF2
RUN pip install --no-cache-dir nltk
RUN pip install --no-cache-dir pdfplumber
RUN pip install --no-cache-dir pymupdf

# Copy the rest of the application code into the container.
COPY . .

# Set environment variable to fix protobuf issue
ENV PROTOCOL_BUFFERS_PYTHON_IMPLEMENTATION=python

# Expose the port Streamlit will run on
EXPOSE 8501

# Command to run the Streamlit app.
CMD ["streamlit", "run", "business_contract_validation.py"]