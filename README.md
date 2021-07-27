# fcitx5-nord

Fcitx5 theme based on Nord color.

## Screenshot

![Dark Variant](https://user-images.githubusercontent.com/29998228/127147288-372b2a8b-59ff-47be-9f60-274b12361c8c.png)
![Light Variant](https://user-images.githubusercontent.com/29998228/127147303-256c017a-9efa-45fd-b514-48488ec3f5f9.png)

## Usage

### Installation

```sh
git clone https://github.com/tonyfettes/fcitx5-nord.git
mkdir -p ~/.local/share/fcitx5/themes/
cd fcitx5-nord
cp -r Nord-Dark/ Nord-Light/ ~/.local/share/fcitx5/themes/
```

### Enabling

In `~/.config/fcitx5/conf/classicui.conf`, change the `Theme` line as

```dosini
Theme=Nord-Dark
# or
Theme=Nord-Light
```

Then restart fcitx5 to apply the theme.

```sh
fcitx5 -r
```
