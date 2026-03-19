#  Study Platform for Gamers

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font%20Awesome-6.0.0-528DD7?style=flat&logo=fontawesome&logoColor=white)

A gamified study platform that transforms learning into an RPG-like experience. Complete quests, earn XP, compete on leaderboards, and play educational games—all in one immersive interface.

<img width="1888" height="1868" alt="image" src="https://github.com/user-attachments/assets/06eda49f-6932-4136-97e8-46826bf282bf" />

##  Features

###  **Study Loot System**
- **Flashcard Decks**: Track progress across subjects (Math, Chemistry, Programming)
- **Daily Quests**: Complete study tasks to earn XP and rewards
- **Progress Bars**: Visual representation of your learning journey

###  **Gaming Hub**
- **Quiz Arena**: Multiplayer knowledge battles
- **Spell Vocab**: Co-op word learning game
- **Code Rush**: Solo/PvP coding challenges
- **Quick Play**: One-click game launching

###  **Social Features**
- **Live Leaderboard**: Compete with other scholars
- **Study Sessions**: Join scheduled group games
- **Party System**: Form study groups for bonus XP

###  **Gamification Elements**
- Study XP & Coin currencies
- Level progression (Scholar Level 8+)
- Achievement badges
- Streak tracking

##  Quick Start

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor for modifications (optional)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/study-gaming-platform.git
cd study-gaming-platform
```

2. **Open locally**
- Simply open `index.html` in your browser
- Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with live-server)
npx live-server
```

3. **Start learning!**
- Navigate to `http://localhost:8000`
- Begin your study quests immediately

## 🛠️ Customization

### Modifying Study Content
Edit the flashcard decks in the HTML:
```html
<div class="card">
  <div class="card-icon"><i class="fa-solid fa-calculator"></i></div>
  <h4>Your Subject</h4>
  <p>your description</p>
  <div class="badge-progress"><div class="badge-fill" style="width: XX%;"></div></div>
</div>
```

### Adding New Games
Copy the game card template:
```html
<div class="game-card">
  <div class="game-cover"><i class="fa-solid fa-your-icon"></i></div>
  <div class="game-info">
    <h3>Game Name</h3>
    <div class="meta"><span>details</span></div>
    <button class="play-btn" onclick="yourFunction()">play</button>
  </div>
</div>
```

### Styling Variables
Key color variables in CSS:
```css
body {
  background: linear-gradient(145deg, #0d0f1a 0%, #1a1e30 100%);
}
.study-zone {
  background: #151e30e0;
  border: 1px solid #3c5280;
}
.gaming-hub {
  background: #111a2ce3;
  border: 1px solid #6a7fae;
}
```

##  Project Structure

```
study-gaming-platform/
│
├── index.html          # Main platform interface
├── README.md           # Documentation
└── assets/            # (optional) Custom assets
    ├── css/
    ├── js/
    └── images/
```

##  Use Cases

- **Individual Learners**: Gamify your personal study routine
- **Study Groups**: Compete and collaborate with friends
- **Classrooms**: Engage students with game-based learning
- **Hackathons**: Quick demo for edtech projects
- **Portfolio**: Showcase gamification design skills

##  Technical Details

### Built With
- **HTML5**: Semantic structure
- **CSS3**: Flexbox/Grid layouts, gradients, animations
- **Vanilla JavaScript**: Interactive elements
- **Font Awesome 6**: Gaming & study icons

### Key Features Implemented
-  Responsive design (mobile-friendly)
-  Interactive quest toggling
-  Glass-morphism UI effects
-  Game-like button states
-  XP progression visualization
-  No external dependencies (except Font Awesome)

##  Contributing

Contributions make the open-source community amazing! Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more flashcard decks
- Create additional mini-games
- Implement local storage for progress
- Add dark/light theme toggle
- Build backend integration
- Create study timer feature

##  License

Distributed under the MIT License. See `LICENSE` for more information.

##  Acknowledgments

- Font Awesome for the incredible icon library
- The gaming community for inspiration
- All scholars who gamify their learning

## Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)

Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)

Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)

LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)

Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
