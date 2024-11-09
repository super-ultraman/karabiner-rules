# Karabiner-Elements Custom Rules for macOS

This repository provides custom rules for [Karabiner-Elements](https://karabiner-elements.pqrs.org/), enabling Windows-style shortcuts and tailored keyboard mappings for specific macOS applications.

## Prerequisites

1. **Install Karabiner-Elements**: Download and install Karabiner-Elements from [karabiner-elements.pqrs.org](https://karabiner-elements.pqrs.org/).

## Using Rules from This Repository

1. **Create a New Rule**:
   - Open **Karabiner-Elements** and go to `Complex Modifications` > `Add rule`.
   - Select `Import More Rules from the Internet...` to browse and understand existing rules, but to use the rules from this repository, continue with the steps below.

2. **Copy the Rule Content**:
   - Open the desired rule file in this repository, such as:
     - [Command+C to Control+C](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-c-to-ctrl-c.json)
     - [Command+V to Control+V](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-v-to-ctrl-v.json)
     - [Command+W to Control+W](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-w-to-ctrl-w.json)
     - [Command+S to Control+S](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-s-to-ctrl-s.json)
   - Copy the JSON content of the file.

3. **Add the Rule to Karabiner Configuration**:
   - Open the Karabiner configuration file located at `~/.config/karabiner/karabiner.json`.
   - Paste the copied JSON content under `"rules"` within the `"profiles"` section of the JSON file.

4. **Save and Reload**:
   - Save the `karabiner.json` file.
   - Restart Karabiner-Elements or go back to `Complex Modifications` to enable the new rule.

After following these steps, the new rule should be active. Repeat for any additional rules you’d like to add.
