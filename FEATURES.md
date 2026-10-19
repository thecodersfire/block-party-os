# Built-in features for block-party-os

Purpose: Minecraft gaming

1. **prepare racing and game notes** — run block-party-os-workspace. It creates ~/Documents/block-party-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run block-party-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/block-party-os-session-plans/.
3. **check game and controller readiness** — run block-party-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/block-party-os-workspace features/block-party-os-plan features/block-party-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for Minecraft gaming:

1. **Prism Launcher** — org.prismlauncher.PrismLauncher
2. **VSCodium** — com.vscodium.codium
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for Minecraft gaming:

1. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
2. **GIMP** — edit raster graphics and textures (org.gimp.GIMP)
3. **Inkscape** — create vector illustrations and diagrams (org.inkscape.Inkscape)
4. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
9. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
10. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
