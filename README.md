# QuizGenie 🧞‍♂️

**QuizGenie** is a sleek and fun AI-powered quiz generator built with React. You enter any topic, and QuizGenie magically generates a multiple-choice quiz for you on the fly — complete with points, answer checking, a progress bar, and score tracking.

## Features

- 🔮 Generate 15 unique questions using AI (DeepSeek via Together.ai)
- 🎯 Multiple difficulty levels with a point system
- ✅ Instant answer validation (correct/wrong feedback)
- 🌈 Light and Dark mode toggle
- 📊 Score display and high score saving
- 🎉 Confetti animation on quiz completion
- ⏱️ Timer and progress tracking
- 💅 Smooth animations and responsive design

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/quizgenie.git
cd quizgenie
```
2. Install dependencies
bash
Copy
Edit
npm install
3. Run the app
bash
Copy
Edit
npm run dev
4. Setup .env
You'll need to provide your Together.ai API key for the quiz generation to work.

ini
Copy
Edit
VITE_TOGETHER_API_KEY=your_api_key_here
How It Works
The app sends your topic to an AI API with a prompt requesting 15 well-formatted quiz questions.

Each question includes 4 options, a correct answer index, a difficulty level, and a unique ID.

The quiz logic handles question display, answer checking, score calculation, and UI animations.

Tech Stack
⚛️ React

💅 CSS Grid + Flexbox + Custom Properties

🧠 Gemeni API

## About the Creator

Just a curious mind with a laptop and a love for building cool stuff.  
QuizGenie started as a late-night idea and turned into a fun little project mixing AI, design, and interactivity.  
Hope it makes learning feel a bit more magical ✨
