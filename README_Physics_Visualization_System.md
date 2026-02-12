# AI-Powered Physics Visualization System

Project Title

AI-Powered Physics Visualization System

------------------------------------------------------------------------
 Description

The Physics Visualization System is an AI-powered interactive learning
platform that converts physics word problems into real-time visual
simulations.

Users can enter a physics problem in natural language, and the system:

-   Analyzes the problem using AI
-   Extracts physical entities and parameters
-   Classifies the problem type
-   Runs physics calculations
-   Generates an interactive simulation
-   Allows real-time parameter adjustments

This helps students understand physics concepts visually instead of only
mathematically.

------------------------------------------------------------------------

## 🛠 Tech Stack

### Frontend

-   React.js
-   Canvas API
-   TypeScript
-   Vite

### Backend

-   Node.js + Express
-   Python (Flask microservice)

### AI & Machine Learning

-   Claude API (AI analysis)
-   SpaCy (NLP entity extraction)
-   Scikit-learn (problem classification)

### Visualization & Simulation

-   Custom Physics Engine
-   Real-time animation loop
-   Parameter control sliders

------------------------------------------------------------------------

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone
https://github.com/your-username/physics-visualization-system.git cd
physics-visualization-system

### 2️⃣ Install Frontend Dependencies

cd frontend npm install npm run dev

### 3️⃣ Install Backend (Node.js)

cd backend npm install node server.js

### 4️⃣ Install Python ML Service

cd backend/ml pip install -r requirements.txt python
entity_extraction.py

### 5️⃣ Environment Variables

Create .env file:

ANTHROPIC_API_KEY=your_api_key PYTHON_SERVICE_URL=http://localhost:5000
PORT=3001

------------------------------------------------------------------------

## 📦 Dependencies

### Frontend

-   react
-   react-dom
-   vite
-   lucide-react
-   recharts

### Backend (Node)

-   express
-   cors
-   dotenv
-   axios
-   anthropic sdk

### Backend (Python)

-   flask
-   spacy
-   numpy
-   scikit-learn

------------------------------------------------------------------------

## ⚠️ Important Instructions

✔ Run Python ML service before backend\
✔ Backend must run before frontend\
✔ Add valid Claude API key\
✔ Install SpaCy model:

python -m spacy download en_core_web_sm

✔ Ports used: - Python → 5000 - Node → 3001 - Frontend → 5173 (default
Vite)

------------------------------------------------------------------------

## 🎬 MVP Demo Video

(Add your demo video link here)

------------------------------------------------------------------------

## 🖼 MVP Demo Images

(Add screenshots here)

------------------------------------------------------------------------

## 🧩 Key Features

-   Natural language physics problem input
-   AI-based parameter extraction
-   Automatic problem classification
-   Real-time physics simulation
-   Interactive visualization canvas
-   Adjustable parameters
-   Educational insights

------------------------------------------------------------------------

## 🏗 System Architecture

Frontend (React UI)\
⬇\
Node.js API layer\
⬇\
Python ML services\
⬇\
Physics Engine\
⬇\
Canvas Visualization

------------------------------------------------------------------------

## 🧪 Testing

npm run test

Includes: - Unit tests - Integration tests - Physics engine validation

------------------------------------------------------------------------

## 📈 Performance Optimizations

-   requestAnimationFrame rendering
-   AI result caching
-   Lazy loading components
-   Debounced parameter updates

------------------------------------------------------------------------

## 🎯 Target Users

-   Physics students
-   Teachers
-   Engineering learners
-   Interactive education platforms

------------------------------------------------------------------------

## 👨‍💻 Authors

    G Harshith Reddy
    G Sai Varun
    Haasini Gayathri SK
    K Poorna Chandra Raayudu

