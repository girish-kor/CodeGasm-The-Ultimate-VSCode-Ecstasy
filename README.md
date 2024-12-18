# CodeGasm: The Ultimate VSCode Ecstasy

Welcome to **CodeGasm** – the ultimate VSCode configuration that will take your coding experience to the next level. This repository contains my curated VSCode settings, extensions, and customizations designed to make your coding as smooth and pleasurable as possible.

## 🚀 Preview Your Coding Pleasure

![CodeGasm VSCode Setup]((https://raw.githubusercontent.com/girish-kor/CodeGasm-The-Ultimate-VSCode-Ecstasy/refs/heads/main/assets/CodeGasm.png))
*Placeholder for VSCode screen recording*

## 🛠 Features

- **Optimized Editor Settings**
- **Prettier Integration**
- **Tailwind CSS Support**
- **Smooth Animations**
- **Integrated Code Runner**
- **Framework Support**
- **Live Server Functionality**

## 🔧 Prerequisites

- Visual Studio Code (v1.50+)
- Git
- NodeJS

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/CodeGasm.git
cd CodeGasm
```

### 2. Install VSCode Extensions

```powershell
# Core Extensions
code --install-extension esbenp.prettier-vscode
code --install-extension dbaeumer.vscode-eslint
code --install-extension bradlc.vscode-tailwindcss
code --install-extension formulahendry.code-runner
code --install-extension ritwickdey.liveserver
code --install-extension usernamehw.errorlens
code --install-extension miguelsolorio.symbols
code --install-extension brandonkirbyson.vscode-animations

# Framework Extensions
code --install-extension johnpapa.angular2
code --install-extension wscats.html-snippets

# Productivity Extensions
code --install-extension formulahendry.auto-close-tag
code --install-extension formulahendry.auto-rename-tag
code --install-extension ionutvmi.path-autocomplete
```

### 3. Apply VSCode Settings

- **Windows**: `%APPDATA%\Code\User\settings.json`
- **Mac/Linux**: `~/.config/Code/User/settings.json`

Copy the contents of `settings.json` from this repository into your VSCode settings.

## 💡 Key Configuration Highlights

### 1. Prettier Formatting
- Auto-format on save
- Supports multiple file types
- Consistent code styling

### 2. Tailwind CSS Integration
- Intelligent auto-completion
- Real-time class validation
- Emmet support

### 3. ESLint Configuration
- Automatic linting
- Catch potential errors
- Enforce coding standards

### 4. Code Runner
- Execute code snippets instantly
- Support for multiple languages
- Integrated terminal execution

### 5. Live Server
- Instant browser preview
- Auto-reload on changes
- Works with HTML/CSS/JS

## 🎨 Theming

- **Theme**: Material Night Eighties
- **Icon Pack**: Symbols
- **Error Visualization**: ErrorLens

## 📝 Custom Snippets

Example HTML5 Snippet:

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
  ],
  "description": "HTML5 base template"
}
```

## ⚠️ Troubleshooting

- Ensure VSCode is updated
- Check extension compatibility
- Refer to individual extension documentation for specific issues

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

MIT License - Completely free to use and modify

## 🌟 Final Thoughts

CodeGasm transforms your VSCode into a powerhouse of productivity and pleasure. Enjoy your ultimate coding experience!

---

**Happy Coding! 🚀👨‍💻**
