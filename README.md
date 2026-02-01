# Mac Voice Assistant Bot

An interactive voice-controlled chatbot with wake word detection, animated personality, and Mac application control capabilities.

![Voice Assistant](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-macOS-blue)

## Features

🎤 **Wake Word Detection** - Say "Hey Bot" to activate the assistant  
🤖 **Animated Character** - Expressive bot face with blinking eyes and talking mouth  
🗣️ **Voice Commands** - Full speech recognition and text-to-speech  
💻 **Mac App Control** - Open applications via voice commands  
🎨 **Retro-Futuristic Design** - Cyberpunk aesthetic with bold colors

## Demo

Visit the live demo: [GitHub Pages URL will be here]

## Usage

1. Open the page in Chrome or Edge (Safari has limited speech recognition support)
2. Click "Start Listening" button
3. Allow microphone access when prompted
4. Say "Hey Bot" followed by your command

## Voice Commands

- **"Hey Bot, open Excel"** - Opens Microsoft Excel
- **"Hey Bot, open Safari"** - Opens Safari browser
- **"Hey Bot, open Chrome"** - Opens Google Chrome
- **"Hey Bot, what time is it"** - Tells you the current time
- **"Hey Bot, tell me a joke"** - Tells a programming joke
- **"Hey Bot, hello"** - Greets you back

### Supported Applications

Excel, Word, PowerPoint, Safari, Chrome, Firefox, Notes, Mail, Calendar, Music, Finder, Terminal, Calculator, Messages

## How It Works

The assistant uses the Web Speech API for voice recognition and synthesis. When you say the wake word "Hey Bot", it activates and listens for your command.

**Note on App Control:** Due to browser security restrictions, the bot cannot directly launch Mac applications. Instead, it provides you with the AppleScript command to execute in Terminal.

## Customization

Click the ⚙️ settings button to change the wake word to your preference.

## Technical Stack

- HTML5
- CSS3 (with animations)
- JavaScript (Web Speech API)
- AppleScript (for Mac automation)

## Browser Compatibility

- ✅ Chrome (Recommended)
- ✅ Edge
- ⚠️ Safari (Limited speech recognition)
- ❌ Firefox (No speech recognition support)

## Local Development

Simply open `index.html` in your browser. No build process required!

## Future Enhancements

- [ ] Backend server for direct app launching
- [ ] More complex commands and conversations
- [ ] Memory/context retention
- [ ] Integration with calendar and reminders
- [ ] Custom wake word training

## License

MIT License - feel free to use and modify!

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.
