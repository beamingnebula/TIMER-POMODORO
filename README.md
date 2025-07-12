# Timer By Mehboob

A clean and intuitive timer application built for productivity and time management.

## 🚀 Live Demo

Check out the live application: [Timer App](https://timerbymehboob.netlify.app/)

## ✨ Features

- **Easy-to-use Interface**: Clean and minimalist design for distraction-free timing
- **Fullscreen Clock**: Run the timer in fullscreen mode with auto-hiding controls
- **Multiple Timer Modes**: Support for various timing needs: Work (25 min) and Break (5 min)
- **Keyboard Shortcuts**: Supports keybinds for faster controls
- **Customizable**: Supports 9 different clock fonts and 13 beautiful background options
- **Timer Size Control**: Adjustable timer size (15-35vw on desktop, 20-30vw on mobile)
- **Auto-Repeat**: Automatically restart timer with 3-second cooldown
- **Audio Notifications**: Get alerted when your timer completes
- **Haptic Feedback**: Vibration support for mobile devices
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Persistent Settings**: Your preferences are saved for future sessions
- **Settings Panel**: Tabbed interface for easy customization

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Deployment**: Netlify
- **Design**: Responsive web design principles
- **Storage**: Local Storage for settings persistence

## 📱 Screenshots

<!-- Add screenshots of your app here -->
*Screenshots coming soon...*

[![Watch on YouTube](https://img.youtube.com/vi/xBr5OaRW6Yw/0.jpg)](https://youtube.com/shorts/xBr5OaRW6Yw)

## 🎯 How to Use

### Basic Usage
1. Visit the [live application](https://timerbymehboob.netlify.app/)
2. Set your desired time duration using the slider (1-60 minutes)
3. Click "Start" to begin the timer
4. Use "Pause" to pause/resume the timer
5. Get notified when the timer completes with sound and vibration
6. Reset or set a new timer as needed

### Quick Presets
- **25 min**: Standard Pomodoro work session
- **5 min**: Short break session
- **Custom**: Use the slider for any duration (1-60 minutes)

### Keyboard Shortcuts
- **Space**: Start/Pause timer
- **F**: Toggle fullscreen mode
- **R**: Reset to 25 minutes
- **B**: Set to 5 minutes (break)
- **S**: Toggle settings panel
- **V**: Test vibration (mobile)

### Fullscreen Mode
- Click the "Fullscreen" button or press **F**
- Controls auto-hide after 4 seconds of inactivity
- Move mouse to show controls
- Cursor hides automatically in fullscreen

### Settings Panel
- Click the settings gear icon (top-left) or press **S**
- **Font Tab**: Choose from 9 different fonts and adjust timer size
- **Background Tab**: Select from 13 colors or animated gradient
- **Shortcuts Tab**: View all keyboard shortcuts
- **Info Tab**: App information and Discord community
- **Download Tab**: Download the app for offline use

## 🔧 Local Development

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic knowledge of HTML, CSS, and JavaScript
- Git (for version control)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/beamingnebula/TIMER-POMODORO.git
   ```

2. Navigate to the project directory:
   ```bash
   cd timer-app
   ```

3. Open `index.html` in your preferred web browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js
   npx serve
   
   # Using PHP
   php -S localhost:8000
   ```

4. Open your browser and go to `http://localhost:8000`

### Project Structure

```
timer-app/
├── index.html              # Main application file
├── favicon.ico            # App icon
├── favicon-32x32.png      # 32x32 icon
├── favicon-16x16.png      # 16x16 icon
├── apple-touch-icon.png   # iOS icon
├── site.webmanifest       # PWA manifest
├── timer-end.mp3          # Timer completion sound
└── README.md              # This file
```

### Development Guidelines

#### Code Organization
- **HTML**: Single file structure with embedded CSS and JavaScript
- **CSS**: Organized into logical sections with clear comments
- **JavaScript**: Modular functions with comprehensive documentation

#### Key Features Implementation
- **Timer Logic**: `updateTimerDisplay()`, `startTimer()`, `resetTimer()`
- **Fullscreen**: `toggleFullscreen()`, `showControls()`, `hideAllButtons()`
- **Settings**: `initSettings()`, `updateTimerFontSize()`, `updateRepeatToggle()`
- **Haptic Feedback**: `vibrate()` function with fallback support

#### Local Storage Keys
- `timerFont`: Selected font family
- `timerBackgroundColor`: Background color preference
- `timerFontSize`: Timer size setting
- `timerRepeat`: Auto-repeat setting
- `lastActiveTab`: Last active settings tab

## 🌟 Features in Detail

### Timer Functionality
- **Custom Duration**: 1-60 minute range with slider control
- **Visual Countdown**: Real-time display with customizable fonts
- **Auto-Repeat**: Optional automatic restart with 3-second countdown
- **Reset Capability**: Click timer at 00:00 to reset to previous duration

### User Experience
- **Intuitive Controls**: Clear button layout and responsive design
- **Visual Feedback**: Yellow flash animations for interactions
- **Audio Alerts**: Sound notification when timer completes
- **Haptic Feedback**: Vibration support for mobile devices

### Customization Options
- **Font Selection**: 9 Google Fonts (Lato, Roboto, Givonic, Raleway, Oswald, Quicksand, Poppins, Orbitron, Montserrat)
- **Background Colors**: 13 solid colors plus animated gradient
- **Timer Size**: Adjustable from 15-35vw (desktop) or 20-30vw (mobile)
- **Auto-Repeat**: Toggle automatic timer restart

### Responsive Design
- **Mobile-First**: Optimized for touch interfaces
- **Cross-Platform**: Works on all devices and browsers
- **Safe Areas**: Proper handling of device notches and status bars
- **Dynamic Layout**: Controls adjust position based on timer size

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Getting Started
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/new-feature`
3. Make your changes following the code style
4. Test thoroughly on different devices
5. Commit your changes: `git commit -m 'Add new feature'`
6. Push to the branch: `git push origin feature/new-feature`
7. Submit a pull request

### Development Guidelines
- **Code Style**: Follow existing comment structure and formatting
- **Testing**: Test on desktop, tablet, and mobile devices
- **Documentation**: Add comments for new features
- **Accessibility**: Ensure keyboard navigation and screen reader support

### Areas for Contribution
- **New Fonts**: Add more Google Fonts to the selection
- **Background Options**: Create new color themes or gradients
- **Keyboard Shortcuts**: Add more shortcut combinations
- **Animations**: Enhance visual effects and transitions
- **PWA Features**: Add offline support and app installation
- **Localization**: Add multi-language support
- **Themes**: Create dark/light mode toggle

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Mehboob** for **[Beaming Media](https://beamingmedia.netlify.app/)**
- GitHub: [@beamingnebula](https://github.com/beamingnebula)
- Live App: [Timer App](https://timerbymehboob.netlify.app/)
- [Download App](https://timerbymehboob.netlify.app/downloadpage.html)

## 🙏 Acknowledgments

- Thanks to all users and contributors
- Inspiration from productivity methodologies (Pomodoro Technique)
- Built with modern web technologies
- Google Fonts for typography options
- Inspired from Bigtimer.net (until it got ruined with ads)

## 📞 Support

If you have any questions or run into issues, please:
- Open an issue on GitHub
- Check the existing issues for solutions
- Join our [Discord Server](https://discord.com/invite/CDAmXSaXQF/) for community support

## 🔄 Version History

- **v1.13.0**: Current version with auto-repeat, font customization, and enhanced UX
- **v1.0.0**: Initial release with basic timer functionality

---

⭐ If you found this project helpful, please consider giving it a star on GitHub!
