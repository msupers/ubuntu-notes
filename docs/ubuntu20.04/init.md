# ubuntu20.04初始化

- 最小化安装

- 语言选择中文

## 配置国内update源

- come soon~

- 更新软件和升级系统
```bash
sudo apt update &&　sudo apt upgrade
```

## 中文目录to英文

```bash
export LANG=en_US
xdg-user-dirs-gtk-update
export LANG=zh_CN
```

## 常用软件安装

```bash
sudo apt install openssh-server screenfetch screenkey vim zsh git -y
```

## 关闭sudo密码

>这一行 %sudo ALL=(ALL:ALL) ALL <br> 改为 %sudo ALL=(ALL:ALL) NOPASSWD:ALL

```bash
sudo vim /etc/sudoers
```
