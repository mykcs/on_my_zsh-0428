# on_my_zsh-0428

ref [macOS 程序员必备：iTerm2 与 oh-my-zsh](www.bilibili.com/video/BV14a4y1F7Ss)

https://ohmyz.sh/

## install

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## issue 01 -fixed

## /.zhsrc文件

从ver0变为ver1

改变一下，加入插件
```shell
plugins=(
    git
    zsh-autosuggestions
    zsh-syntax-highlighting
)
```
