# edu-i3

Educational / tutorial repository for [i3wm](https://i3wm.org/), the popular tiling window manager. Part of the `~/EDU/` learning series — a working i3 config dropped on top of a fresh Arch / Kiro install.

## What's in this repo

- `etc/skel/` — i3 config + supporting dotfiles that land in `/etc/skel/`.
- `setup.sh`, `up.sh`, `cleanup.sh` — standard EDU bash scaffold.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-i3-git
```

You'll also need i3:

```bash
sudo pacman -S i3-wm i3status i3lock
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-i3.git
cd edu-i3
sudo cp -r etc/skel/. /etc/skel/
```

Existing users can copy the config into their own home:

```bash
cp -rT /etc/skel ~/
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
