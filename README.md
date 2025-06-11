# PawTrack 🐾

PawTrack is a full-stack web application built with a **Django backend** and a **React + TypeScript + Tailwind frontend**.

---

## 📦 Clone the Repository

```bash
git clone https://github.com/chrs09/PawTrack.git
cd PawTrack
⚙️ Backend Setup (Python + Django)
cd backend

# Create virtual environment
python -m venv .venv

# Activate the virtual environment
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
pip install django

# Run migrations
python manage.py migrate

# Start Django development server
python manage.py runserver

🎨 Frontend Setup (React + Vite + Tailwind)
# Open a new terminal and navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev

🧹 Git Remote Setup

If remote is not yet set:
git remote add origin https://github.com/chrs09/PawTrack.git
git push -u origin main

If you see a remote conflict (because the GitHub repo already has a commit), run:
git pull origin main --allow-unrelated-histories
# Accept the merge message, then:
git push -u origin main
