# fcitx5-nord

Fcitx5 theme based on Nord color.

## Screenshot

![light](./shot/light.png)

![dark](./shot/dark.png)

## Usage

1. install

   `git clone https://github.com/tonyfettes/fcitx5-nord.git`

   `mkdir -p ~/.local/share/fcitx5/themes/`

   `cd fcitx5-nord`

   `cp -r nord-dark/ nord-light/ ~/.local/share/fcitx5/themes/`

2. enable

   `vim ~/.config/fcitx5/conf/classicui.conf`

   change the theme to: 

   `nord-dark` or `nord-light`

3. restart fcitx5

   `fcitx5 -r`
