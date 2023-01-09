# How to install and run

## install venv
python -m venv .venv

## install dependencies
.venv\scripts\activate
pip install -r requirements.txt

## run server
uvicorn main:app --reload