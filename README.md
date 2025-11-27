# 📚 AI Study Buddy

An intelligent and interactive web app that helps students study smarter using **Gemini AI (Google Generative AI)**.  
This tool offers live chat with AI, flashcard generation, quiz mode, and a smart study timer — all inside a clean, dark-themed UI with theme toggle support.
Used the API's of genai in this project.

---

## ✅ Features

- Ask questions and get answers from Gemini AI
- Generate flashcards based on any topic
- Take multiple-choice quizzes with answer reveal
- Track study time with start/stop/save functionality
- Dark/light theme toggle 🌗
- Clean, mobile-responsive UI

---

## 💻 Tech Stack

- **Frontend:** HTML, Tailwind CSS, JavaScript  
- **Backend:** Python Flask  
- **AI Model:** Gemini (via Google Generative AI)  
- **API Library:** `google-generativeai`  
- **Environment:** Localhost (no DB required)  

---

### Home Screen
![Screenshot 2025-06-20 152555](https://github.com/SanjanaDasari26/AI-study-buddy/blob/main/images1/Screenshot%202025-06-20%20152555.png)

### Chat section
![Screenshot 2025-06-20 152717](https://github.com/SanjanaDasari26/AI-study-buddy/blob/main/images1/Screenshot%202025-06-20%20152717.png)

### Flashcard Section
![Screenshot 2025-06-20 152644](https://github.com/SanjanaDasari26/AI-study-buddy/blob/main/images1/Screenshot%202025-06-20%20152644.png)

### Quiz Section
![Screenshot 2025-06-20 152805](https://github.com/SanjanaDasari26/AI-study-buddy/blob/main/images1/Screenshot%202025-06-20%20152805.png)

### Timer Section
![Screenshot 2025-06-20 152820](https://github.com/SanjanaDasari26/AI-study-buddy/blob/main/images1/Screenshot%202025-06-20%20152820.png)

---

## 🛠️ How to Run

1. Make sure you have Python 3.10 or later installed.  
2. Clone this repository using `git clone https://github.com/yourusername/ai-study-buddy.git` and navigate to the folder using `cd ai-study-buddy`.  
3. Create a virtual environment using `python -m venv venv` and activate it with `venv\Scripts\activate` on Windows or `source venv/bin/activate` on macOS/Linux.  
4. Install dependencies using `pip install flask google-generativeai`.  
5. Open the `app.py` file and replace `YOUR_API_KEY` with your Gemini API key in the line `genai.configure(api_key="YOUR_API_KEY")`.  
6. Run the app using `python app.py` and open `http://localhost:5000` in your browser.  

---

## 🧠 How It Works

- **Chat Mode:** Type a question and receive an AI-generated response powered by Gemini.  
- **Flashcards:** Enter any topic to get 5 Q&A pairs for quick review.  
- **Quiz Mode:** Input a topic and get a 5-question multiple-choice quiz. Tap to reveal correct answers.  
- **Timer:** Track your study time per session and get cumulative statistics.  
- **Theme Toggle:** Use the 🌗 button to switch between light and dark mode anytime.  

---

## 📁 Project Structure

ai-study-buddy/  
├── app.py           → Flask backend logic  
├── index.html       → Frontend layout and UI with Tailwind CSS and JS  
├── README.md        → Documentation  

---

## 🙌 Contribute

Found a bug or want to suggest a feature? Fork the repo, make your changes, and submit a pull request. Contributions are welcome!

---

## 📜 License

MIT License © Dasari Sanjana

---

## 📧 Contact

For questions, reach out to [dasarisanjana260804@gmail.com](mailto:dasarisanjana260804@gmail.com)

---

Thanks for using AI Study Buddy! Let’s study smarter together. 🚀
