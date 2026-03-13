Typing Effect ⌨️
A smooth animated typing effect built with vanilla HTML, CSS, and JavaScript. Words cycle through automatically with a blinking cursor — no libraries, no frameworks.
🔗 Live Demo
👉 https://rainbow-valkyrie-3ad0ec.netlify.app
Features

Pure vanilla JS — zero dependencies
Smooth character-by-character typing animation
Auto word cycling with loop
Blinking cursor via CSS animation

Tech Stack

HTML5
CSS3 (keyframe animations, flexbox)
JavaScript (DOM manipulation, recursion + setTimeout)

How It Works
The typeEffect() function runs recursively using setTimeout. It slices one character at a time from the current word and updates the DOM. Once the full word is typed, it pauses 1 second then moves to the next word. A CSS ::before pseudo-element creates the blinking cursor effect.
Project Structure
typing-effect/
├── index.html
├── style.css
└── script.js
