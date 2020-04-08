# Roberto's OSX terminal config #
![Plugins Demo](demo/demo.gif)   

This configuration is **heavily** based on [this](https://medium.com/@Clovis_app/configuration-of-a-beautiful-efficient-terminal-and-prompt-on-osx-in-7-minutes-827c29391961)
Medium configuration walkthrough.     

### Components   
* [iTerm2](https://www.iterm2.com/)  
* [oh-my-zsh](https://ohmyz.sh/)  
* [ranger](https://github.com/ranger/ranger)     
* [ksh](https://en.wikipedia.org/wiki/KornShell)

## Installation ##
1. Install iTerm2   
`brew cask install iterm2`   

2. Configure iTerm2
  1. In Preferences - Profile - Colors set color preset to solarized dark   
  2. Install [Meslo Powerline Font](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20M%20Regular%20for%20Powerline.ttf). 
Click view Raw to download the font. (In OSX when you open it it should add it to your Font Book).    
  3. In Preferences - Profile - Text set font to Meslo LG Power Font
  4. In Preferences - Profile - Window enable Background image, select a background you would like and set blending to your hearts desire. 
I use [this image](https://mocah.org/uploads/posts/4544095-steps-forest-green-foliage-pine-trees-trees-dirt-road.jpg)      

3. Install ksh    
  `brew install ksh`   
4. Install oh-my-zsh    
  `brew install zsh zsh-completions`     
  `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`   
4. Replace .zshrc   
  `rm ~/.zshrc`   
  `rm -rf ~/.oh-my-zhrc`   
  `ln ~/config/zshrc ~/.zshrc`   
5. If you want ranger to preview images look at instructions [here](https://github.com/ranger/ranger/wiki/Image-Previews) (Please note the image rendering is very slow may not be worth the trouble).

___

[Roberto](https://robertoodogherty.github.io/) 03/2020


