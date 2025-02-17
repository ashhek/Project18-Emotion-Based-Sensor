# Project18 | Emotion-Based Playlist Generator

## 🎵 Overview
Project18 is an AI-powered emotion-based playlist generator that recommends Spotify playlists based on user sentiment. By analyzing textual input using advanced Natural Language Processing (NLP) techniques, it identifies the user's mood and provides an appropriate music playlist to enhance their experience.

## 🚀 Features
- **Sentiment Analysis:** Uses state-of-the-art NLP models to analyze text input and determine emotions.
- **Spotify API Integration:** Fetches curated playlists based on detected emotions.
- **User-Friendly UI:** Interactive and intuitive interface built using Streamlit or Gradio.
- **FastAPI Backend:** Efficient API endpoints to process user input and return recommendations.
- **Scalability:** Designed for seamless deployment on Vercel.

## 🛠 Tech Stack
- **Languages & Libraries:**
  - Python, Hugging Face Transformers, LangChain, TensorFlow/PyTorch, spaCy, NLTK
- **Frameworks & Tools:**
  - Streamlit/Gradio (UI), FastAPI (Backend)
- **APIs & Datasets:**
  - Spotify API, Kaggle, Hugging Face Hub, UCI ML Repository

## 🔧 Installation
### Clone the Repository
```bash
git clone https://github.com/ashhek/Project18-Emotion-Based-Sensor.git
cd Project18-Emotion-Based-Sensor
```
### Create a Virtual Environment
```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```
### Install Dependencies
```bash
pip install -r requirements.txt
```

## 🎯 Usage
### Run the Application
```bash
streamlit run app.py  # If using Streamlit
# OR
python -m uvicorn main:app --reload  # If using FastAPI
```
### Access the UI
- If using **Streamlit**: Open `http://localhost:8501`
- If using **FastAPI**: Open `http://localhost:8000/docs` for API documentation

## 📌 Evaluation Criteria
- **Functionality:** Accuracy of sentiment analysis and playlist recommendation.
- **Code Quality:** Modular and optimized structure.
- **GenAI Integration:** Effective use of transformer models for emotion detection.
- **Creativity:** Unique approach to playlist curation.
- **Scalability:** Efficient API handling and deployment on cloud platforms.

## 🌎 Deployment
- The project is optimized for **Vercel** deployment.
- Ensure environment variables (Spotify API credentials) are set before deployment.

## 💡 Future Enhancements
- Multi-language support for sentiment analysis.
- Integration with more music streaming services (Apple Music, YouTube Music).
- Voice-based emotion detection.

## 🤝 Contributing
Feel free to contribute by:
- Forking the repository
- Creating a new branch
- Making improvements and submitting a pull request




