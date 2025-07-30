# Data Science Challenge Library (DSCL)

A curated collection of interactive challenges and datasets designed to help students, educators, and data science enthusiasts practice and learn fundamental to advanced AI/ML concepts. Access the live App: [https://dscl.azurewebsites.net](https://dscl.azurewebsites.net)

## Features

- Real-world datasets across classification, regression, NLP, deep learning, etc.
- Challenges organized by difficulty and topic
- Use cases and starter tips to approach each challenge
- Full-stack web app with a Flask backend and Vite + React frontend

---

## Local Setup

Clone the repository:

```bash
git clone https://github.com/thomasbritnell/DSCL.git
cd DSCL

### 1 Backend Server
In the first terminal:

cd backend
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py

## Seed the Database
In the second terminal:

cd backend
source venv/bin/activate
python seed_data.py

## Frontend Server
In the third terminal:

cd frontend
npm install  # Run once
npm run dev

Open http://localhost:5173 to view the frontend.

## Project Structure

DSCL/
├── backend/             # Flask app and database scripts
├── frontend/            # React + Vite frontend
└── README.md            # You're here!

## Tech Stack
- Frontend: React + Vite + TailwindCSS
- Backend: Python + Flask + SQLAlchemy
- Database: SQLite (local dev)
- Hosting: Azure (live)

## Future Plans
- Challenge submission + leaderboard
- User auth
- Custom challenge uploads
- AutoML integration

## Contributing
Open an issue or PR. Contributions are welcome!

## License
MIT License
