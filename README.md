# Employee Management System - FastAPI

This project is a simple **Employee Management System** built using **FastAPI**, **SQLAlchemy**, and **SQLite** for development purposes. It provides a RESTful API to manage employees with the ability to add, update, retrieve, and delete employee records. The application also supports pagination, sorting, and logging.

## Project Setup and Running

Follow the steps below to set up and run the project locally.

1. Clone the Repository

```bash
git clone https://github.com/your-username/employee-management-system.git
cd employee-management-system

2. Create a Virtual Environment
Make sure you're using Python 3.9 or higher.

On MacOS:

python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
Install the required dependencies using pip.

pip install -r requirements.txt
4. Database Setup
The project uses SQLite by default. The database and tables will be automatically created when you run the application.

5. Run the Application
Start the FastAPI server using Uvicorn.

uvicorn app.main:app --reload
Your application will be available at http://127.0.0.1:8000.

6. Testing the Application
The project uses pytest for unit and integration testing.

Run the tests using the following command:

pytest
