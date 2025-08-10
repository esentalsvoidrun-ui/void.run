# VOIDRUN
A human-first terminal layer: ritualized startup, reflective logging, glitch/retro aesthetics, and safe backups.

## Quick start (manual install)
- Save scripts locally (see `scripts/`) and make them executable.
- Add the `.desktop` shortcut if you want a double-click launcher.
- Optional: use `install.sh` for one-shot setup.

## Roadmap
- v0.1: Splash, Retro/Glitch modes, Reflect/Startday, Safe .bashrc backup/restore
- v0.2: VOIDMAIL, Itch/Substack launcher, theme packs
- v0.3: .deb packaging & Plymouth theme
# VOIDRUN

VOIDRUN is not “an app”. It’s a ritual in your terminal.  
A living, glitchy pulse that turns boot + shell into a scene.

---

## 🚀 Install
Download the latest build from **Releases** and install:

**Releases:** ../../releases

Debian/Ubuntu:
```bash
sudo dpkg -i voidrun_<version>.deb || sudo apt -f install
voidrun --overdrive
