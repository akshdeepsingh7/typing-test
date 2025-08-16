# Advanced Typing Speed Test

A modern, feature-rich typing speed test application built with vanilla HTML, CSS, and JavaScript. Test your typing speed and accuracy with customizable settings and beautiful themes.

## ✨ Features

### Core Functionality
- **Real-time WPM calculation** - See your words per minute as you type
- **Live accuracy tracking** - Monitor your typing accuracy in real-time
- **Smooth cursor animation** - Visual cursor that follows your typing position
- **Auto-scrolling text** - Text automatically scrolls as you progress through lines
- **Backspace support** - Correct your mistakes with full backspace functionality

### Customization Options
- **Multiple time limits**: 15s, 30s, 60s (default), 120s
- **Test modes**: 
  - **Words mode** - Type randomly shuffled common English words
  - **Custom mode** - Paste your own text to practice with
- **Theme selection**: 
  - Dark (default monospace theme)
  - Dracula (popular purple/pink color scheme)
  - Aether (elegant purple/brown aesthetic)

### User Experience
- **Focus management** - Click anywhere to start typing
- **Blur effect** - Text blurs when unfocused with helpful prompt
- **Responsive design** - Works seamlessly on desktop and mobile devices
- **Keyboard shortcuts** - Any keypress focuses the typing area
- **Visual feedback** - Clear indication of correct/incorrect characters

## 🚀 Getting Started

### Quick Start
1. Download the HTML file
2. Open it in any modern web browser
3. Click on the text area or press any key to start
4. Begin typing to start the timer automatically

### No Installation Required
This is a standalone HTML file with no dependencies. Simply open it in your browser and start typing!

## 🎯 How to Use

1. **Select your preferences**:
   - Choose a time limit (15s, 30s, 60s, or 120s)
   - Pick a test mode (Words or Custom)
   - Select your preferred theme

2. **For Custom Text Mode**:
   - Switch to "Custom" mode
   - Paste your text in the textarea that appears
   - Start typing in the main area

3. **Start typing**:
   - Click on the text area or press any key to focus
   - The timer starts automatically when you begin typing
   - Type the highlighted text as accurately as possible

4. **View your results**:
   - After time expires or completing the text, see your detailed stats
   - Click "Try Again" to restart with the same settings

## 📊 Statistics Explained

### During the Test
- **Timer**: Countdown showing remaining time
- **WPM**: Current words per minute (updates in real-time)

### Results Screen
- **Net WPM**: Words per minute after accounting for errors
- **Raw WPM**: Total characters typed divided by 5, regardless of accuracy
- **Accuracy**: Percentage of correctly typed characters
- **Characters**: Breakdown of correct vs incorrect character counts
- **Test Config**: Summary of your test settings

## 🎨 Themes

### Dark Theme
Clean, minimal design with high contrast for comfortable typing

### Dracula Theme
Popular color scheme featuring:
- Deep purple background (#282a36)
- Bright pink accents (#ff79c6)
- Green for correct text (#50fa7b)
- Red for errors (#ff5555)

### Aether Theme
Elegant aesthetic with:
- Dark navy background (#101015)
- Warm beige text (#E2B792)
- Purple highlights (#9370DB)

## ⚡ Technical Details

### Performance Features
- **Smooth animations** - CSS transitions for cursor movement and text scrolling
- **Efficient rendering** - Minimal DOM manipulation for smooth typing experience
- **Memory management** - Clean timer intervals and event handling

### Browser Compatibility
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design adapts to different screen sizes
- No external dependencies required

### Code Structure
- **Modular JavaScript** - Well-organized code with clear separation of concerns
- **CSS custom properties** - Easy theme customization through CSS variables
- **Semantic HTML** - Accessible and well-structured markup

## 🔧 Customization

### Adding New Themes
Add a new theme by defining CSS custom properties:

```css
[data-theme='mytheme'] {
    --background-color: #your-bg-color;
    --text-color: #your-text-color;
    --primary-color: #your-accent-color;
    /* ... other properties */
}
```

### Modifying Word Lists
The `COMMON_WORDS` array contains ~400 common English words. You can:
- Add more words to increase variety
- Replace with words from other languages
- Adjust the word selection algorithm

### Customizing Time Options
Add new time limits by modifying the time settings buttons in the HTML and updating the event listener logic.

## 🎮 Keyboard Shortcuts

- **Any key**: Focus typing area and begin
- **Backspace**: Correct the previous character
- **Click**: Focus typing area

## 💡 Tips for Better Scores

1. **Focus on accuracy first** - Higher accuracy leads to better net WPM
2. **Use proper finger placement** - Touch typing technique improves speed
3. **Stay relaxed** - Tension slows down typing
4. **Practice regularly** - Consistency is key to improvement
5. **Use custom text** - Practice with content relevant to your needs

## 🛠️ Development

### Local Development
No build process required! Simply edit the HTML file and refresh your browser.

### File Structure
```
typing-test.html
├── HTML structure
├── CSS styles (embedded)
└── JavaScript logic (embedded)
```

### Contributing
Feel free to fork and modify this project. Some ideas for enhancements:
- Additional themes
- More language options
- Statistics history
- Multiplayer functionality
- Sound effects
- Progress tracking

## 📱 Mobile Support

The application is fully responsive and works on mobile devices with:
- Touch-friendly interface
- Adaptive font sizes
- Mobile-optimized layout
- Virtual keyboard support

## 🔒 Privacy

- **No data collection** - Everything runs locally in your browser
- **No internet required** - Works completely offline
- **No cookies** - Only localStorage for theme preference
- **No tracking** - Your typing data never leaves your device

---

**Happy typing! 🎯**

*Test your skills, improve your speed, and track your progress with this modern typing speed test.*
