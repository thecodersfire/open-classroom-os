# Built-in features for open-classroom-os

Purpose: remote learning

1. **prepare study and research files** — run open-classroom-os-workspace. It creates ~/Documents/open-classroom-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run open-classroom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/open-classroom-os-session-plans/.
3. **check study and source readiness** — run open-classroom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/open-classroom-os-workspace features/open-classroom-os-plan features/open-classroom-os-check "$HOME/.local/bin/"
