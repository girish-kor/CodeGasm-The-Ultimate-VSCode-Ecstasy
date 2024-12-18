# CodeGasm: The Ultimate VSCode Ecstasy 🚀🔥

Welcome to **CodeGasm** – the VSCode configuration that'll make your coding sessions feel like a digital romance novel. Prepare for an IDE so smooth, it'll make other text editors blush! 😏💻

## 🚀 Preview Your Coding Pleasure

![CodeGasm VSCode Setup](https://raw.githubusercontent.com/girish-kor/CodeGasm-The-Ultimate-VSCode-Ecstasy/refs/heads/main/assets/CodeGasm.png)
*Warning: May cause spontaneous coding euphoria* 🤯

## 🛠 Features That'll Make Your Keyboard Tingle

- **Optimized Editor Settings** (Because bland is banned) 🎨
- **Prettier Integration** (Goodbye, code mess!)
- **Tailwind CSS Support** (CSS on steroids) 💪
- **Smooth Animations** (Code like you're in a Matrix movie) 🕶️
- **Integrated Code Runner** (Instant gratification) ⚡
- **Framework Support** (We love ALL your frameworks) ❤️
- **Live Server Functionality** (Refresh? Never heard of her) 🔄

## 🔧 Prerequisites (AKA Coding Foreplay)

- Visual Studio Code (v1.50+) - Your digital playground
- Git - Because commitment issues are for relationships, not code
- NodeJS - The runtime that makes everything possible

## 📦 Installation (Let's Get Intimate)

### 1. Clone the Repository (First Base)

```bash
git clone https://github.com/yourusername/CodeGasm.git
cd CodeGasm
# *winks* Let the magic begin
```

### 2. Install VSCode Extensions (Protection Optional, but Recommended)

```powershell
# Core Extensions (Because we're not savages)
code --install-extension esbenp.prettier-vscode       # Prettify me, baby
code --install-extension dbaeumer.vscode-eslint      # Lint me harder
code --install-extension bradlc.vscode-tailwindcss   # Tailwind me senseless
code --install-extension formulahendry.code-runner   # Run me quick
code --install-extension ritwickdey.liveserver       # Live and unfiltered
code --install-extension usernamehw.errorlens        # Errors? We expose them all
code --install-extension miguelsolorio.symbols       # Symbolic relationship
code --install-extension brandonkirbyson.vscode-animations  # Smooth moves only

# Framework Extensions (We don't discriminate) 
code --install-extension johnpapa.angular2           # Angular? More like An-gular
code --install-extension wscats.html-snippets        # HTML snippets = code foreplay

# Productivity Extensions (Work smarter, not harder)
code --install-extension formulahendry.auto-close-tag    # Closure is important
code --install-extension formulahendry.auto-rename-tag   # Identity crisis? Solved!
code --install-extension ionutvmi.path-autocomplete      # Guide me, senpai
```

### 3. Apply VSCode Settings (The Intimate Moment)

- **Windows**: `%APPDATA%\Code\User\settings.json` (Your secret diary)
- **Mac/Linux**: `~/.config/Code/User\settings.json` (No judgement here)

Copy the contents of `settings.json` - it's like a love letter to your IDE.

## 💡 Key Configuration Highlights (The Foreplay)

### 1. Prettier Formatting
- Auto-format on save (Because messy is never sexy)
- Supports multiple file types (We're not monogamous)
- Consistent code styling (OCD? We got you) 💅

### 2. Tailwind CSS Integration
- Intelligent auto-completion (Mind reading, basically)
- Real-time class validation (No fake classes here)
- Emmet support (Speed dating for developers)

### 3. ESLint Configuration
- Automatic linting (Cleaning up your mess)
- Catch potential errors (We're watching you)
- Enforce coding standards (Discipline is hot)

### 4. Code Runner
- Execute code snippets instantly (Quickest draw in the West)
- Support for multiple languages (Polyglot? Oh yeah!)
- Integrated terminal execution (No switching required)

### 5. Live Server
- Instant browser preview (Impatience is a virtue)
- Auto-reload on changes (Commitment issues? Not here)
- Works with HTML/CSS/JS (The holy trinity)

## 🎨 Theming (Dress to Impress)

- **Theme**: Material Night Eighties (Retro meets modern)
- **Icon Pack**: Symbols (Because looks matter)
- **Error Visualization**: ErrorLens (Transparency is key)

## 📝 Custom Snippets (Quick and Dirty)

Example HTML5 Snippet (A quickie template):

```json
"html5": {
  "prefix": "html5",
  "body": [
    "<!DOCTYPE html>",
    "<html lang=\"en\"> <!-- Internationalization, darling 😘 -->",
    "<head>",
    "    <meta charset=\"UTF-8\">",
    "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
    "    <title>${1:Document of Desires}</title>",
    "</head>",
    "<body>",
    "    ${2:<!-- Insert your wildest dreams here -->}",
    "</body>",
    "</html>"
  ],
  "description": "HTML5: Your Gateway to Digital Seduction"
}
```

## ⚠️ Troubleshooting (When Things Get Complicated)

- Ensure VSCode is updated (Stay fresh)
- Check extension compatibility (No toxic relationships)
- Refer to individual extension docs (Communication is key)

## 🤝 Contributing (Let's Collaborate)

1. Fork the repository (Take what you want)
2. Create your feature branch (Make it your own)
3. Commit your changes (Seal the deal)
4. Push to the branch (No holding back)
5. Create a Pull Request (The ultimate proposal)

## 📄 License

MIT License - Free as your coding spirit 🕊️

## 🌟 Final Thoughts (Pillow Talk)

CodeGasm transforms your VSCode into a productivity powerhouse that'll make other developers swoon. Code hard, play harder! 💥👨‍💻

---

**Happy Coding, You Beautiful Debugging Machines! 🚀💖**

---

# Bonus: Nuclear Options 💥

## Remove All VS Code Extensions

```powershell
# Scorched Earth Extension Removal
$extensions = code --list-extensions
foreach ($extension in $extensions) {
    code --uninstall-extension $extension
}
```

## Nuke All settings.json

```powershell
# Settings Annihilation Protocol
$settingsPaths = @(
    "$env:APPDATA\Code\User\settings.json",
    "$env:HOME\AppData\Roaming\Code\User\settings.json",
    "$env:HOME/.config/Code/User/settings.json"
)

foreach ($settingsPath in $settingsPaths) {
    if (Test-Path $settingsPath) {
        Remove-Item $settingsPath -Force
        Write-Host "Obliterated settings.json from: $settingsPath"
    }
}
```

**Caution: These scripts have no mercy. Use with the confidence of a developer who knows no fear!** 🔥👀
