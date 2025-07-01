## 🎯 Project Title
#### Quiz React Project
A dynamic quiz app built with React — displays questions, tracks scores, and offers a smooth interactive experience.

## 🚀 Live Demo
(Add a link if hosted, e.g. on Netlify, Vercel, or GitHub Pages.)

## 💡 Features
- Multiple-choice quiz with dynamic question rendering

- Score calculation and final result display

- Option to restart the quiz

- Clean, responsive interface

- Easy-to-extend question bank

## 📁 Project Structure
```
quiz-react-project/
├── public/           # Static assets (index.html, favicon, etc.)
└── src/
    ├── components/   # React components (Quiz, QuestionCard, Result, etc.)
    ├── data/         # quizData.js – static question data
    ├── App.js        # Main app wrapper
    ├── index.js      # React mounting point
    └── styles.css    # App styling
```
## 🔧 Installation & Setup

### 1. Clone the repo
git clone https://github.com/Devyani030/Quiz_ReactProject.git  

cd Quiz_ReactProject

### 2. Install dependencies
`npm install`

### 3. Start development server
`npm run dev`

Open http://localhost:3000 in your browser.

## 🛠 How It Works
- Quiz Data
Stored in `src/data/quizData.js` : each question has text, options, and the correct answer.

- Quiz Component
Renders current question, tracks user choice, updates score, progresses through questions.

- Score & Results
At the end, shows total score and percentage. Offers a “Restart Quiz” button to reset state.

- Styling
Simple, responsive CSS contained in `styles.css`.

## 🧩 Customization
- Add/edit questions: Modify `quizData.js` to include new quizzes.

- Adjust scoring: Change scoring logic in the `Quiz` component.

- Styling tweaks: Customize in `styles.css` or integrate Tailwind, Bootstrap, etc.

## 📈 Further Enhancements
| Feature            | Description                                           |
|--------------------|-------------------------------------------------------|
| Timer              | Add a countdown timer per question                   |
| Difficulty Levels  | Categorize questions into Easy, Medium, Hard         |
| API Integration    | Fetch questions from an external trivia API          |
| Scoreboard         | Save scores using local storage or backend           |
| Responsive Design  | Improve UI for tablets and phones using media queries|

## ScreenShot

![Quiz App Screenshot](.src/assets/Screenshot.png)