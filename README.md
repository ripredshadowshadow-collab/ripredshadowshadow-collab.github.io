# Interactive Grid Game

A fun and interactive HTML5 web application featuring multiple mini-games built with vanilla JavaScript and Tailwind CSS.

## 🎮 Games Included

- **Grid Avoidance Game (Practice Mode)**: Navigate through a grid-based racing game while avoiding obstacles. Use W/S keys or touch buttons to move and step forward.
- **CPS Tester**: Test your clicks-per-second performance with adjustable test durations (1s, 5s, 10s).
- **Reaction Time Tester**: Measure your reaction time with visual feedback and performance ranking.

## ✨ Features

- 🎬 **Dynamic Video Backgrounds**: Separate background videos for menu and practice modes with sound controls
- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- 👆 **Touch Controls**: Mobile-optimized touch buttons for the Grid Game (W, GO!, S buttons)
- 🎨 **Modern UI**: Built with Tailwind CSS for a clean, professional look
- 🚗 **Multiple Cars**: Select from 3 different cars (AE86, GTR, BRZ) with unique specifications
- 📊 **Score Tracking**: Real-time performance metrics and statistics

## 🎯 How to Play

### Grid Avoidance Game
1. Select your car from the carousel
2. View car specifications and details
3. Click "Start Grid Race" to begin
4. **Desktop Controls**:
   - W key: Move up one lane + step forward
   - S key: Move down one lane + step forward
   - Click/Touch on track: Step forward without changing lane
5. **Mobile Controls**: 
   - W Button (Blue): Move up + step forward
   - GO! Button (Green): Step forward without changing lane
   - S Button (Red): Move down + step forward
6. Avoid obstacles and earn points for each grid you safely pass

### CPS Tester
1. Select test duration (1s, 5s, or 10s)
2. Click the button and start clicking as fast as possible
3. View your CPS score and equivalent speed in KMPH

### Reaction Time Tester
1. Wait for the screen to turn green
2. Click/tap as quickly as possible when you see the color change
3. Track your best time and average across multiple runs

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Tailwind CSS (CDN)
- **Backend**: Python 3.11 HTTP Server
- **JavaScript**: Vanilla JS (no frameworks)
- **Hosting**: Replit (easily deployable)

## 📦 Installation & Setup

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/interactive-grid-game.git
cd interactive-grid-game
```

2. Install Python (if not already installed):
```bash
python3 --version
```

3. Run the development server:
```bash
python3 server.py
```

4. Open your browser and navigate to:
```
http://localhost:5000
```

### On Replit

1. Fork or import this repository into Replit
2. Click "Run" to start the development server
3. The app will open in the web preview

## 📁 Project Structure

```
.
├── index.html              # Main HTML file with embedded CSS and JavaScript
├── server.py              # Python HTTP server for serving static files
├── replit.md              # Replit project documentation
├── README.md              # This file
├── .gitignore             # Git ignore configuration
├── css/                   # CSS files (if separated)
│   ├── mobile.css
│   └── mobile-ui-overlay.css
└── js/                    # JavaScript files (if separated)
    ├── mobile-touch.js
    └── mobile-integration.js
```

## 🎬 Video Assets

The application uses video backgrounds for enhanced visual appeal:
- `background-video.mp4`: Menu background
- `practice-video.mp4`: Practice mode background

**Note**: Video files are not included in this repository due to size constraints. To add them:
1. Place your video files in the project root directory
2. Ensure they're named `background-video.mp4` and `practice-video.mp4`
3. Or upload them as GitHub Releases

## 🎵 Sound Control

Both video backgrounds include sound toggle buttons in the top-right corner for muting/unmuting audio.

## 🚀 Deployment

### Deploy to Replit
1. Import this repository into Replit
2. Click the "Publish" button to get a live URL
3. Share the URL with others

### Deploy to GitHub Pages (Static Version)
Due to the Python server requirement, this app is best served from:
- Replit
- Heroku
- Any server that supports Python

For a pure static deployment, remove `server.py` and host the `index.html` directly on GitHub Pages.

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for improvements.

## 📧 Support

For issues, questions, or suggestions, please open an issue on GitHub.

---

**Made with ❤️ using HTML5, CSS, and JavaScript**
