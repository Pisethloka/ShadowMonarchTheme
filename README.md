# Shadow Monarch (Solo Leveling Theme)

*“Arise.”*

I built this theme family for developers who want a clean, focused coding environment themed around Sung Jin-woo and the system interface in *Solo Leveling*. The goal was to capture that shadow-magic aesthetic—void darkness, glowing electric violets, and system-window cyans—without sacrificing readability or causing eye strain during long sessions.

The extension bundles four distinct variants (two dark, two light) designed for different lighting conditions and personal preferences.

---

## The Variants

### Shadow Monarch (Void)
This is the default dark theme. It features a deep purple-black canvas that is much softer on the eyes than pure black. The syntax highlighting maps electric purple to keywords, radiant gold to functions, and status-window cyan to strings. It mimics the holographic popups of the Solo Leveling system while keeping contrast high enough for easy scanning.

* **Editor Background**: `#0D0A1A`
* **Best for**: Daily coding in standard workspace lighting.

![Shadow Monarch Void](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/void.png)

### Shadow Monarch Abyss
For night sessions or high-contrast fans. Abyss strips the background luminance down to an absolute pitch black. This makes the electric purple keywords and neon cyan strings pop like active shadow extraction magic, offering a very stark, glowing contrast.

* **Editor Background**: `#05040B`
* **Best for**: Pitch-dark rooms or if you prefer pure black themes.

![Shadow Monarch Abyss](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/abyss.png)

### Shadow Monarch Light
A clean, pastel counterpart built for bright workspaces. It uses a soft lavender-white base and replaces the neon syntax with highly legible deep indigo, dark violet, warm gold, and emerald green. It keeps the purple family aesthetic but makes it comfortable to read in direct sunlight.

* **Editor Background**: `#F5F3FF`
* **Best for**: Bright offices or working outdoors.

![Shadow Monarch Light](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/light.png)

### Shadow Monarch Twilight
If you want the clarity of a light theme but find bright white backgrounds too harsh, Twilight is a softer, dusty lavender-gray alternative. It drops the overall contrast and reduces glare to keep eye strain to a minimum.

* **Editor Background**: `#E0DBEC`
* **Best for**: Extended daytime coding under fluorescent lights.

![Shadow Monarch Twilight](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/twilight.png)

---

## UI and Sidebar Adjustments

I made sure the Explorer sidebar and editor chrome felt clean and structured rather than a generic dark block:
* **Separation**: A glowing violet border (`#2D1B69B3`) divides the editor from the sidebar, which has its own absolute dark background (`#0A0812`) for depth.
* **Tree Guides**: Indent guides in the file explorer use a muted purple (`#4C3A7A99`), with the active folder path highlighted in electric violet (`#7C3AED`).
* **Hover States**: Hovering over files in the explorer tree highlights them in a glowing gold (`#FBBF24`), making the UI feel responsive.
* **Scrollbars & Highlights**: Subtle scrollbar sliders (`#2D1B69`) and selections (`#2D1B69B3` at 70% opacity) prevent visual clutter.

---

## Syntax Color Mappings (Dark Variants)

| Hex | Role | Visual Concept |
| :--- | :--- | :--- |
| `#A78BFA` | Keywords, control flow, imports, HTML tags | Jin-woo's purple aura |
| `#FBBF24` | Functions, methods, React hooks, hovers | System keys and quest highlights |
| `#38BDF8` | Strings, template literals, JSON/CSS values | Holographic status screens |
| `#F43F5E` | Numbers, booleans, constants | Jin-woo's eyes / Danger warnings |
| `#34D399` | Comments (*italic*), docstrings | Healing potions / Passive buffs |
| `#E2D9F3` | Variables, parameters, plain text | Silver-gray shadow energy |
| `#818CF8` | Punctuation, delimiters, JSX attributes | Shadow soldier energy |

---

## Installation

### Manual Install
If you aren't installing directly from the marketplace, copy the theme folder into your extensions directory:
* **Windows**: Copy to `%USERPROFILE%\.vscode\extensions\shadow-monarch` (or `.vscode-insiders` for Insiders)
* **macOS / Linux**: Copy to `~/.vscode/extensions/shadow-monarch` (or `.vscode-insiders` for Insiders)

After copying the files, open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`), run **Developer: Reload Window**, and then select **Shadow Monarch** from the color theme list (`Ctrl+K Ctrl+T`).
