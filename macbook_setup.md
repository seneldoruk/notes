#### Terminal

- https://iterm2.com/downloads.html
- Settings > Profiles > Keys > Key Mappings > Presets > Natural Text Editing

#### System Settings

- Desktop and Dock

  - Magnification: off
  - Automatically hide and show dock

- Keyboard

  - Key repeat rate max, Delay until repeat min
  - Keyboard Shortcuts > Input Sources > Select both

- Trackpad

  - Tracking speed max

- Accessibility
  - Pointer Control > Mouse and Trackpad > Trackapd Options > Three Finger Drag

#### Apps

```bash
#homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

#zsh
brew install zsh

#git
brew install git

#GitHub CLI
brew install gh

#powerlevel10k
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc

#case insensitive autocomplete
echo "set completion-ignore-case On" >> ~/.inputrc
source ~/.inputrc

#AltTab
brew install --cask alt-tab
#Preferences > Controls > Hold > CMD

#Hidden Bar
brew install --cask hiddenbar
#Deselect "Show preferences on launch"

#Monitor Control
brew install MonitorControl
#Select "Start at login", "Sync brightness"
#Deselect "Combine hardware and software dimming"

```
