# 💖 Happy Valentine's Day - Animated Love Message

A romantic, animated Valentine's Day greeting card featuring a beautifully drawn heart animation and floating hearts effect. This project displays "I Love You Tisha" with elegant animations powered by GSAP.

![Valentine's Day Animation](https://img.shields.io/badge/Valentine's%20Day-2024-ff69b4?style=for-the-badge&logo=heart&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)

## ✨ Features

- 🎭 **Animated Heart Drawing**: Beautiful SVG heart that draws itself using CSS stroke animation
- 💫 **Floating Hearts**: Multiple small hearts with randomized animations
- 🌊 **Text Animation**: Elegant letter-by-letter animation with stagger effects
- 💖 **Romantic Typography**: Custom font styling with heart symbol
- 📱 **Responsive Design**: Works beautifully on all screen sizes
- 🎨 **Smooth Animations**: Powered by GSAP (GreenSock Animation Platform)

## 🚀 Demo

Open `index.html` in your browser to see the romantic animation in action!

### Animation Sequence:
1. **Heart Drawing** (0.5s delay): Main heart draws itself over 3 seconds
2. **Text Reveal** (3s delay): "I Love You Tisha" appears letter by letter
3. **Floating Hearts** (3.6s delay): Small hearts animate into position with wave motion

## 🛠️ Technologies Used

- **HTML5**: Semantic structure with SVG graphics
- **CSS3**: Modern styling with animations and Google Fonts
- **JavaScript (ES6)**: Dynamic heart generation and animation control
- **GSAP**: Professional-grade animation library
- **SVG**: Scalable vector graphics for crisp heart shapes
- **Google Fonts**: Amatic SC font for romantic typography

## 📁 Project Structure

```
Happy-Valentine-Day/
│
├── index.html          # Main HTML file with SVG heart and text
├── style.css           # CSS styling and animations
├── script.js           # JavaScript animations using GSAP
└── README.md           # Project documentation
```

## 🎨 Customization

### Changing the Message
To personalize the message, edit the spans in `index.html`:

```html
<div class="greeting">
  <div>
    <span class="s">Y</span>
    <span class="s">o</span>
    <span class="s">u</span>
    <span class="s">r</span>
    <!-- Add your custom message here -->
  </div>
</div>
```

### Adjusting Animation Timing
Modify timing in `script.js`:

```javascript
// Text animation delay
delay: '3',  // Change this value

// Small hearts animation delay  
delay: '3.6',  // Change this value
```

### Styling Customization
Update colors and fonts in `style.css`:

```css
/* Main heart stroke color */
stroke: #d63b3b;

/* Background color */
background: #ecebeb;

/* Text font */
font-family: "Amatic SC", cursive;
```

## 🌟 Animation Details

### Heart Drawing Animation
- Uses CSS `stroke-dasharray` and `stroke-dashoffset` for drawing effect
- 3-second duration with linear timing
- Starts after 0.5-second delay

### Text Animation
- GSAP timeline with staggered letter animations
- Scale and Y-axis transformations
- Power1.inOut easing for smooth effect

### Floating Hearts
- 13 dynamically generated heart elements
- Random positioning with CSS nth-child selectors
- Sine wave motion using GSAP modifiers
- Randomized scale and rotation values

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Happy-Valentine-Day.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Happy-Valentine-Day
   ```

3. **Open in browser**:
   - Simply open `index.html` in your favorite web browser
   - Or serve with a local server for best results

4. **Customize**:
   - Edit the message in `index.html`
   - Adjust colors and timing in CSS/JS files
   - Make it your own! 💕

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 💡 Inspiration

This project was created as a romantic gesture to express love through code. Perfect for:
- Valentine's Day surprises
- Anniversary celebrations
- Romantic proposals
- Learning web animations
- Impressing your loved ones with code! 

## 🤝 Contributing

Feel free to fork this project and make it even more beautiful! Some ideas:
- Add more animation effects
- Include sound effects
- Create different themes
- Add particle effects
- Make it interactive

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 💌 Message

> "Love is not just a feeling, it's an art. And sometimes, the most beautiful art is written in code." 

Made with ❤️ for Tisha

---

**Happy Valentine's Day!** 🌹💕
