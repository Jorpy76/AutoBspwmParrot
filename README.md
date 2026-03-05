# AutoBspwmParrot

<div align="center">
  <h1>🦜 BSPWM Environment for ParrotOS + VMware</h1>
  <p>Automated installation script for BSPWM window manager adapted for ParrotOS Security Edition in VMware environments</p>
</div>

---

## 🎯 Features

- **🎨 Window Manager**: BSPWM with custom keybindings
- **📁 File Manager**: PCManFM-Qt with dark theme
- **🌐 Browser**: Brave Browser (default)
- **🔒 Lockscreen**: Betterlockscreen with custom wallpapers
- **🎵 Audio**: PipeWire 1.4.2 + WirePlumber 0.5.8 compatible
- **📊 Panel**: Polybar with custom modules
- **🚀 Terminal**: Kitty with custom configuration
- **🎨 Theme**: Nord-inspired with dark aesthetic
- **⌨️ Shortcuts**: Mechanical keyboard controls (F2-F10)
- **🎬 MPV Controls**: YouTube-TUI integration

---

## 🖼️ Custom Wallpapers

This setup includes 5 carefully selected wallpapers:

- **virus-nord.png** (Default) - Nord theme inspired
- **flower_tokyo.png** - Tokyo flowers aesthetic
- **Parrot-1.png** - ParrotOS logo
- **venom.jpg** - Venom artwork
- **plain-wallpaper.png** - Minimalist design

---

## 🚀 Quick Installation

```bash
git clone https://github.com/YOUR_USERNAME/AutoBspwmParrot.git
cd AutoBspwmParrot
sudo bash AutoBSPWM.sh
```

### During Installation:
1. Select **Virtual Machine** when prompted
2. Choose to install **Brave Browser** (optional)
3. Configure keyboard shortcuts (FN or Windows key)
4. All configurations will be applied automatically

---

## ⌨️ Essential Shortcuts

### Window Management
| Shortcut | Action |
|----------|--------|
| `Super + Enter` | Open terminal (Kitty) |
| `Super + W` | Open Brave Browser |
| `Super + Shift + W` | Open Brave (floating) |
| `Super + Shift + A` | Open PCManFM-Qt |
| `Super + Shift + D` | Rofi launcher |
| `Super + Q` | Close window |
| `Super + Shift + Q` | Logout |
| `Super + Shift + R` | Reload BSPWM |

### Mechanical Keyboard Controls (PipeWire Compatible)
| Shortcut | Action |
|----------|--------|
| `F10` | Increase volume +5% |
| `F9` | Decrease volume -5% |
| `F8` | Mute/Unmute |
| `F3` | Increase brightness +5% |
| `F2` | Decrease brightness -5% |

### MPV Controls (YouTube-TUI)
| Shortcut | Action |
|----------|--------|
| `Alt + P` | Pause/Resume video |
| `Super + Alt + Q` | Close MPV |
| `Alt + F10` | Increase MPV volume only |
| `Alt + F9` | Decrease MPV volume only |

### Workspaces
| Shortcut | Action |
|----------|--------|
| `Super + 1-8` | Switch to workspace |
| `Super + Shift + 1-8` | Move window to workspace |

---

## 🛠️ System Requirements

- **OS**: ParrotOS Security Edition (or Debian-based)
- **Virtualization**: VMware Workstation/Player (recommended)
- **RAM**: 2GB minimum, 4GB recommended
- **Display**: 1920x1080 minimum resolution

---

## 📦 Included Software

### Core Components
- **BSPWM** - Tiling window manager
- **SXHKD** - Hotkey daemon
- **Polybar** - Status bar
- **Rofi** - Application launcher
- **Picom** - Compositor (optional)
- **Dunst** - Notification daemon

### Applications
- **Kitty** - Terminal emulator
- **PCManFM-Qt** - File manager with dark theme
- **Brave** - Web browser
- **Flameshot** - Screenshot tool
- **Betterlockscreen** - Lock screen

### Optional Tools
- Burpsuite Professional
- Obsidian
- VSCode
- PyCharm Community
- Postman
- Neovim with NvChad

---

## 🎨 Customization

### Change Wallpaper
```bash
setWallpaper -i ~/Wallpapers/flower_tokyo.png
setWallpaper -i ~/Wallpapers/venom.jpg -s  # Save as permanent
```

### Reload Configuration
```bash
Super + Escape  # Reload SXHKD
Super + Shift + R  # Reload BSPWM
```

---

## 📚 Documentation

For detailed adaptation information for ParrotOS, check the parent directory for:
- **ADAPTACIONES_PARROT.md** - Complete adaptation guide

---

## 🤝 Credits

**Adapted for ParrotOS by**: jorgerios  
**Original AutoBspwmKali**: [Justice-Reaper](https://github.com/Justice-Reaper/AutoBspwmKali)

### Key Adaptations:
- Thunar → PCManFM-Qt with dark theme
- PipeWire/WirePlumber audio compatibility
- Brave Browser integration
- Custom wallpapers collection
- Mechanical keyboard controls
- MPV media controls

---

## 📝 License

This project maintains the original license from AutoBspwmKali.

---

## 🐛 Issues & Support

If you encounter any issues specific to ParrotOS:
1. Check `ADAPTACIONES_PARROT.md` for ParrotOS-specific configurations
2. Ensure you selected "Virtual Machine" during installation
3. Verify PipeWire is running: `pactl info`

---

<div align="center">
  <p>Made with ❤️ for ParrotOS + VMware</p>
  <p>🦜 Secure • Fast • Customizable</p>
</div>
