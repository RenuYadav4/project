# Backend Installation Guide (FastAPI)

Follow the steps below to set up and run the FastAPI backend locally.

---

## Step 1: Prerequisites

Make sure the following are installed on your system:

- Python 3.10 or higher
- Git

Check Python version:
```bash
python --version

Installation Steps
Step 1: Clone the Repository
git clone <repository-url>
cd backend

Step 2: Create Virtual Environment
python -m venv venv

Step 3: Activate Virtual Environment (Windows PowerShell)
venv\Scripts\activate


After activation, you should see:

(venv)

Step 4: Install Dependencies
pip install -r requirements.txt

Step 5: Run the Development Server
uvicorn app.main:app --reload

Step 6: Access the Application

Open your browser and visit:

http://127.0.0.1:8000


API Documentation:

http://127.0.0.1:8000/docs


## Git Ignore Setup

Create a `.gitignore` file in the `backend/` directory to prevent committing
virtual environments, environment variables, and cache files.

The `.gitignore` should include:
- `venv/`
- `.env`
- Python cache files
