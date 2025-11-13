<div align="center">

# 🎴 3D Flip Card

### Interactive Profile Card with Pure CSS 3D Transform

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://github.com/Mehdi-dev-sudo/Flip-card/graphs/commit-activity)

**[View Live Demo →](https://mehdi-dev-sudo.github.io/Flip-card/)**

<img src="https://raw.githubusercontent.com/Mehdi-dev-sudo/Flip-card/main/imgs/bersek.jpg" alt="Card Preview" width="280" style="border-radius: 15px; box-shadow: 0 10px 40px rgba(0,0,0,0.25);">

*Hover to flip & reveal social links*

</div>

---

## ✨ Features

- **Pure CSS 3D** - No JavaScript, just smooth transforms
- **Responsive Design** - Works flawlessly on all devices
- **Animated Gradient** - Dynamic background with modern colors
- **Social Icons** - 6 linked profiles with hover effects
- **Smooth Transitions** - Cubic-bezier timing for natural motion
- **Lightweight** - Under 5KB total size

---

## 🚀 Quick Start
```bash
# Clone the repo
git clone https://github.com/Mehdi-dev-sudo/Flip-card.git

# Open in browser
cd Flip-card && open index.html

That's it! No build process, no dependencies. Just pure web technologies.

---

## 🎨 How It Works

The card uses CSS `transform-style: preserve-3d` and `rotateY()` to create a realistic 3D flip effect:

css
.wrapper:hover > .front-face {
transform: rotateY(-180deg);
}

.wrapper:hover > .back-face {
transform: rotateY(0deg);
}

**Key techniques:**
- `perspective: 1000px` for depth
- `backface-visibility: hidden` to hide reverse sides
- `transition: all 0.5s cubic-bezier()` for smooth animation

---

## 📂 Structure


Flip-card/
├── index.html          # Card structure
├── style.css           # 3D transforms & animations
└── imgs/
└── bersek.jpg      # Profile image

Clean, minimal, and easy to understand.

---

## 🛠️ Tech Stack

<table>
<tr>
<td align="center" width="100">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" />
<br><sub>HTML5</sub>
</td>
<td align="center" width="100">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" />
<br><sub>CSS3</sub>
</td>
<td align="center" width="100">
<img src="https://cdn.worldvectorlogo.com/logos/font-awesome.svg" width="40" height="40" alt="Font Awesome" />
<br><sub>Font Awesome</sub>
</td>
</tr>
</table>

---

## 🎯 Customization

**Change colors:**
css
/* style.css - line 11 */
background: linear-gradient(375deg, #YOUR_COLOR_1, #YOUR_COLOR_2);

**Update image:**
html
<!-- index.html - line 33 -->
<img src="/imgs/YOUR_IMAGE.jpg" alt="Your Name" />

**Edit content:**
html
<!-- index.html - line 24-27 -->
<div class="title">Your Name</div>
<p>Your Description</p>

---

## 📱 Responsive

| Device | Viewport | Card Size |
|--------|----------|-----------|
| Desktop | > 400px | 320×400px |
| Mobile | < 400px | 95vw×70vw |

Automatically adapts to screen size with CSS media queries.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- 🐛 Report bugs
- 💡 Suggest features
- 🔧 Submit pull requests

---

## 📄 License

MIT License - feel free to use this project for personal or commercial purposes.

---

## 👨‍💻 Author

**Mehdi Khorshidi**

[![GitHub](https://img.shields.io/badge/GitHub-Mehdi--dev--sudo-181717?style=flat-square&logo=github)](https://github.com/Mehdi-dev-sudo)
[![Telegram](https://img.shields.io/badge/Telegram-@Mehdi__ds__KH-26A5E4?style=flat-square&logo=telegram)](https://t.me/Mehdi_ds_KH)

---

<div align="center">

**⭐ Star this repo if you find it useful!**

Made with ❤️ and pure CSS

</div>
