# 🔴 RedClick — Fast Reaction Browser Game

**RedClick** is a fast and addictive reaction-based browser game built using **HTML, CSS, and vanilla JavaScript**.  
Two red squares appear randomly inside the playground — your goal is to click them as quickly as possible.  
Clicking anywhere outside the targets results in an instant **Game Over**.

---

## 🎮 Demo

👉 **Live Demo:** *[(add your Netlify/test URL here)](https://redclick.netlify.app)*  

---

## ✨ Features

- ⚡ Fast-paced reaction gameplay  
- 🎯 Two independently moving targets  
- 🔊 Sound feedback (Pop.mp3)  
- 📈 Real-time score counter  
- 🔥 Increasing difficulty  
- 📱 Basic mobile responsiveness  
- ♻️ Restart system & Game Over screen  

---

## 🕹️ How It Works

1. Two red squares appear in random positions.
2. Clicking a square increases your score.
3. Each click triggers:
   - score++
   - sound playback
   - random repositioning
   - difficulty check
4. Clicking outside the targets = **Game Over**.
5. At 50 and 100 points, targets shrink for greater challenge.
6. Press **Restart** to play again.

---

## 🧠 Game Logic Summary

### Target Elements
```js
#object
#object2
On every click:
Increase score

Play pop sound

Reposition targets

Check difficulty level

Verify if the click was valid

Difficulty Scaling
Score	Target Size
0–49	25px
50+	20px
100+	15px

🛠️ Technologies Used
HTML5

CSS3

JavaScript (Vanilla)

ALK Sanet Georgian Font

MP3 Audio Playback

📂 Project Structure
arduino
Copy code
redclick/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── game.js
├── mp3/
│   └── Pop.mp3
└── assets/
    └── (optional images/icons)
🚀 How to Run Locally
Option 1 — Open Directly
Open:

diff
Copy code
index.html
in any modern browser.

arduino
Copy code
http://localhost:8000
🔮 Future Improvements

🎵 More sounds & animations

🎮 Difficulty modes (Easy / Normal / Hard)

📱 Complete mobile UI redesign
