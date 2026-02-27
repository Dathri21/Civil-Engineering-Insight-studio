🏗️ Civil Engineering Insight Studio

An AI-powered web application that analyzes structural images and generates detailed civil engineering insights such as structure type, materials, dimensions, and construction methods.

🚀 Features

📷 Upload images of civil structures (bridges, buildings, etc.)

🤖 AI-powered analysis using Google Gemini (Vision Model)

🧠 Generates detailed insights:

Structure type

Materials used

Dimensions

Construction methods

Engineering challenges

🌐 Interactive and user-friendly UI built with Streamlit

🛠️ Tech Stack

Frontend/UI: Streamlit

Backend: Python

AI Model: Google Gemini (Vision)


📦 Libraries Used

streamlit

google-generativeai

python-dotenv

pillow

📁 Project Structure
├── app.py              # Main application
├── requirements.txt   # Dependencies
├── .env               # API keys (excluded from repo)
└── README.md          # Documentation

⚙️ Installation & Setup

1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Configure Environment Variables

Create a .env file in the root directory:

GOOGLE_API_KEY=your_api_key_here

3️⃣ Run the Application
python -m streamlit run app.py

🧪 How It Works

User uploads an image of a structure

Image is processed using PIL

Image + prompt are sent to Gemini API

AI analyzes and generates engineering insights

Results are displayed in the UI

📌 Future Enhancements

📊 Structural risk assessment

🧱 Multi-image comparison

📍 Location-based analysis

📄 Export results as PDF reports

🧠 Integration with domain-specific models for higher accuracy

⭐ Project Highlights

Combines AI + Civil Engineering

Real-time image-based analysis

Simple, clean, and interactive interface

Scalable for advanced engineering applications



Demo Video : https://drive.google.com/file/d/1R7PhtuKgt77pGPsXJHCdXdilRKcZPMvx/view?usp=drivesdk

project Documentation : https://docs.google.com/document/d/1oc1gnXaLyjhSeexJOXAJAxTzeXqfU81D/edit?usp=drivesdk&ouid=112734407717090411409&rtpof=true&sd=true
