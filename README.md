# Full-Stack To-Do List Application

This project is a full-stack To-Do List application that integrates a React (Vite) frontend with a FastAPI backend. The backend provides a RESTful API and uses SQLite for data storage, while the frontend allows users to add, edit, delete, and filter tasks.

Setup Instructions

Prerequisites:
- Node.js and npm (for the React frontend)
- Python 3.9+ (for the FastAPI backend)


Frontend (React + Vite):
1. Clone the repository:
git clone <repository-url>
cd <repository-folder>

2. Install frontend dependencies:
npm install

3. Run the development server:
npm run dev

The frontend will be available at: http://localhost:5173

Backend (FastAPI):
1. Navigate to the backend directory:
cd fastapi-backend

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install backend dependencies:
pip install -r requirements.txt

4. Run the FastAPI development server:
uvicorn main:app --reload

The backend will be available at: http://localhost:8000

Backend API Endpoints (Base path: /jazeltodo):

GET https://pit4backend.onrender.com/jazeltodo/
Description: Fetch all to-do items.

POST https://pit4backend.onrender.com/jazeltodo/
Description: Create a new to-do item.

GET https://pit4backend.onrender.com/jazeltodo/{todo_id}
Description: Fetch a single to-do item by ID.

PUT https://pit4backend.onrender.com/jazeltodo/{todo_id}
Description: Update a to-do item by ID.

DELETE https://pit4backend.onrender.com/jazeltodo/{todo_id}
Description: Delete a to-do item by ID.

Live Deployment (optional):

Frontend (GitHub Pages): https://jazeljeanachas.github.io/pit4FRONTEND/
Backend (Render): https://pit4backend.onrender.com/docs
