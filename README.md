# story-spark-app

🚀 **Story Spark** is a web application that generates AI-powered short stories and illustrations.

## 🌐 Live Demo
🔗 https://story-spark-frontend.onrender.com 

## 📌 Features
✅ AI-generated short stories  
✅ AI-generated images  
✅ Responsive reading layout  

## 🛠 Tech Stack
- **Frontend:** React, Material-UI
- **Backend:** NestJS, OpenAI API
- **Deployment:** Render

## 🛠 Installation & Setup

### 📥 1. Clone the Repository

git clone https://github.com/cristinaAlarcon98/story-spark-app.git story-spark
cd story-spark


1️⃣Install Dependencies
cd frontend
npm install
cd ../backend
npm install

2️⃣ Set Up Environment Variables
Create a .env file in both frontend/ and backend/:

Frontend .env
REACT_APP_API_URL=https://story-spark-backend.onrender.com || https://localhost:9090
Backend .env
OPENAI_API_KEY=your-api-key

3️⃣ Run the Project
Run the backend:
cd backend
npm run start
Run the frontend:
cd ../frontend
npm start
