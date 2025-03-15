---

This is my custom theme for [Oh My Posh](https://ohmyposh.dev/), designed for a sleek and productive terminal experience. It provides a well-structured prompt with useful information for developers.

## 📥 Installation

### 1️⃣ Download the Theme File
Clone this repository or manually download the theme file:

```sh
wget https://raw.githubusercontent.com/SalehKhatri/oh-my-posh_Theme/main/amro_modified.omp.json -O ~/.amro_modified.omp.json
```

### 2️⃣ Apply the Theme
Run the following command to set the theme temporarily:

```sh
oh-my-posh init bash --config ~/.amro_modified.omp.json | source
```

For permanent use, add this to your shell configuration file:

#### Bash (`~/.bashrc` or `~/.bash_profile`)
```sh
echo 'eval "$(oh-my-posh init bash --config ~/.amro_modified.omp.json)"' >> ~/.bashrc
```

#### Zsh (`~/.zshrc`)
```sh
echo 'eval "$(oh-my-posh init zsh --config ~/.amro_modified.omp.json)"' >> ~/.zshrc
```

#### PowerShell (`$PROFILE`)
```powershell
oh-my-posh init pwsh --config "~/.amro_modified.omp.json" | Out-String | Invoke-Expression
```

Restart your terminal to apply the changes.

## 🔧 Customization
Feel free to edit the theme file to match your personal preferences. The theme file is in JSON format and can be modified using any text editor.

To preview changes live:
```sh
oh-my-posh debug --config ~/.amro_modified.omp.json
```

## 📸 Preview
![image](https://github.com/user-attachments/assets/05dd66c9-4ac3-4c58-9895-4339a727fb2d)  

## 🚀 Enjoy!
If you like this theme, feel free to share it or suggest improvements!

---

💡 **Tip:** Make sure you have the required fonts installed for proper icons and glyphs. You can install a [Nerd Font](https://www.nerdfonts.com/) for the best experience.

---
