# PathVera

PathVera is a career guidance platform that analyzes a user's resume and suggests suitable career options based on their skills and experience. The system processes resume data, compares it with occupational profiles, and generates career recommendations along with market insights.

The goal of the project is to help users understand which career paths align best with their existing skills.

## Main Features

- Resume upload and processing
- Skill extraction from resumes
- Career matching using semantic similarity
- Career recommendation engine
- Market data integration
- Career dashboard

## Technology Used

Backend
- Python
- Django

Machine Learning
- Scikit-learn
- Text embeddings
- Cosine similarity

Frontend
- HTML
- CSS
- JavaScript

Data
- Career profile datasets
- Skill datasets
- Job market data APIs

## How the System Works

1. User uploads a resume
2. Resume text is extracted
3. Skills are detected from the text
4. The resume is converted into an embedding
5. Career profiles are converted into embeddings
6. Cosine similarity is used to compare the resume with career profiles
7. Matching careers are identified
8. Market data is fetched and displayed

## Project Structure

PathVera
│
├── backend
│ ├── api
│ ├── core
│ ├── ml
│ │ ├── data
│ │ ├── models
│ │ └── pipeline
│ ├── static
│ ├── templates
│ └── manage.py
│
├── API_DOCUMENTATION.md
├── DJANGO_SETUP.md
├── QUICKSTART.md
└── README.md

## Installation

Clone the repository
git clone https://github.com/Himanshu5623/PathVera.git

cd PathVera
Create a virtual environment
python -m venv .venv
source .venv/bin/activate
Install dependencies
pip install -r backend/requirements.txt
Run the server
cd backend
python manage.py runserver
Open the application in a browser
http://127.0.0.1:8000

## Possible Improvements

- More advanced NLP for skill detection
- Better recommendation ranking
- Career growth prediction
- Additional job market integrations

## Author

Himanshu Agnihotri  
Lovely Professional University  
B.Tech CSE-[AI & ML]

## Note
This project was developed for academic and learning purposes.