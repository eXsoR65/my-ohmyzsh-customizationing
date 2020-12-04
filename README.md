# My OhMyZsh customizationing

## Install with curl
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## Using my Customized Theme that inclused hostname in the path. 
I custumized robbyrussell.zsh-theme to add hostname in the prompt. The orginal can by found here: https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme

Download mytheme by

`curl -o $ZSH_CUSTOM/themes/mytheme.zsh-theme https://raw.githubusercontent.com/eXsoR65/my-ohmyzsh-customizationing/main/mytheme.zsh-theme`

- `nano ~/.zshrc` and find ZSH_THEME="robbyrussell"
-  Change it to ZSH_THEME="mytheme"

## Enabling Plugins (zsh-autosuggestions & zsh-syntax-highlighting)
 - Download zsh-autosuggestions by
 
 `git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions`
 
 - Download zsh-syntax-highlighting by
 
 `git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting`

 - Modify you .zshrc file to add the plugins example: `nano ~/.zshrc`
 
 - Append `zsh-autosuggestions & zsh-syntax-highlighting` to  plugins() like this `plugins=(git zsh-autosuggestions zsh-syntax-highlighting)`
 
 - Reload your .zshrc to apply changes with `source ~/.zshrc`.

 ### Ref
 - [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
 - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)