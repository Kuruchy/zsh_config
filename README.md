# zsh_config
This is a repository to put the Zsh configuration files and preferences for the different OS I use.

## 1.- MacOS

Terminal: iTerm2  
Font: SourceCodePro+Powerline+Awesome Regular  
Color Scheme: Solarized Dark

### Instalation
In iTerm2 in `Preferences/Profiles/General` uncheck `Login shell` and check `Command`, adding `/usr/local/bin/zsh`.

I use Sublime as my external text editor, so I will need to create an alias for the zsh. I add it to the `.zshrc` config file.  
`alias subl="/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl"`

To setup Sublime:
- Go to [https://packagecontrol.io/installation](https://packagecontrol.io/installation) and copy the code inside the box labeled as Sublime Text 3.
- In Sublime, open the console `View > Show Console` and paste the code that you just copied on it. Press enter to execute it.
- Press CTRL+SHIFT+P and search for `Package Control: Install Package`
- I install the following packages:
	- SublimeLinter
	- SublimeLinter-eslint
	- SublimeLinter-contrib-stylelint
	- EditorConfig

## 2.- Windows

The solution for Windows is to use the new Window Terminal and the Linux Subsystem.

- Ubuntu 20.04 LTS (Microsoft Store)
- Windows Terminal (Microsoft Store)
- Move `settings.json` to Windows Terminal
- Install ZSH
- Change bash -> `chsh -s /bin/zsh`
- Install OhMyZsh -> `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- Install Poerlevel10k


## Links

Repo: [Windows Terminal](https://github.com/microsoft/terminal)  
Repo: [oh-my-zsh for Zsh](https://github.com/robbyrussell/oh-my-zsh)  
Repo: [powerlevel10k for Zsh](https://github.com/romkatv/powerlevel10k)

## Meta

Bruno Retolaza  
[https://github.com/Kuruchy](https://github.com/Kuruchy/)
