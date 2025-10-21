# Render deployment configuration
# This file helps Render understand how to deploy your application

# Frontend (Static Site)
# Build command: cd frontend && npm install && npm run build
# Publish directory: frontend/dist
# Environment variables needed:
# - VITE_FIREBASE_API_KEY
# - VITE_FIREBASE_AUTH_DOMAIN  
# - VITE_FIREBASE_PROJECT_ID
# - VITE_FIREBASE_STORAGE_BUCKET
# - VITE_FIREBASE_MESSAGING_SENDER_ID
# - VITE_FIREBASE_APP_ID

# Backend (Web Service)
# Build command: cd backend && pip install -r requirements.txt
# Start command: cd backend && python app.py
# Environment variables needed:
# - GEMINI_API_KEY
# - FLASK_SECRET_KEY
# - JWT_SECRET_KEY
# - PORT (Render will set this automatically)
