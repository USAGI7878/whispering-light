# Whispering Light in a Clear Winter

A beautiful, interactive Christmas e-card with elegant Dior-inspired design, gentle snowfall, and relaxing lofi music. Perfect for sharing warm holiday wishes with colleagues and friends.

## Features

- **Elegant Envelope Design**: Dior-inspired luxury Christmas theme with golden accents
- **Gentle Snowfall**: Realistic slow-falling snow animation across the entire page
- **Interactive Particles**: Golden particle effects that activate when opening the card
- **Lofi Christmas Music**: Relaxing background music with toggle control
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Accessible**: Keyboard navigation and screen reader friendly
- **Smooth Animations**: Beautiful transitions and micro-interactions

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/christmas-card.git
Open the card

Simply open index.html in your web browser

Or host it on any web server

Experience the magic

Click the golden seal to open the envelope

Enjoy the animated particles and message

Click the music button for relaxing lofi Christmas tunes

How to Use
For Personal Use
Customize the message in the card-content section

Modify the sender name and year

Share the link with your colleagues and friends

For Developers
The project uses vanilla HTML, CSS, and JavaScript with:

Canvas API for particle effects

Web Audio API for music

CSS animations and gradients

Modern responsive design principles

Customization
Changing the Message
Edit the text inside the .message div in index.html:

html
<div class="message">
  <em>"Your custom quote here"</em><br><br>
  Your holiday message...<br><br>
  — Your Name · 2025
</div>
Modifying Colors
Update the CSS variables in the :root selector:

css
:root {
  --dior-gold: #c4a86f;
  --dior-deep-red: #8b0000;
  --dior-burgundy: #722f37;
  /* Add your custom colors */
}
Adjusting Snowfall
Modify the snow parameters in the JavaScript:

javascript
const SNOWFLAKE_COUNT = 120; // Number of snowflakes
vy: Math.random() * 0.3 + 0.1, // Falling speed
Browser Support
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

Note: Web Audio API requires user interaction to start playback (browser security policy)

Project Structure
text
christmas-card/
├── index.html          # Main HTML file
├── README.md          # Project documentation
└── assets/            # (Optional) Additional assets
    ├── images/
    └── fonts/
Music Features
Lofi Christmas beats with gentle drums and bells

Toggle control - play/pause with visual feedback

Web Audio API for smooth, synthesized music

Looping playback for continuous ambiance

Perfect For
Company holiday greetings

Personal Christmas wishes

Virtual holiday parties

Social media sharing

Email newsletters

Contributing
Feel free to fork this project and create your own customized Christmas cards! Some ideas:

Add different color themes

Create custom animations

Add more interactive elements

Implement different music styles

License
This project is open source and available under the MIT License.

Credits
Created with care for the 2025 holiday season. Perfect for spreading warmth and kindness during the Christmas period.

If you like this project, please give it a star on GitHub.

May your holidays be filled with warmth and light.
