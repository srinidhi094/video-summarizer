# video-summarizer
A simple and efficient tool to generate short summaries from YouTube videos using AI.

This Streamlit-based app allows users to input a YouTube video URL and receive a **detailed summary** of the video in bullet points — powered by **Google Gemini Pro**. It extracts the transcript using the YouTube Transcript API and summarizes the content using generative AI.

---

## ✨ Features

- 🔗 Accepts any YouTube URL
- 📜 Extracts transcript using `youtube-transcript-api`
- 🧠 Summarizes the transcript using Google Gemini Pro
- 🖼️ Displays the video thumbnail for context
- 📝 Outputs a clean, concise summary within **250 words**

---

## 🛠️ Tech Stack

- Python 3.10
- [Streamlit](https://streamlit.io/)
- [Google Generative AI (Gemini)](https://ai.google.dev/)
- [youtube-transcript-api](https://pypi.org/project/youtube-transcript-api/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

---

## ⚙️ Installation & Setup

<!-- ### 1. Clone the Repository -->

<!-- ```bash
git clone https://github.com/yourusername/youtube-transcriber-summarizer.git
cd youtube-transcriber-summarizer -->
Make sure you have Python 3.10 and Conda installed.

Clone the repository
```bash
git clone https://github.com/yourusername/youtube-transcriber-summarizer.git
cd youtube-transcriber-summarizer
```

Create and activate the virtual environment
```bash
conda create -p venv python=3.10 -y
conda activate venv/
```

Install the dependencies
```bash
pip install -r requirements.txt
```

Create a `.env` file in the root directory and add your Google Gemini API key:

```env
GOOGLE_API_KEY=your_google_api_key_here
```

Then run the app:

```bash
streamlit run app.py
```

---