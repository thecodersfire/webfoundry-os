# Built-in features for webfoundry-os

Purpose: frontend web development

1. **prepare a technical project** — run webfoundry-os-workspace. It creates ~/Documents/webfoundry-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run webfoundry-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/webfoundry-os-session-plans/.
3. **check technical change readiness** — run webfoundry-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/webfoundry-os-workspace features/webfoundry-os-plan features/webfoundry-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for frontend web development:

1. **Wireshark** — org.wireshark.Wireshark
2. **KiCad** — org.kicad.KiCad
3. **Arduino IDE 2** — cc.arduino.IDE2

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for frontend web development:

1. **Thonny** — write and debug Python code (org.thonny.Thonny)
2. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
3. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
4. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
5. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
