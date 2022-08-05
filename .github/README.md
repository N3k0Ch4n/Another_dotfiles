
<h1 align='center'>
  
  <br>
  
  My Rice..
</h1>

<img align='right' alt="GitHub Repo stars" src="https://img.shields.io/github/stars/rklyz/MyRice?color=%23E6B88A&logo=starship&style=for-the-badge">

<br>

<br>

<br>

<img align='right' width='380px' src="https://i.imgur.com/pfo1nV6.png">

An awesome(wm) **rice** that I made to get comfy experience for my daily usage.<br>

So.. go ahead on what you're trying to do.

I wouldn't mind.

### My setup 🧰:

- **OS** - Endeavor OS
- **WM**   - AwesomeWM
- **Term**  -  Wezterm
- **Comp**  -  Picom

Nothing special

> I'm using 1920x1080 screen resolution. Hope things goes perfectly fine for others..

<br>

---

<br>

### How do I get this ❓

<br>

Well.. You just need to follow (or not) the following instructions given below

<details close>

<summary><b>1. Install the Dependencies</b></summary>
  
  - [awesome-git](https://aur.archlinux.org/packages/awesome-git)
  - [mpd-mpris](https://github.com/natsukagami/mpd-mpris)
  - [picom (pijulius fork)](https://github.com/pijulius/picom)
  - jq
  - inotify-tools
  - playerctl
  - brightnessctl
  - pulseaudio
  - network-manager
  - rxvt-unicode
  - mpd
  - ncmpcpp
  - redshift
  - bluez
  - bluez-utils
  - wezterm

<br>

**Required Fonts**

- [Material Design Icons](https://materialdesignicons.com/)
- Roboto
- Iosevka

</details>

<br>

<details close>

<summary><b>2. Clone the repo</b></summary>

```sh
git clone https://github.com/rklyz/MyRice.git
cd MyRice/conf/
git submodule init
git submodule update
```

</details>

<br>

<details close>

<summary><b>3. Copy the config file</b></summary>

```sh
cp -rf cava awesome mpd ncmpcpp picom $HOME/.config/
cp -rf .Xresources .bashrc .vimrc .zshrc $HOME/
cd ..; cp -rf misc/fonts/* $HOME/.local/share/fonts/
fc-cache -v
systemctl enable mpd.service; systemctl start mpd.service
```

Change to your wall location at awesome.theme.theme

You might wanna put your city name inside awesome.signals.weather

</details>

<br>

**4. Restart your system & Log in with awesomeWM**

<br>

**5. You're done!**

<br>

---

<br>

### Did you say keybind?

| Keybinds    | Uses     |
| ----------- | -------- |
| Mod + Enter | Terminal |
| Mod + Space | Layout   |
| Mod + r     | Rofi      |
| alt + c     | Sidebar  |
| Mod + Ctrl + n | Un-minimize |

<br>

---

<br>

### Colorscheme

The colorscheme that used in this rice is custom. (still doesn't have name yet)

### Light

<img width='300px' src='https://i.imgur.com/sXDJ3dw.png'>

### Dark

<img width='300px' src='https://i.imgur.com/SkdhTVQ.png'>

---

<br>

### Improvement in the future

- [ ] Notifications enhancement
- [ ] Lock Screen 
- [x] Code-Cleaning

<br>

---

<br>

### Million of Thanks to 💕

- [Ner0z](https://github.com/ner0z/dotfiles)
- [Drahenprofi](https://github.com/drahenprofi/dotfiles)
- [Elenapan](https://github.com/elenapan/dotfiles)
- [Saimoom/Harry](https://github.com/saimoomedits/dotfiles)
- [Rxyhn](https://github.com/rxyhn/dotfiles)
- [unix-parrot](https://github.com/unix-parrot)

<br>

**And lastly.. To You Guys!**
