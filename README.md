# 🎯 Guess It Right!

A fun and interactive **Number Guessing Game** built using HTML, Tailwind CSS, and Vanilla JavaScript.

🔗 Live Demo:  
https://vercel.com/bhavya-kuretis-projects/number_guessing

---

## ✨ Features

- Random number generation (0–100)
- Customizable number of chances
- Smart hints (Super Close, Close, High, Low, Too High, Too Low)
- Dynamic scoring system
- Background music toggle
- Responsive design
- Interactive modals (Welcome, How to Play, Score Card, Chances)

---

## 🧠 How It Works

1. The game generates a random number between 0 and 100.
2. Player enters a guess.
3. The game provides hints based on proximity.
4. Score depends on how quickly the number is guessed.
5. The game ends when:
   - The number is guessed correctly.
   - All chances are used.

---

## 🎯 Scoring Formula

(maxGuesses - wrongGuesses) × (100 / maxGuesses)


The fewer guesses you use, the higher your score.

---

## 🏗️ Tech Stack

- HTML5
- Tailwind CSS
- JavaScript (ES6)
- Font Awesome
- Vercel (Deployment)

