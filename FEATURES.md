# Built-in features for block-party-os

Purpose: Minecraft gaming

1. **prepare racing and game notes** — run block-party-os-workspace. It creates ~/Documents/block-party-os-workspace/ with Game Notes, Screenshots, Capture Plans folders.
2. **plan a play or streaming session** — run block-party-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/block-party-os-session-plans/.
3. **check game and controller readiness** — run block-party-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/block-party-os-workspace features/block-party-os-plan features/block-party-os-check "$HOME/.local/bin/"
