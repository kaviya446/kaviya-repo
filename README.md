Installation Guide for Node.js and Git
Windows Installation
Installing Node.js on Windows
Visit Node.js official website
Download the LTS (Long Term Support) version
Run the downloaded .msi installer
Follow the installation wizard:
Click "Next"
Accept the license terms
Choose the installation location (default is recommended)
Click "Next" on all default options
Click "Install"
Verify installation by opening Command Prompt and typing:
node --version
npm --version
Installing Git on Windows
Visit Git for Windows
Download the latest version for Windows
Run the installer:
Click "Next"
Choose installation location (default is recommended)
Select components (default is recommended)
Choose default editor (e.g., Visual Studio Code if installed)
Choose default branch name (main is recommended)
Choose PATH environment (recommended: "Git from the command line and also from 3rd-party software")
Choose HTTPS transport backend (OpenSSL recommended)
Choose line ending conversions (recommended: "Checkout Windows-style, commit Unix-style")
Choose terminal emulator (Windows' default console window recommended)
Choose default 'git pull' behavior (recommended: "Fast-forward or merge")
Choose credential helper (Git Credential Manager recommended)
Enable file system caching (recommended)
Click "Install"
Verify installation by opening Command Prompt and typing:
git --version
macOS Installation
Installing Node.js on macOS
Option 1: Using Homebrew (Recommended)

Open Terminal
Install Homebrew if not installed:
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install Node.js:
brew install node
Verify installation:
node --version
npm --version
Option 2: Direct Download

Visit Node.js official website
Download the macOS LTS installer (.pkg file)
Run the installer package
Follow the installation wizard
Verify installation using the commands above
Installing Git on macOS
Option 1: Using Homebrew (Recommended)

Open Terminal
Install Git:
brew install git
Verify installation:
git --version
Option 2: Using Xcode Command Line Tools

Open Terminal
Run:
xcode-select --install
Follow the installation prompt
Verify installation:
git --version
Post-Installation Setup
Configure Git (Both Windows and macOS)
Set your username:
git config --global user.name "Your Name"
Set your email:
git config --global user.email "your.email@example.com"
Verify Everything is Working
For Node.js:
node --version  # Should show v18.x.x or higher
npm --version   # Should show 9.x.x or higher
For Git:
git --version   # Should show 2.x.x or higher
Troubleshooting
Windows
If commands aren't recognized, restart your Command Prompt
If still not working, check if PATH environment variables were set correctly
For Git issues, try running Git Bash instead of Command Prompt
macOS
If Homebrew commands fail, try:
brew doctor
If permissions issues occur:
sudo chown -R $(whoami) $(brew --prefix)/*
For command not found errors, restart your Terminal
Updating
Windows
Node.js: Download and run the new installer
Git: Download and run the new installer
macOS
Using Homebrew:

brew update
brew upgrade node
brew upgrade git
webify
webify
# kaviya-repo
