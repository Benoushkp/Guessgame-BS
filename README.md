FUTURISTIC GUESS GAME BY BS STUDIOS

A web-based number guessing game with retro-futuristic visuals and particle effects


🚀 Features
Dynamic Feedback: Hints like "Very High 🔥" or "Super Near! ⚡"

Score Tracking: Start with 10 points, lose 1 per wrong guess

Visual Effects:

GSAP animations for smooth transitions

Particles.js background

Glowing UI elements with CSS filters

Responsive Design: Works on all screen sizes

Auto-Restart: Play again without reloading

🛠️ Tech Stack
Core: HTML5, CSS3, JavaScript

Libraries:

Tailwind CSS - Utility-first styling

GSAP - Smooth animations

Particles.js - Interactive background

🎯 How to Play
Guess numbers between 1-100

Receive temperature-based hints (🔥 = too high, ❄️ = too low)

Find the number before your score reaches 0!

⚠️ Critical Issue Resolved
Problem:
404 Error for Background Image.png on Netlify due to:

File actually contained mathematical equations (text) instead of image data

Space in filename (Background-image.png) caused path resolution issues

Case sensitivity mismatch in deployment

Solution:

Replaced text file with actual PNG image

Renamed to background-image.png (lowercase + hyphen)

Verified file structure matches deployment:

Clone repo:

bash
Copy
git clone https://Benoushkp/Guessgame-BS.git
Install dependencies (included via CDN):

No installation needed!

Open index.html in browser

📖 Lessons Learned
File Validation: Always verify actual file content matches extension

Web-Safe Naming: Use hyphens instead of spaces (e.g., background-image.png)

Case Sensitivity: Maintain consistent lowercase naming

Path Checking: Double-check relative paths in deployment environments

🙌 Acknowledgements
Particle effects by Particles.js

Animations powered by GSAP

UI styling with Tailwind CSS

🔗 Live Demo: Netlify Deployment Link (http://bsguessgame.netlify.app/)
📄 License: MIT © 2025 [Benoush Valentine F]
