# FastAPI-Cohort
Learning Fast API from beginning to Advance

#API : Application Programming Interface

# Setup Python Virtual Enviroment
#How to check Python version into your from your terminal
    - python -V
    - python --version
#Macbook
    - python3 -m venv fast-venv
#Windows

virtualenv fast-venv

# Activate Virtual Enviroment
- Mac
source fast-venv/bin/activate

- Windows
source fast-venv\Scripts\activate

# Clone Repo

git clone https://github.com/pankajit/FastAPI-Cohort.git


#Part 1 - Basic Setup  - Hello World with SQLite

    - Step 1 - Install Require Packages

        - command : pip install fastapi uvicorn sqlalchemy pydantic

    - Steps 2 - Project Structure 

        FASTAPI_PROJECT/
            - main.py           # Entry Point
            - models.py         # SQLAlchemy Models
            - schemas.py        # Pydantic schemas 
            - database.py       # Database connection
            - crud.py           # CRUD Operations
            - requirements.txt  # Optional : Dependencies List 
            
    - Updated requirements.txt file with install package into current virtual env

    pip freeze > requirements.txt 

#Part 2 - Database Setup with SQLAlchemy 

-- check database.py 


#Part 3 - Define Models and Schemas

    - completed 

#Part 4 - Create CRUD Operations
    - completed

#Part 5  - Create Fast API Endpoints 
    - completed


#Part 6 - Run the Application

    - completed 




# API METHOD HTTP:

    GET -   Listing a data 
    POST -   Post the data via HTTP  
    PUT -  UPDATE 
    DELETE -  DELETE


#Part 7 - Advanced Features


#Part 8 - Handling Relationship ( One to Many )


#Part 9 -  Push to Github


#Part 10 - Frontend
