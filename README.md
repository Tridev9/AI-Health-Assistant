# 🩺 AI Health Assistant

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)

An AI-powered health assistant that provides symptom analysis, medical recommendations, nutrition advice, and emergency assistance with multi-language support.

## ✨ Features

- **Symptom Analysis**: Describe your symptoms and get AI-powered assessment
- **Image Diagnosis**: Upload images of visible symptoms for analysis
- **Medication Recommendations**: Get specific medication suggestions with dosages
- **Multi-language Support**: English, Hindi, and Telugu output
- **Voice Output**: Listen to recommendations in your preferred language
- **Emergency Services**: Find nearby hospitals and emergency contacts
- **Nutrition Planning**: Get personalized dietary recommendations
- **Medication Purchase Links**: Find where to buy recommended medications
- **PDF Export**: Save nutrition plans as PDF

## 🛠️ Technologies Used

- **Google Gemini API** - For AI-powered health analysis
- **Streamlit** - Web application framework
- **Google Maps API** - For locating nearby medical facilities
- **gTTS (Google Text-to-Speech)** - For audio output
- **Firecrawl** - For medication product searches
- **FPDF** - For PDF generation

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-health-assistant.git
   cd ai-health-assistant
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Create a .env file and add your API keys:
   ```bash
   GEMINI_API_KEY=your_gemini_api_key
   GOOGLE_MAPS_API_KEY=your_google_maps_key
   FIRECRAWL_API_KEY=your_firecrawl_key
   ```
## 🏃‍♂️ Running the Application

1. Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```
2. Open your browser to:
   ```bash
   [[[python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`](http://localhost:8501)](http://localhost:8501)](http://localhost:8501)
   ```

## 📋 How to Use

1. Enter Symptoms: Describe your symptoms in detail

2. Upload Images (Optional): Add photos of visible symptoms

3. Provide Health Information: Fill in your medical history and details

4. Get Recommendations: Receive AI-powered health assessment

5. Explore Features:

  1. Listen to audio recommendations

  2. Get nutrition advice

  3. Find nearby hospitals in emergencies

  4. Search for medication purchase options

## 🌐 Supported Languages

   English

   Hindi (हिंदी)

   Telugu (తెలుగు)

## 📄 License

   This project is licensed under the MIT License - see the LICENSE file for details.
