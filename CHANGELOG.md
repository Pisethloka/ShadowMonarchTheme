# Changelog

All notable changes to the Shadow Monarch theme extension will be documented in this file.

## [0.4.0] — 2026-07-30

### Added
- **Rich Syntax Color Spectrum (12–19 distinct colors per theme)**: Expanded TextMate token rules to 51 rules per theme, giving distinct color identities to control flow keywords, function declarations vs calls vs library built-ins, regular expressions (`string.regexp`), parameters, readonly constants, interfaces, enums, structs, decorators, template literal expressions, and dunder methods across all 8 theme variants.

## [0.3.1] — 2026-07-27

### Added
- **Full Scope Block Background Fills**: Tinted background fill shading for code blocks (`editorBracketPairGuide.activeBackground1..6` & `background1..6`), matching the vertical guide line color from the top opening tag down to the closing tag.
- **Rainbow Indent & Bracket Pair Guides**: Configured 6 distinct, low-opacity colors for all vertical guide lines from left to right across all 8 theme variants.

## [0.3.0] — 2026-07-27

### Added
- **49 New Workbench UI Color Keys** across all 8 themes (208 total UI keys per theme): Minimap (background, selection, highlights), Inlay Hints (types & parameters), Diagnostics (error/warning/info squiggles & overview ruler markers), Peek View (definition & reference popups), Git Merge Conflict headers & Git Gutter indicators, Code Lens, Word Highlights, Symbol Icons, Notifications, Debug Toolbar, Notebook Cells, Settings page, and Progress Bar.
- **Expanded Semantic Token Colors (18 rules per theme)**: Full semantic token highlighting for namespaces, interfaces, type parameters, enums, structs, decorators, macros, built-in standard library variables/functions, readonly properties, and method declarations.
- Expanded syntax highlighting for Python (`@decorators`, `self`/`cls`, type hints, docstrings), Rust (lifetimes, macros, attributes, traits), Go (channels, goroutines, raw strings), Vue & Svelte (SFC tags & directives), Tailwind CSS (class names), SQL, Docker, YAML, and Shell script variables.
- Two new theme variants: **Shadow Monarch Igris** (Dark metallic steel black with blood red accents) and **Shadow Monarch Frost** (Glacial deep ice black with electric cyan accents).

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
