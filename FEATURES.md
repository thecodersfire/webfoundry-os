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
