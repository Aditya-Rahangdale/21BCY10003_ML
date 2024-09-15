# 21BCY10003_ML
# Document Retrieval System (Aditya Rahangdale 21BCY10003)


## Setup Instructions

## 1. Local Setup

1. *Install dependencies*


pip install -r requirements.txt


2. *Initialize the database:*


python -c "from app.models import init_db; init_db()"


3. *Run the FastAPI server:*


uvicorn app.api:app --reload


Access the API:

- Health check: http://localhost:8000/health
- API docs: http://localhost:8000/docs

## 2. Docker Setup for these

1. Build the Docker image:


docker build -t document-retrieval


2. Run the Docker container for these:


docker run -p 8000:8000 document-retrieval



### Collaborator
- recruitments@trademarkia.com
