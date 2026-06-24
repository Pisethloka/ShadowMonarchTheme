# Shadow Monarch (Solo Leveling Theme)

*"Arise."*

I designed this theme family for developers who want a clean, focused coding environment themed around Sung Jin woo and the system interface in *Solo Leveling*. The main goal was to capture that iconic shadow magic aesthetic—void darkness, glowing electric violets, and system window cyans—without causing eye strain during long sessions.

The extension bundles six distinct variants (three dark, three light) to fit different lighting conditions, personal setups, and color preferences.

---

## The Variants

### Shadow Monarch (Void)
This is the default dark theme. It features a deep purple black canvas that is much softer on the eyes than pure black. The syntax highlighting maps electric purple to keywords, radiant gold to functions, and status window cyan to strings. It mimics the holographic popups of the Solo Leveling system while keeping contrast high enough for easy scanning.

* **Editor Background**: `#0D0A1A`
* **Best for**: Daily coding in standard workspace lighting.

![Shadow Monarch Void](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/void.png)

### Shadow Monarch Abyss
For night sessions or high contrast preferences. Abyss darkens the canvas to an absolute pitch black. This makes the electric purple keywords and neon cyan strings pop like active shadow extraction magic, offering a very stark, glowing contrast.

* **Editor Background**: `#05040B`
* **Best for**: Pitch dark rooms or if you prefer pure black themes.

![Shadow Monarch Abyss](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/abyss.png)

### Shadow Monarch Ember
A dark theme with its accent shifted from violet toward deep red orange ember tones. The backgrounds stay in the same near black family as Void and Abyss, but the syntax palette trades purple aura for fiery ember glow. Keywords burn in bright orange, types smolder in warm amber, and the overall feel is like coding by firelight.

* **Editor Background**: `#100A0A`
* **Best for**: Developers who love dark themes but prefer warm tones over cool purples.

![Shadow Monarch Ember](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/ember.png)

### Shadow Monarch Light
A light mode counterpart styled in the lavender family. Light provides a clean, soft pastel lavender white workspace. It features high contrast indigo, deep violet, warm gold, and emerald green syntax colors that make reading code very comfortable in bright rooms.

* **Editor Background**: `#F5F3FF`
* **Best for**: Working in bright rooms or outdoors.

![Shadow Monarch Light](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/light.png)

### Shadow Monarch Twilight
If you want the clarity of a light theme but find bright white backgrounds too harsh, Twilight is a softer, dusty lavender gray alternative. It drops the overall contrast and reduces glare to keep eye strain to a minimum.

* **Editor Background**: `#E0DBEC`
* **Best for**: Extended daytime coding under fluorescent lights.

![Shadow Monarch Twilight](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/twilight.png)

### Shadow Monarch Dawn
A light theme with its accent shifted from lavender toward warm cream and gold. The backgrounds use soft parchment tones instead of cool lavender whites. Keywords glow in deep amber, functions darken to burnt orange, and the whole palette feels like golden hour sunlight on paper.

* **Editor Background**: `#FFFBF0`
* **Best for**: Developers who prefer light themes with warm, earthy tones.

![Shadow Monarch Dawn](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/dawn.png)

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
| `#A78BFA` | Keywords, control flow, imports, HTML tags | Jin woo's purple aura |
| `#FBBF24` | Functions, methods, React hooks, hovers | System keys and quest highlights |
| `#38BDF8` | Strings, template literals, JSON/CSS values | Holographic status screens |
| `#F43F5E` | Numbers, booleans, constants | Jin woo's eyes / Danger warnings |
| `#34D399` | Comments (*italic*), docstrings | Healing potions / Passive buffs |
| `#E2D9F3` | Variables, parameters, plain text | Silver gray shadow energy |
| `#818CF8` | Punctuation, delimiters, JSX attributes | Shadow soldier energy |

### Ember Variant Accents

| Hex | Role | Visual Concept |
| :--- | :--- | :--- |
| `#F97316` | Keywords, control flow, imports, HTML tags | Ember flame |
| `#FBBF24` | Functions, methods, React hooks | Molten gold |
| `#38BDF8` | Strings, template literals, JSON/CSS values | Cool contrast |
| `#EF4444` | Numbers, booleans, constants | Burning red |
| `#34D399` | Comments (*italic*), docstrings | Forest underglow |
| `#F3E2D9` | Variables, parameters, plain text | Warm cream |
| `#F87171` | Punctuation, delimiters, JSX attributes | Soft ember |

---

## What's New in v0.2.0

Version 0.2.0 is a major update that brings several highly requested UI enhancements, deeper editor styling, and two brand new theme variants.

### Semantic Highlight Upgrades
We have enabled `"semanticHighlighting": true` across all six themes. Now, VS Code will use language servers to resolve scopes more precisely. Readonly variables, function declarations, parameters, properties, classes, and enum members get their own distinct styling rules. Function declarations are now bolded to make your codebase entry points immediately recognizable, and readonly values use distinct accent colors to stand out from standard variables.

### Integrated Chat Panel Theme
For developers using Copilot, Gemini, or other AI chat assistants in VS Code, we fully themed the chat panel. We styled request blocks, borders, avatar backgrounds, and slash commands to blend in with each theme's core palette. The chat sidebars now look like a native part of the interface rather than an unstyled plugin window.

### Bracket Pair Colorization & Guides
To help keep track of deep nesting without getting lost in nested braces, we added full styling for bracket pair colorization and guides. 
* **Nesting Colors**: Brackets transition through six distinct colors based on their nesting level, using the theme's accent palette. 
* **Pair Guides**: Vertical lines connect bracket pairs, with active guides highlighted at full opacity (`66` alpha) and background guides softly visible (`1A` alpha).

### The Ember and Dawn Variants
We expanded the family from four themes to six by introducing **Ember** (our third dark variant) and **Dawn** (our third light variant). Both are built for developers who prefer warm, earthy tones (red orange firelight and golden parchment) instead of the cool lavender and purple hues of the original variants.

---

## Installation

### Manual Install
If you are not installing directly from the marketplace, copy the theme folder into your extensions directory:
* **Windows**: Copy to `%USERPROFILE%\.vscode\extensions\shadow-monarch` (or `.vscode-insiders` for Insiders)
* **macOS / Linux**: Copy to `~/.vscode/extensions/shadow-monarch` (or `.vscode-insiders` for Insiders)

After copying the files, open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`), run **Developer: Reload Window**, and then select **Shadow Monarch** from the color theme list (`Ctrl+K Ctrl+T`).
