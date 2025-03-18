# 🚀 Make Your Mac Terminal Better with Homebrew, Oh My Zsh & Powerlevel10k  

## Description  
This repository provides a step-by-step guide to enhancing your macOS terminal with **Homebrew**, **Oh My Zsh**, and **Powerlevel10k**.  
It includes instructions to install essential tools, customize the shell, and add useful plugins like **Autosuggestions** and **Syntax Highlighting** for an optimized and modern command-line experience.  

## Features  
- ✅ **Install and configure Homebrew**  
- ✅ **Set up Oh My Zsh and Powerlevel10k theme**  
- ✅ **Add Zsh plugins for better productivity**  
- ✅ **Customize and improve your terminal experience**  

---

## 🚀 How To Make Your Boring Mac Terminal So Much Better  
This guide walks you through enhancing your **macOS terminal** with **Homebrew**, **Oh My Zsh**, and the **Powerlevel10k** theme for a **modern, efficient, and stylish** command-line experience.  

---

## 📌 Prerequisites  
Ensure you have:  
✔️ **A macOS system**  
✔️ **Terminal access**  

---

## ⚡ Installation Steps  

### 1️⃣ Install Homebrew  
Homebrew is a package manager for macOS that makes software installation easy.  

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

2️⃣ Set Up Homebrew in Your Shell

echo >> ~/.zprofile
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

3️⃣ Verify Homebrew Installation

brew --version  # Check if Homebrew is installed

4️⃣ Install Git (If Not Installed)

git --version  # Check if Git is installed
brew install git  # Install Git using Homebrew

5️⃣ Install Oh My Zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

6️⃣ Install Powerlevel10k Theme

git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

7️⃣ Configure the Zsh Theme

Edit the .zshrc file:

vim ~/.zshrc

Find the line that sets the theme and change it to:

ZSH_THEME="powerlevel10k/powerlevel10k"

Save and exit (Press ESC, then type :wq and press Enter).

8️⃣ Apply the Changes

source ~/.zshrc



⸻

🔹 Install Zsh Plugins

✅ Autosuggestions Plugin

This plugin helps you by suggesting commands as you type.

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

✅ Syntax Highlighting Plugin

This plugin adds color coding to your terminal commands.

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

✅ Enable Plugins in .zshrc

Open .zshrc again:

vim ~/.zshrc

Find the line that starts with plugins=() and update it to:

plugins=(git zsh-autosuggestions zsh-syntax-highlighting web-search)

Save and exit (ESC, then :wq).

🔟 Reload Zsh

source ~/.zshrc



⸻

🎨 Customize Powerlevel10k

After installation, restart your terminal, and Powerlevel10k will start a configuration wizard.
Follow the on-screen instructions to customize your terminal’s look.

⸻

📌 Additional Commands

✅ Remove Oh My Zsh

uninstall_oh_my_zsh

❌ Remove Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/uninstall.sh)"



⸻

🤝 Contributing

Feel free to fork this repository and submit pull requests if you want to improve it!

⸻

📜 License

This project is licensed under the MIT License.

⸻

🔗 Connect with Me

📧 Email: mhdd24.rafi@gmail.com
💻 GitHub: Mhdd-24

⸻

🚀 Push Updated README to GitHub

Once you’ve fixed the Markdown formatting in your README.md, commit and push the changes:

git add README.md
git commit -m "Added structured README for macOS terminal customization"
git push origin main



⸻

🎉 Enjoy Your New Terminal Setup!

Now your terminal looks 🔥 better, faster, and more efficient! 🚀

---