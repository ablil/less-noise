# less-noise
My custom zsh theme, its simple, minimal and has the necessary informations.

# Installation
1. Download the theme
```shell
curl https://raw.githubusercontent.com/ablil/less-noise/main/less-noise.zsh-theme -o $HOME/.oh-my-zsh/custom/themes/less-noise.z
sh-theme
```
2. set to `$HOME/.zshrc`
```shell
ZSH_THEME="less-noise"
```
3. Reload the shell (or logout)
```shell
source $HOME/.zshrc
```

# Features
The layout is basic, it is as follows:
```shell
~/repositories/less-noise main *													12:47:58 AM
```
You need to know you're **working directory**, you current **git branch** if you are inside a git repository, you current **git status** (you modified some files, uncommited files ....) and lastly the **current time**.

The following icons identify the files on your current git directory:

| Icon | Description     |
|------|-----------------|
| ✈    | Added files     |
| ✭    | Modifed files   |
| ✗    | Deleted files   |
| ➦    | Renamed files   |
| ✂    | Unmerged files  |
| ✱    | Untracked files |

