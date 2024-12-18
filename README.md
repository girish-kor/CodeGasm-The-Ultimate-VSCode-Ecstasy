# CodeGasm: The Ultimate VSCode Ecstasy 🚀

Welcome to **CodeGasm** – the ultimate VSCode configuration that will revolutionize your coding experience.

## 🌟 Quick Start

### Prerequisites
- Visual Studio Code (v1.50+)
- Git
- Node.js

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/CodeGasm.git
cd CodeGasm
```

2. Install Required Extensions
```powershell
code --install-extension be5invis.vscode-custom-css \
     --install-extension bradlc.vscode-tailwindcss \
     --install-extension brandonkirbyson.vscode-animations \
     --install-extension dbaeumer.vscode-eslint \
     --install-extension esbenp.prettier-vscode \
     --install-extension formulahendry.auto-close-tag \
     --install-extension formulahendry.auto-rename-tag \
     --install-extension formulahendry.code-runner \
     --install-extension ionutvmi.path-autocomplete \
     --install-extension johnpapa.angular2 \
     --install-extension miguelsolorio.symbols \
     --install-extension ms-vscode.theme-materialkit \
     --install-extension ritwickdey.liveserver \
     --install-extension usernamehw.errorlens \
     --install-extension wscats.html-snippets
```

## 🔧 Configuration Files

### 1. settings.json
Replace your VSCode `settings.json` with the configuration in this repository:

- Windows Path: `%APPDATA%\Code\User\settings.json`
- Mac/Linux Path: `~/.config/Code/User/settings.json`

### 2. keybindings.json
Custom keyboard shortcuts are included in `keybindings.json`

### 3. snippets
Custom code snippets for various languages located in `snippets/`

## 🚀 Key Features

### Formatting & Linting
- Prettier auto-formatting on save
- ESLint for code quality
- Auto-tag closing and renaming

### Development Enhancements
- Tailwind CSS IntelliSense
- Live Server for instant previews
- Code Runner for multi-language execution
- Angular 2 support
- Path autocomplete

### Visual Improvements
- MaterialKit theme
- Cursor animations
- Enhanced error display with ErrorLens
- Custom CSS modifications

## 📦 Included Snippets

### HTML5 Boilerplate
```json
"html5": {
  "prefix": "html5",
  "body": [
    "<!DOCTYPE html>",
    "<html lang=\"en\">",
    "<head>",
    "    <meta charset=\"UTF-8\">",
    "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
    "    <title>${1:Document}</title>",
    "</head>",
    "<body>",
    "    ${2}",
    "</body>",
    "</html>"
  ]
}
```

## 🛠 Customization

Feel free to fork and modify the configuration to suit your personal coding style. Create pull requests to share your improvements!

## 🔒 License

MIT License - Fully open-source and free to use.

## 🙌 Contributions

Contributions are welcome! Please read the contribution guidelines before submitting a pull request.

## 📞 Support

If you encounter any issues, please file an issue on the GitHub repository.

---

**Happy Coding! 💻✨**
