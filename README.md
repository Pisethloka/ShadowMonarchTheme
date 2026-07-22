# Shadow Monarch (Solo Leveling Theme)

*"Arise."*

I designed this theme family for developers who want a clean, focused coding environment themed around Sung Jin-woo and the system interface in *Solo Leveling*. The main goal was to capture that iconic shadow magic aesthetic—void darkness, glowing electric violets, radiant red flames, and glacial system window cyans—without causing eye strain during long sessions.

The extension bundles **eight distinct variants** (five dark, three light) to fit different lighting conditions, personal setups, and color preferences.

---

## The Variants

### Shadow Monarch (Void)
This is the default dark theme. It features a deep purple black canvas that is much softer on the eyes than pure black. Syntax highlighting maps electric purple to keywords, radiant gold to functions, and status window cyan to strings.

* **Editor Background**: `#0D0A1A`
* **Best for**: Daily coding in standard workspace lighting.

![Shadow Monarch Void](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/void.png)

### Shadow Monarch Abyss
For night sessions or high contrast preferences. Abyss darkens the canvas to absolute pitch black, making electric purple keywords and neon cyan strings pop like active shadow extraction magic.

* **Editor Background**: `#05040B`
* **Best for**: Pitch dark rooms or pure black display preferences.

![Shadow Monarch Abyss](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/abyss.png)

### Shadow Monarch Ember
A dark theme with its accent shifted from violet toward deep red orange ember tones. Keywords burn in bright orange and types smolder in warm amber.

* **Editor Background**: `#100A0A`
* **Best for**: Developers who love dark themes with warm firelight tones.

![Shadow Monarch Ember](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/ember.png)

### Shadow Monarch Igris
Inspired by the loyal Red Knight Commander Igris. Built on a metallic dark steel canvas (`#0A090D`) with vivid blood red and crimson flame accents, molten gold function declarations, and silver knight armor text.

* **Editor Background**: `#0A090D`
* **Best for**: High contrast dark coding with sharp crimson knight accents.

![Shadow Monarch Igris](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/igris.png)

### Shadow Monarch Frost
Inspired by the Frost Monarch. Built on a glacial deep ice black background (`#060C14`) with vibrant electric cyan and frost blue accents, crystal blue strings, and frosted silver text.

* **Editor Background**: `#060C14`
* **Best for**: Developers who love cool, icy cyan and blue neon dark themes.

![Shadow Monarch Frost](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/frost.png)

### Shadow Monarch Light
A light mode counterpart styled in the lavender family. Provides a soft pastel lavender white workspace with high contrast indigo, deep violet, warm gold, and emerald syntax colors.

* **Editor Background**: `#F5F3FF`
* **Best for**: Working in bright rooms or outdoors.

![Shadow Monarch Light](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/light.png)

### Shadow Monarch Twilight
A softer, dusty lavender gray light theme that drops contrast slightly to reduce glare under harsh lighting.

* **Editor Background**: `#E0DBEC`
* **Best for**: Extended daytime coding under fluorescent lights.

![Shadow Monarch Twilight](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/twilight.png)

### Shadow Monarch Dawn
A light theme styled in warm cream and gold. Keywords glow in deep amber and functions darken to burnt orange on a soft parchment canvas.

* **Editor Background**: `#FFFBF0`
* **Best for**: Developers who prefer light themes with warm, earthy tones.

![Shadow Monarch Dawn](https://raw.githubusercontent.com/Pisethloka/ShadowMonarchTheme/main/images/dawn.png)

---

## Expanded Multi-Language Syntax Support

Shadow Monarch includes tailored syntax highlighting rules for a wide variety of modern languages:
* **JavaScript / TypeScript & React (JSX/TSX)**: Full hook, component, decorator, and prop styling.
* **Python**: Specific colors for `@decorators`, `self`/`cls`, type hints (`Optional[str]`), and docstrings.
* **Rust**: Dedicated styling for lifetimes (`'a`), macros (`println!`, `vec!`), attributes (`#[derive]`), and traits.
* **Go**: Channels, goroutines, struct tags, and interface definitions.
* **Vue & Svelte**: Single File Component tags (`<script>`, `<style>`, `<template>`) and template directives (`v-if`, `bind:`).
* **Tailwind CSS**: Custom class string scope highlighting.
* **SQL, Docker, YAML, & Shell**: DML/DDL keywords, Docker instructions (`FROM`, `RUN`), YAML keys, and shell environment variables.

---

## What's New in v0.3.0

Version 0.3.0 is a major release expanding the theme family and adding deep syntax coverage:

* **Two New Character Variants**: Added **Shadow Monarch Igris** (Blood Red & Steel) and **Shadow Monarch Frost** (Glacial Cyan & Ice Blue).
* **Multi-Language Syntax Coverage**: Added dedicated syntax scopes for Python, Rust, Go, Vue, Svelte, Tailwind CSS, SQL, Docker, YAML, and Shell.
* **Modern Workbench UI Integration**: Added support for Editor Sticky Scroll (`editorStickyScroll.background`), Command Center title bar search, Copilot ghost text (`editorGhostText.foreground`), split diff highlights, and Test Explorer status icons.

---

## Installation

### Manual Install
Copy the extension directory into your VS Code extensions folder:
* **Windows**: `%USERPROFILE%\.vscode\extensions\shadow-monarch`
* **macOS / Linux**: `~/.vscode/extensions/shadow-monarch`

After copying the files, reload VS Code (`Ctrl+Shift+P` -> **Developer: Reload Window**) and select **Shadow Monarch** from the color theme picker (`Ctrl+K Ctrl+T`).
