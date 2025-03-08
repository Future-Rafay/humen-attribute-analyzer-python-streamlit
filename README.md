# Human Attribute Analyzer

An AI-powered application that analyzes human attributes from images using **Google Gemini AI**. The app provides details such as age estimation, gender, mood, facial expressions, and more.

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 🚀 Features
- Upload an image for AI-based attribute analysis
- Provides demographic details (age, gender, ethnicity)
- Detects facial attributes (hair color, eye color, glasses, beard, etc.)
- Analyzes mood and emotions
- Displays confidence level and processing time
- Custom instructions for enhanced analysis
- Responsive and intuitive UI

## 🛠️ Technologies Used
- **Streamlit** - For the web interface
- **Google Gemini AI** - For human attribute analysis
- **PIL (Pillow)** - For image processing
- **JSON** - To structure AI responses
- **Python** - Backend logic and AI integration

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/human-attribute-analyzer.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd human-attribute-analyzer
   ```

3. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```bash
   streamlit run app.py
   ```

## ⚙️ Configuration
Replace `GOOGLE_API_KEY` with your own Google Gemini API key in `app.py`:

```python
GOOGLE_API_KEY = "your-google-api-key"
genai.configure(api_key=GOOGLE_API_KEY)
```

## 🎯 Usage
1. Open the web app in your browser.
2. Upload an image of a human face.
3. (Optional) Provide additional instructions for AI analysis.
4. View detailed attribute analysis.
5. Check raw AI-generated data if needed.

## ⚠️ Disclaimer
- **Powered by Google Gemini AI**
- **Results are AI-generated and may not be 100% accurate.**
- **The author holds no responsibility for any inaccuracies in the results.**

## 💡 Author
**Abdul Rafay**  
Built with ❤️ using Streamlit  
[GitHub](https://github.com/Future-Rafay/) | [LinkedIn](https://www.linkedin.com/in/rafay-nadeem-web-developer/)
