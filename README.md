# 21BCY10003_ML
# Document Retrieval System (Aditya Rahangdale 21BCY10003)


## Setup Instructions

## Local Setup

 *Install dependencies*


pip install -r requirements.txt


 *Initialize the database:*


python -c "from app.models import init_db; init_db()"


 *Run the FastAPI server:*


uvicorn app.api:app --reload


Access the API:

- Healther  checker for localhost: http://localhost:8000/health
- API on docs retrieved: http://localhost:8000/docs

## . Docker Setup

1. Build the Docker image for the docker:


docker build -t document-retrieval


2. Run the Docker container for these: the 


docker run -p 8000:8000 document-retrieval



### Collaborator
- recruitments@trademarkia.com
