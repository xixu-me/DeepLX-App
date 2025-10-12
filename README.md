# DeepLX App

A modern, free web-based translation app powered by the DeepLX API. This app provides a clean, responsive interface for translating text between 30+ languages with features like auto-detection, translation history, and RTL (Right-to-Left) language support.

## 🌟 Features

- **Multi-language Support**: Translate between 30+ languages with automatic language detection
- **Auto-translation**: Automatically translates text as you type (with customizable delay)
- **Translation History**: Keeps track of your translation history with local storage
- **Language Swapping**: Quick swap between source and target languages
- **Copy to Clipboard**: One-click copying of translation results
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **RTL Language Support**: Proper support for right-to-left languages
- **Dark Theme**: Modern dark UI design for comfortable usage
- **Keyboard Shortcuts**:
  - `Ctrl+Enter`: Manual translation
  - `Esc`: Close panels
- **Customizable Settings**:
  - Custom API endpoint configuration
  - Adjustable auto-translate delay
  - Toggle auto-translate on/off

## 🚀 Live Demo

Visit the live app at: [https://deeplx.xi-xu.me](https://deeplx.xi-xu.me)

## 📋 Prerequisites

- A modern web browser with JavaScript enabled
- Internet connection for API calls
- DeepLX API endpoint (default provided)

## 🛠️ Installation

### Option 1: Direct Usage

Simply open `index.html` in your web browser. The app will work with the default API endpoint.

### Option 2: Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/xixu-me/DeepLX-App.git
   cd DeepLX-App
   ```

2. Open `index.html` in your preferred web browser or serve it using a local web server:

   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Navigate to `http://localhost:8000` in your browser.

## 🔧 Configuration

### API Endpoint

The app uses a default DeepLX API endpoint, but you can configure your own:

1. Click the **Settings** button (⚙️)
2. Enter your custom API endpoint URL
3. The setting will be saved automatically in your browser's local storage

### Auto-translate Settings

- **Delay**: Adjust the delay (100-5000ms) before auto-translation starts
- **Toggle**: Enable or disable auto-translation feature

## 🎨 Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Custom styles with animations and responsive design
- **JavaScript (ES6+)**: Modern JavaScript for app functionality
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Lucide Icons**: Beautiful, customizable SVG icons
- **DeepLX API**: Translation service backend

## 🔌 API Integration

The app integrates with the DeepLX API, which is a free alternative to DeepL's official API. The default endpoint is pre-configured, but you can use your own DeepLX instance.

### API Request Format

```javascript
{
  "text": "Hello, world!",
  "source_lang": "EN",
  "target_lang": "ES"
}
```

### API Response Format

```javascript
{
  "code": 200,
  "data": "¡Hola, mundo!",
  "source_lang": "EN",
  "target_lang": "ES"
}
```

## 🌐 Supported Languages

The app supports translation between the following languages:

- Auto-detect, English, Chinese
- Spanish, French, German, Italian, Portuguese, Russian
- Japanese, Korean, Arabic, Dutch, Polish, Turkish
- Swedish, Danish, Norwegian, Finnish, Greek, Czech
- Hungarian, Romanian, Bulgarian, Croatian, Slovak
- Slovenian, Estonian, Latvian, Lithuanian, Ukrainian
- And more...

## 📱 Mobile Support

The app is fully responsive and includes:

- Touch-friendly interface
- Mobile-optimized layouts
- Apple Touch Icon support
- Progressive Web App (PWA) capabilities
- Mobile web app meta tags

## 🔒 Privacy & Security

- **No Data Collection**: All translations are processed through the API without storing personal data
- **Local Storage Only**: Settings and history are stored locally in your browser
- **HTTPS Ready**: Designed to work with secure HTTPS endpoints
- **No Registration Required**: Use the app immediately without creating accounts

## 📄 License

This repository is licensed under the GPL-3.0 license - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [DeepLX](https://github.com/xixu-me/DeepLX) - The translation API backend
- [Tailwind CSS](https://tailwindcss.com/) - For the beautiful UI framework
- [Lucide Icons](https://lucide.dev/) - For the clean, modern icons

---

**Made with ❤️ by [Xi Xu](https://xi-xu.me)**
