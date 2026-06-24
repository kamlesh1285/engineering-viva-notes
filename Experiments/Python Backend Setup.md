Python Backend Setup
Create Virtual Environment:-

mkdir attendance-backend
cd attendance-backend

python -m venv venv

Activate environment:-

Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate

Install packages:-

pip install flask

or

pip install fastapi uvicorn

Save dependencies:-

pip freeze > requirements.txt

Run Flask app:-

python app.py

Run FastAPI app:-

uvicorn main:app --reload