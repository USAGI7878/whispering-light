# Whispering Light in a Clear Winter

A beautiful, interactive Christmas e-card with elegant design, gentle snowfall, and relaxing lofi music. Perfect for sharing warm holiday wishes with colleagues and friends.

## Features

- **Elegant Envelope Design**: Luxury Christmas theme with golden accents
- **Gentle Snowfall**: Realistic slow-falling snow animation across the entire page
- **Interactive Particles**: Golden particle effects triggered upon opening the card
- **Lofi Christmas Music**: Relaxing background music with toggle control
- **Responsive Design**: Works well on desktop, tablet, and mobile devices
- **Accessible**: Keyboard navigation and screen reader friendly
- **Smooth Animations**: Beautiful transitions and micro-interactions

---

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/your-username/christmas-card.git
```

### 2. Open the card
- Open **index.html** in your browser  
- Or host it on any web server  

### 3. Experience the magic
- Click the golden seal to open the envelope  
- Enjoy particles and greeting message  
- Click the music button for relaxing Christmas lofi  

---

## How to Use

### For Personal Use
- Edit the greeting message in the **card-content** section  
- Update sender name and year  
- Share with colleagues and friends  

### For Developers
Technologies used:
- Canvas API for particle effects  
- Web Audio API for music  
- CSS animations & gradients  
- Fully responsive layout  

---

## Customization

### Change the Message
```html
<div class="message">
  <em>"Your custom quote here"</em><br><br>
  Your holiday message...<br><br>
  — Your Name · 2025
</div>
```

### Modify Theme Colors
```css
:root {
  --gold: #c4a86f;
  --deep-red: #8b0000;
  --burgundy: #722f37;
  --cream: #f5f1e6;
  --dark-blue: #021E47;
  --light-gold: #e6d7b8;
}
```

### Adjust Snowfall Settings
```javascript
const SNOWFLAKE_COUNT = 120;     // number of snowflakes
vy: Math.random() * 0.3 + 0.1;   // falling speed
```

---

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

> Web Audio API requires user interaction before music playback.

---

## Project Structure
```
christmas-card/
├── index.html
├── README.md
└── assets/
    ├── images/
    └── fonts/
```

---

## Music Features

- Lofi Christmas beats with gentle bells  
- Play/pause toggle with animation  
- Smooth Web Audio API handling  
- Looping playback for ambiance  

---

## Perfect For

- Corporate holiday greetings  
- Personal Christmas wishes  
- Virtual celebrations  
- Social media sharing  
- Email newsletters  

---

## Contributing

You’re welcome to fork and customize:
- New color themes  
- Additional animations  
- More interactive elements  
- Different music tracks  

---

## License

Released under the **MIT License**.

---

## Credits

Created with care for the 2025 holiday season.  
If you enjoy this project, please consider giving it a ⭐ on GitHub.

**May your holidays be filled with warmth and light.**

---

### Major Updates
- Removed all “Dior-inspired” / “Dior” wording  
- Updated CSS variables (removed dior- prefix)  
- Kept technical details  
- More neutral & professional tone  
