# invoice_data_extraction

This project uses Oracle Cloud Infrastructure (OCI) AI Document service to process and extract key-value pairs from invoice PDFs stored in Object Storage.

## Features
- Splits PDFs page by page and uploads to OCI Object Storage
- Run AI Document key-value extraction
- Collects and processes the output into a structured DataFrame

## Requirements
- Python 3.x
- OCI Python SDK
- PyPDF2
- pandas
