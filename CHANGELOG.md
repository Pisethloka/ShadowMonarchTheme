# Changelog

All notable changes to the Shadow Monarch theme extension will be documented in this file.

## [0.3.0] — 2026-07-22

### Added
- Expanded syntax highlighting for Python (`@decorators`, `self`/`cls`, type hints, docstrings), Rust (lifetimes, macros, attributes, traits), Go (channels, goroutines, raw strings), Vue & Svelte (SFC tags & directives), Tailwind CSS (class names), SQL, Docker, YAML, and Shell script variables.
- New theme variant: **Shadow Monarch Igris** (Dark metallic steel black with blood red and crimson knight accents).
- New theme variant: **Shadow Monarch Frost** (Glacial deep ice black with electric cyan and frost blue accents).
- Modern Workbench UI colors across all themes: `editorStickyScroll.background`, `commandCenter.background`, `editorGhostText.foreground`, `diffEditor.insertedTextBackground`, `diffEditor.removedTextBackground`, and `testing` status icons.

## [0.2.1] — 2026-06-29

### Changed
- Updated extension logo to new premium Shadow Monarch artwork

## [0.2.0] — 2026-06-24

### Added
- Semantic token highlighting across all 6 themes (variable.readonly, parameter, property, function.declaration, class, enumMember)
- Chat panel colors for Copilot and AI integration (chat.requestBackground, chat.requestBorder, chat.slashCommandBackground, chat.slashCommandForeground, chat.avatarBackground, chat.avatarForeground)
- Bracket pair colorization with rank progression through 6 nesting levels
- Bracket pair guide colors (active and inactive) for visual nesting depth
- New variant: Shadow Monarch Ember (dark theme with red orange ember accent)
- New variant: Shadow Monarch Dawn (light theme with warm cream and gold accent)
- Keywords, bugs URL, and gallery banner metadata added to package.json

### Fixed
- statusBar.debuggingBackground was missing from Light and Twilight themes, now consistent across all 6 variants

## [0.1.5] — 2026-06-16

### Fixed
- README screenshot links updated to use absolute raw GitHub URLs for Marketplace rendering
- Version bump to force VS Code client cache refresh

## [0.1.0] — 2026-06-14

### Added
- Initial release with 4 theme variants: Void, Abyss, Light, and Twilight
- Full UI color theming for editor, sidebar, activity bar, status bar, tabs, panels, terminal
- 26 syntax highlighting rules covering JS/TS, React/JSX, HTML, CSS, JSON, and Markdown
- Solo Leveling inspired visual identity with purple aura, system window cyan, and quest gold
