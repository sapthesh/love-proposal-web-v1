# 💖 Interactive Web Proposal: The Crimson Pulse 💖

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)
<a href="https://hits.sh/github.com/sapthesh/love-proposal-web-v1/"><img alt="Hits" src="https://hits.sh/github.com/sapthesh/love-proposal-web-v1.svg?view=today-total&style=for-the-badge&color=fe7d37"/></a>

A beautifully crafted, interactive, and multi-step web experience designed to pop the big question. Built with HTML5 Canvas, Vanilla JavaScript, and GSAP for fluid, cinematic animations. 

Instead of a simple static page, this project guides the user through a gamified, emotional journey before revealing the final proposal. 

---

## 📑 Table of Contents
* [✨ The Experience](#-the-experience)
* [🌟 Key Features](#-key-features)
* [🚀 Tech Stack](#-tech-stack)
* [💻 Running Locally](#-running-locally)
* [🛠️ Detailed Customization Guide](#️-detailed-customization-guide)
* [🌐 Deployment](#-deployment)

---

## ✨ The Experience

The proposal is broken down into five distinct, interactive phases:

1. **The Hook (Catch the Hearts):** An interactive mini-game where the user must catch 3 fast-moving, glowing golden hearts floating among interactive crimson particles.
2. **The Letter:** A frosted-glass UI card elegantly reveals a personalized, long-form romantic message.
3. **Fill My Heart:** A CSS-drawn glowing heart that grows and intensifies with every tap, culminating in a visual explosion on the 5th tap.
4. **The Big Question:** The final proposal card with dodging "No" button mechanics (a playful trap) and a massive "Yes" button.
5. **The Cinematic Finale:** Upon clicking "Yes", the text drops from the sky, triggers a screen shake, explodes into 250+ interactive particles, and elegantly reveals the sender and receiver's names.

---

## 🌟 Key Features

* **Zero Build Tools:** No Webpack, Node.js, or NPM required. Just open the HTML file.
* **Custom Particle Engine:** A lightweight 2D canvas engine handling hundreds of interactive, physics-based hearts.
* **Glassmorphism UI:** Modern, responsive styling using CSS `backdrop-filter` for a sleek, frosted-glass aesthetic.
* **Mobile Responsive:** Works perfectly on desktops, tablets, and smartphones.
* **Playful Mechanics:** Features classic proposal tropes, like a "No" button that playfully dodges the user's cursor.

---

## 🚀 Tech Stack

* **HTML5 / CSS3:** Uses modern CSS variables for easy theming.
* **Vanilla JavaScript:** Powers the core logic, game states, and canvas rendering.
* **[GSAP (GreenSock)](https://greensock.com/gsap/):** Professional-grade animation library used for the timeline pacing, UI reveals, and cinematic effects. Loaded effortlessly via CDN.

---

## 💻 Running Locally

You do not need any servers or special environments to view or edit this project.

1. Clone the repository or download the ZIP file.
2. Navigate to the project folder.
3. Open `index.html` directly in any modern web browser (Chrome, Safari, Edge, Firefox).
4. Refresh the page after making any edits in your code editor to see changes instantly.

---

## 🛠️ Detailed Customization Guide

You only need to edit a single file (`index.html`) to make this entirely your own.

### 1. Update the Names
Scroll down to the `<script>` section in `index.html` and look for the configuration block at the very top of the JavaScript. This controls the final cinematic reveal.

```javascript
// =======================================================
// 💌 EDIT YOUR NAMES HERE 💌
// =======================================================
const RECEIVER_NAME = "Ju"; // The person receiving it
const SENDER_NAME = "Sapthesh";   // The person sending it
// =======================================================
```

### 2. Personalize the Story
Search the HTML file for the following text blocks and replace them with your own story:
* **The Long Message:** Look for `<div id="long-message"` and edit the `<p>` tag inside to reflect your unique journey.
* **The Question:** Look for `<div id="proposal-card"` and edit the `<h1>` text to ask the question in your own words.

### 3. Change the Theme Colors (Advanced)
If you want to move away from the "Crimson" theme, you can easily change the core colors. Go to the `<style>` section at the top of the file and locate the `:root` variables:

```css
:root {
    --primary-red: #ff003c;  /* Main accent color */
    --glow-red: #ff3366;     /* Used for shadows and glows */
    --dark-red: #2a0008;     /* Background gradient center */
    --gold: #ffd700;         /* Task 1 heart color */
    --text-light: #ffffff;
}
```

---

## 🌐 Deployment 

To share this with your partner, you need to host it online. The easiest, free methods are:

### Method A: GitHub Pages (Recommended)
1. Push your code to a public GitHub repository.
2. Go to your repository **Settings**.
3. Select **Pages** on the left sidebar.
4. Under "Build and deployment", set the source to **Deploy from a branch**.
5. Select your `main` or `master` branch and click **Save**. 
6. In a few minutes, your site will be live at `https://yourusername.github.io/your-repo-name`.

### Method B: Netlify Drop
Drag and drop the folder containing your `index.html` file directly into [Netlify Drop](https://app.netlify.com/drop) for an instant, free live link.

---
*Crafted and coded with ❤️ by Sapthesh V*
