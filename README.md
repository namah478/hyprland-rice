# Hyprland Rice by Raphael & Drake123

![Hyprland]((https://commons.wikimedia.org/wiki/File:Hyprland_logo.png#/media/File:Hyprland_logo.png))

Welcome to **Hyprland-Rice**, a custom, minimal, and aesthetic Hyprland configuration created by **Raphael (Yash Namdev)** and **Drake123 (Aditya Verma)**. This project is our take on making Hyprland more functional, visually appealing, and efficient for daily use.

---

## ✨ Features
- Custom **hyprland.conf** built from scratch
- Optimized **waybar**, **dunst**, and **rofi** setup
- **Touchpad gestures** for smooth navigation
- **Minimalist & performance-focused** configuration
- **Custom keybindings** for efficiency
- **Modular structure** for easy tweaking

---

## 📥 Installation
### Requirements:
- **Arch Linux** or any Arch-based distro (Manjaro, EndeavourOS, etc.)
- **Hyprland** installed (`hyprland-git` recommended)
- Basic understanding of Linux config files

### Clone the Repository:
```bash
cd ~/.config
mv hypr hypr.bak  # Backup existing config
mkdir -p ~/.config/hyprland-rice && cd ~/.config/hyprland-rice
git clone https://github.com/YOUR_USERNAME/hyprland-rice.git .
```

### Apply Configuration:
```bash
ln -sf ~/.config/hyprland-rice/hyprland.conf ~/.config/hypr/hyprland.conf
```

### Install Dependencies:
```bash
sudo pacman -S waybar dunst rofi kitty nwg-look blueman
```

Restart Hyprland to apply the changes.

---

## 🎮 Keybindings
| Keybinding | Action |
|------------|--------|
| `Super + Q` | Close window |
| `Super + Enter` | Open terminal (kitty) |
| `Super + F` | Open browser (Firefox) |
| `Super + D` | Open application launcher (Rofi) |
| `Super + Shift + R` | Reload Hyprland |
| `Super + Shift + Q` | Logout |
| `Super + P` | Take a screenshot |

---

## 🖌️ Themes & Styling
We’ve included a minimal yet elegant theme that works well with **Waybar, Rofi, and Dunst**. Feel free to modify the theme by editing:
```bash
~/.config/hyprland-rice/themes/theme.conf
```
---

## ⚙️ Customization
### Modify Wallpaper:
```bash
swww img ~/Pictures/wallpaper.png
```
### Adjust Waybar Style:
Modify `~/.config/waybar/style.css` to tweak colors and fonts.

---

## 💡 Credits
A collaborative effort by **Raphael (Yash Namdev)** and **Drake123 (Aditya Verma)** to enhance the Hyprland experience.

For any issues or improvements, feel free to contribute! 🚀
