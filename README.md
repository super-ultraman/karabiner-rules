# Karabiner-Elements Custom Rules for macOS

This repository provides custom rules for [Karabiner-Elements](https://karabiner-elements.pqrs.org/), enabling Windows-style shortcuts and tailored keyboard mappings for specific macOS applications.

## Prerequisites

1. **Install Karabiner-Elements**: Download and install Karabiner-Elements from [karabiner-elements.pqrs.org](https://karabiner-elements.pqrs.org/).

## Using Rules from This Repository

1. **Download the Desired Rule Files**:
   - Download the JSON files for the rules you want to use from the following links:
     - [Command+C to Control+C](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-c-to-ctrl-c.json)
     - [Command+V to Control+V](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-v-to-ctrl-v.json)
     - [Command+W to Control+W](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-w-to-ctrl-w.json)
     - [Command+S to Control+S](https://raw.githubusercontent.com/super-ultraman/karabiner-rules/refs/heads/main/app-specific/windows-remote/command-s-to-ctrl-s.json)

2. **Copy Files to Karabiner-Elements Configuration Folder**:
   - Move the downloaded JSON files to Karabiner’s `complex_modifications` folder:
     ```plaintext
     ~/.config/karabiner/assets/complex_modifications/
     ```

3. **Load the Rules in Karabiner-Elements**:
   - Open **Karabiner-Elements**.
   - Go to `Preferences > Complex Modifications > Add rule`.
   - Find and enable the rules you copied to the configuration folder.

After completing these steps, the rules will be active in Karabiner-Elements.
