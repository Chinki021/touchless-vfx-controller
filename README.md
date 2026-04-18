# 🖐️ Touchless VFX Controller  

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-blue)
![Status](https://img.shields.io/badge/Status-Active-success)

A real-time hand gesture-based visual effects system built using computer vision and browser-based rendering.

---

## 🎥 Demo  

Watch how hand gestures control fire, ice, and lightning effects in real-time.

https://github.com/user-attachments/assets/9f6a6374-c943-4d59-a9c1-60e875c6a61d

---

## 🔍 Overview  

This project uses hand tracking and gesture recognition to create interactive visual effects directly in the browser using your webcam.  

Users can control different visual powers like fire, ice, lightning, and color effects — all without touching the screen.

---

## ⚙️ Tech Stack  

- HTML5 Canvas  
- JavaScript (Vanilla JS)  
- MediaPipe Hands  
- Web Camera API  

---

## ✨ Features  

- 🎥 Real-time hand tracking  
- ⚡ Multiple gesture-based effects:
  - 🔥 Fire & Ice mode  
  - ⚡ Lightning mode  
  - 🔴🔵 Dual color (Red & Blue) mode  
- 🤏 Pinch detection for drawing effects  
- 🖐️ Open hand detection for power activation  
- 🎨 Particle-based visual system  
- 🔥 Optimized rendering for smoother performance  

---

## 🎮 Controls  

| Key | Mode                      |
|-----|---------------------------|
| 1   | Fire (Left) & Ice (Right) |
| 2   | Lightning                 |
| 3   | Red & Blue                |

---

## 🧠 How It Works  

- Uses MediaPipe to track **21 hand landmarks in real-time**  
- Detects gestures like:
  - 🤏 Pinch → enables drawing  
  - 🖐️ Open hand → activates effects  
- Maps hand coordinates to the canvas  
- Generates effects using a **particle system + gradients**  
- Updates visuals continuously using webcam input  

---

## ⚠️ Notes  

- Works best in **Google Chrome**  
- Requires webcam access  
- Performance may vary based on system capability  

---

## 💡 Future Improvements  

- Advanced multi-hand gesture recognition  
- Custom gesture training  
- UI overlay for controls  
- Mobile compatibility  
- Performance optimization (FPS tuning)  

---

## 🙋‍♀️ Author  

**CHINKI RAJ**  
GitHub: https://github.com/Chinki021  


