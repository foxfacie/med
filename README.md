# Websiteox - Sachin Yadav's Portfolio

[Check product](https://websiteox.tech)

A stunning 3D interactive portfolio website showcasing web development and SEO expertise.

## 🌟 Features

- **3D Interactive Cube Navigation** - Rotate through different sections with smooth animations
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Space Theme** - Beautiful starfield, shooting stars, and nebula effects
- **Audio Integration** - Background music with audio visualization
- **GitHub Integration** - Automatic project loading from GitHub API
- **Modern Animations** - Smooth transitions and micro-interactions
- **SEO Optimized** - Built with best practices for search engine visibility

## 🚀 Technologies Used

- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Advanced animations, 3D transforms, and responsive design
- **JavaScript (ES6+)** - Modern JavaScript with classes and async/await
- **Web Audio API** - Audio visualization and sound effects
- **GitHub API** - Dynamic project loading
- **Font Awesome** - Beautiful icons
- **Google Fonts** - Typography optimization

## 📱 Mobile Experience

- **Touch Gestures** - Swipe navigation for mobile devices
- **Haptic Feedback** - Tactile response on supported devices
- **Optimized Performance** - Reduced animations for better mobile performance
- **Responsive Layout** - Adaptive design for all screen sizes

## 🎵 Audio Features

- **Background Music** - Ambient space-themed music
- **Audio Visualization** - Real-time frequency analysis
- **Sound Effects** - Keyboard typing sounds and transitions
- **Volume Control** - Easy audio management

## 🎨 Design Highlights

- **3D Cube Navigation** - Unique interactive navigation system
- **Space Theme** - Immersive cosmic environment
- **Smooth Animations** - 60fps animations with hardware acceleration
- **Color Scheme** - Professional purple and blue gradient theme
- **Typography** - Modern, readable fonts with proper hierarchy

## 🛠️ Technical Architecture

The project is built with a modular architecture:

- **`AudioManager`** - Handles all audio functionality
- **`TypingAnimation`** - Manages the typing effect on load
- **`CubeController`** - Controls 3D cube navigation
- **`MobileSlider`** - Mobile-specific navigation
- **`AudioVisualizer`** - Real-time audio visualization
- **`StarfieldManager`** - Space particle effects
- **`GitHubProjectsManager`** - GitHub API integration and project display
- **`SafariWarningManager`** - Browser compatibility handling

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/Webdevyadav/websiteox.git
cd websiteox
```

2. Open `index.html` in your browser or serve it with a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` in your browser

## 🔧 Configuration

### GitHub Integration
Update the GitHub username in `script.js`:
```javascript
class GitHubProjectsManager {
    constructor() {
        this.username = 'Webdevyadav'; // Your GitHub username
        // ...
    }
}
```

### Audio Settings
Modify audio settings in `script.js`:
```javascript
const CONFIG = {
    words: ['transform', 'ideas', 'into', 'websiteox'],
    typeSpeed: 120,
    deleteSpeed: 60,
    // ...
};
```

### Customization
- **Colors**: Update CSS variables in `styles.css`
- **Content**: Modify HTML content in `index.html`
- **Animations**: Adjust timing in CSS and JavaScript
- **Projects**: Update project data or GitHub integration

## 🌐 Browser Support

- **Chrome** - Full support with all features
- **Firefox** - Full support with all features
- **Safari** - Full support (with warning for some features)
- **Edge** - Full support with all features
- **Mobile Browsers** - Optimized for iOS Safari and Chrome Mobile

## 📊 Performance

- **Lighthouse Score**: 95+ across all metrics
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🔒 Privacy & Security

- **No Tracking** - No analytics or tracking scripts
- **Local Storage** - Minimal local storage usage
- **HTTPS Ready** - Secure by design
- **No External Dependencies** - Self-contained except for fonts and icons

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 About the Developer

**Sachin Yadav** is a passionate web developer and SEO specialist from Delhi, India. With expertise in creating responsive websites, SEO optimization, and android app development, he helps businesses establish a strong online presence.

### Contact Information
- **Email**: webdevsachinyadav@gmail.com
- **LinkedIn**: [webdevsachin](https://www.linkedin.com/in/webdevsachin/)
- **GitHub**: [Webdevyadav](https://github.com/Webdevyadav)
- **Twitter**: [webdevsachin](https://x.com/webdevsachin)
- **Instagram**: [devsachinyadav](https://www.instagram.com/devsachinyadav/)

### Services Offered
- Web Development
- SEO Optimization
- Android App Development
- WordPress Development
- UI/UX Design
- Web Hosting & Maintenance

---

*Built with ❤️ and lots of ☕ by Sachin Yadav (Websiteox)* 