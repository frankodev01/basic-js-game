# 🔴 RedClick — Fast Reaction Browser Game  
### *(Built with HTML, CSS, and Vanilla JavaScript)*

## 🎮 Overview
**RedClick** is a simple but addictive reaction-based browser game built entirely with HTML, CSS, and JavaScript.  
Two red squares randomly appear inside a white play area — your goal is to click them as fast as possible.  
If you click anywhere outside the objects, **you lose**.

The game includes sound effects, live score tracking, increasing difficulty, and a restart system.

---

## ✨ Features
- ⚡ **Fast-paced reaction gameplay**
- 🎯 Two targets that move after each click
- 🔊 Pop sound on every hit
- 📈 Live score counter
- 🔥 Difficulty increases as score grows
- 📱 Mobile-friendly layout
- ♻️ Restart button + lose screen

---

## 🕹️ How It Works
1. Click the red squares to earn points.  
2. Each successful click:
   - Increases the score  
   - Plays a sound  
   - Moves the target to a new random position  
3. Clicking outside the objects ends the game.  
4. Press **Restart** to try again.  
5. At **50** and **100** points, objects get smaller → the game becomes harder.

---

## 🧠 Game Logic Summary
Targets:  
- `#object`  
- `#object2`

Each click triggers:
- `score++`
- Play sound effect
- Random reposition
- Difficulty scaling check

**Difficulty:**
- 50 points → objects shrink to **20px**
- 100 points → objects shrink to **15px**

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3** (including media queries)
- **Vanilla JavaScript**
- **ALK Sanet Georgian font**
- **MP3 audio playback**

---

## 📂 Project Structure
