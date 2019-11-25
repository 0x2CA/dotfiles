# dotfiles
使用stow进行管理我的配置。

# 启动界面 安装theme
```
# yay -S plymouth-theme-arch-charge
# vim /etc/mkinitcpio.conf	// HOOKS="base udev plymouth [...] "
# plymouth-set-default-theme -R arch-charge
# vim /boot/loader/entries/arch.conf	// options [...] quiet splash
```

# 安装 fish
```
yay -S fish
```

# 安装 xorg 服务 
```
yay -S xorg xorg-xinit
```

# 安装 i3-gaps
```
yay -S i3-gaps
```

# 安装 终端模拟器 xterm-termite
```
yay -S tremite
```

# 安装 bar
```
yay -S polybar
```

# 安装 网络显示
```
yay -S net-tools
```

# 安装 cpu显示
```
yay -S sysstat
```

# 安装 音乐
```
yay -S  mpd ncmpcpp
```

# 安装 声音
```
yay -S alsa-utils
```
# 安装 视频
```
yay -S mpv
```

# 安装 中文字体
```
yay  -S noto-fonts-cjk
```

# 安装 图标字体 Awesome 
```
yay -S ttf-font-awesome
yay -S ttf-material-icons-git
```
# 文件系统支持 ntfs exfat
```
yay -S ntfs-3g
yay -S exfat-utils
```
# 安装 浏览器 firefox
```
yay -S  firefox
```

# 安装 命令行文件管理器 ranger
```
yay -S ranger
```

# 安装 截图工具 shutter scrot  粘贴到剪贴板 xclip
```
yay -S  scrot xclip
```

# 安装 通知软件 dunst
```
yay -S dunst
```

# 安装 锁屏 i3lock-fancy 自动锁屏 xautolock
```
yay -S i3lock-fancy-git xautolock
```

# 安装 终端 时钟
```
yay -S tty-clock
```

# 安装 启动器 rofi
```
yay -S rofi
```

# 安装 壁纸 feh
```
yay -S feh
```

# 混合器
```
yay -S compton-git
```

# fcitx google输入法
```
yay -S fcitx-im fcitx-googlepinyin fcitx-configtool
```
