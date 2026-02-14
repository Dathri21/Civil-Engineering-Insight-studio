🏗️ Civil Engineering Insight Studio

An AI-powered web application that analyzes structural images and provides detailed civil engineering insights such as structure type, materials, dimensions, and construction methods.


🚀 Features

📷 Upload images of civil structures (bridges, buildings, etc.)

🤖 AI-based structural analysis using Google Gemini

🧠 Generates detailed engineering insights:

Structure type

Materials used

Dimensions

Construction methods

Engineering challenges

🌐 Simple and interactive UI using Streamlit

🛠️ Tech Stack

Frontend/UI: Streamlit

Backend: Python

AI Model: Google Gemini (Vision Model)

Libraries:

streamlit

google-generativeai

python-dotenv

pillow

📁 Project Structure
├── app.py               # Main Streamlit application
├── requirements.txt    # Dependencies
├── .env                # API keys (not included in repo)
└── README.md           # Project documentation

⚙️ Installation & Setup

1. Install Dependencies
pip install -r requirements.txt

2. Setup Environment Variables

Create a .env file in the root directory and add:

GOOGLE_API_KEY=your_api_key_here

 3.▶️ Run the Application

python -m streamlit run app.py

🧪 How It Works

1.User uploads an image of a structure

2.Image is processed using PIL

3.Input + image + prompt are sent to Gemini API

4.AI returns structured engineering insights

5.Results are displayed in the Streamlit UI


📌 Future Enhancements

📊 Add structural risk assessment

🧱 Support multiple images comparison

📍 Geolocation-based analysis

📄 Export reports as PDF

🧠 Improve accuracy with domain-specific models

