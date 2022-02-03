# My Setting Terminal Dotfiles  
*NB (still update until I bored or I found way to get environment easy and better).

## Result
![Terminal](/images/terminal.png "Terminal")

## Workspace  
- Linux (Linux Mint XFCE / Ubuntu Based)  
- VS Code (Coding)

## Ingredients  
- Tilix [link](https://gnunn1.github.io/tilix-web/)  
- zsh [link](https://www.zsh.org/)  
- Oh-My-Zsh [link](https://ohmyz.sh/)  
- Powerlevel10k -> Oh-My-Zsh Themes [link](https://github.com/romkatv/powerlevel10k)

## Tutorial  
### 1. Install Terminal Emulator (Tilix)
- Install Tilix  
```sudo apt-get install tilix```  
### 2. Install Unix Shell (ZSH)
- Install  
```sudo apt install zsh```
- Make zsh default for your terminal  
```chsh -s $(which zsh)```
- Check output zsh  
```echo $SHELL``` or ```echo $0```
- Check output zsh version  
```$SHELL --version```
### 3. Install Oh-My-Zsh
- Install  
```sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```
### 4. Install Powerlevel10k
- Install recommended font  
Tutorial [link](https://github.com/romkatv/powerlevel10k#meslo-nerd-font-patched-for-powerlevel10k)
- Install powerlevel10k  
```git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k```
- Restart zsh  
```exec zsh```
- Type ```p10k configure``` for configuration  
### 5. Plugin (Oh-My-Zsh)
- git [link](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git)  
- zsh-autosuggestion [link](https://github.com/zsh-users/zsh-syntax-highlighting)  
- zsh-syntax-highlighting [link](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)  
- zsh-completions [link](https://github.com/zsh-users/zsh-completions)  
- dirhistory [link](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/dirhistory)  
- copydir [link](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/copydir)  
- sudo [link](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/sudo)  
- vscode [link](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/vscode)  
### 6. Copy dotfiles
- vscode  
copy settings.json to ```/home/{your username OS}/.config/Code/User```  
- terminal  
copy all to ```/home/{your username OS}```
### Notes
- Change default terminal [link](https://itsfoss.com/change-default-terminal-ubuntu/)  
- Change default open in terminal linux mint [link](https://www.technipages.com/linux-mint-default-applications)  
- If font cant use on vs code, install it on your OS. **Don't just copy in fonts folder**