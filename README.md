🖐️ Touchless VFX Controller

A real-time hand gesture-based visual effects engine built using computer vision and browser-based rendering.



🔍 Overview

This project uses hand tracking and gesture recognition to create interactive visual effects directly in the browser using your webcam.
Users can control different visual powers like fire, ice, lightning, and color effects — all without touching the screen.

--

⚙️ Tech Stack

HTML5 Canvas

JavaScript (Vanilla JS)

MediaPipe Hands

Web Camera API

--

✨ Features

🎥 Real-time hand tracking

⚡ Multiple gesture-based effects:

 📌Fire & Ice mode
📌Lightning mode
📌Dual color (Red & Blue) mode

🤏 Pinch detection for drawing effects

🖐️ Open hand detection for power activation

🎨 Particle-based visual system

🔥 Optimized rendering to reduce lag

--

🎮 Controls

| Key | Mode                      |
| --- | ------------------------- |
| 1   | Fire (Left) & Ice (Right) |
| 2   | Lightning                 |
| 3   | Red & Blue                |

--

Key	Mode

1	Fire (Left) & Ice (Right)
2	Lightning
3	Red & Blue

--

🧠 How It Works

Uses landmark detection from MediaPipe to track 21 points on each hand

Detects gestures like:

Open hand → activates power

Pinch → drawing mode

Maps hand coordinates to canvas for real-time rendering

Uses particle systems + gradients for effects
