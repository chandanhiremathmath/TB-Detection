🫁 Lungify - Tuberculosis Detection System
Lungify is an intelligent web-based application that aids early detection of Tuberculosis (TB) through two powerful modules:

X-ray Image Detection
Symptom-Based Prediction
Built with a modern, user-friendly interface, Lungify is designed to be accessible, efficient, and informative. It also includes an interactive chatbot and a TB awareness quiz for public education.

🚀 Features
🧠 X-ray Based Detection
Upload chest X-rays to detect signs of TB using a deep learning model.

🤒 Symptom-Based Detection
Users can answer a short survey to get risk assessment based on symptoms.

🧑‍⚕️ User Authentication
Secure login & registration with fields like name, age, gender, and mobile number.

💬 AI Chatbot
Integrated Gemini-powered chatbot to answer TB-related questions in real time.

🧪 TB Awareness Quiz
A fun and educational quiz to test users' knowledge about Tuberculosis.

📊 Results Dashboard
View your predictions and track your reports.

🛠️ Tech Stack
Frontend: HTML, CSS (inline + modern design), JavaScript
Backend: Flask (Python)
ML Models: TensorFlow/Keras & Symptom-based ML model
AI Chatbot: Google Gemini API
Hosting: Localhost / Deployable on platforms like Render, Vercel, or Heroku
📂 Folder Structure
TB_Detection_App/ │ ├── static/# Styles, JS, assets ├── templates/ # HTML templates │ ├── home.html │ ├── login.html │ ├── register.html │ ├── result.html │ ├── xray_upload.html │ └── quiz.html ├── models/ # ML model files ├── chatbot/ # Gemini chatbot integration ├── app.py # Flask backend app ├── requirements.txt # Python dependencies └── README.md

🧪 How to Run
Clone or download the repository

Install dependencies: pip install -r requirements.txt

Run the app:

Open in browser: like http://localhost:5000

📚 How to Use
Register with name, age, mobile number, and gender.
Choose between:
Uploading a chest X-ray
Filling out a symptom survey
View results instantly.
Chat with the AI bot or take the quiz to learn more!

🙌 Made for Hackathons
This project is built to demonstrate:

Real-world impact
AI/ML for good
Clean UI/UX
Educational outreach (chatbot + quiz)
🧠 Future Enhancements
📱 Mobile responsive version
☁️ Cloud-based model hosting
🏥 Integration with hospital systems


