# Changelog

All notable changes to the Shadow Monarch theme extension will be documented in this file.

## [0.4.1] — 2026-09-04

### Added & Polished
- **S-Tier Luminance & Hierarchy Polish**:
  - **70/30 Neutral Balance**: Softened delimiters and punctuation (`() {} [] , ; :`) across all 8 variants to calm secondary tones, letting functions, identifiers, and keywords instantly pop out.
  - **Atmospheric Line Aura**: Tuned `editor.lineHighlightBackground` from harsh 25% opacity down to an elegant ethereal wash (8-10% opacity) matching Catppuccin and Tokyo Night benchmarks.
  - **Calm Indent Guides**: Muted inactive rainbow indent guides from noisy 27% stripes down to subtle depth (8% opacity), while retaining distinct glowing active block highlighting (`99` alpha).
  - **Refined Comment Elegance**: Replaced loud neon green comments in dark variants with sophisticated, eye-friendly tones (smoldering ash `#8C7368` in Ember, glacial mist `#50889E` in Frost, mystic sage `#529B7C` in Void/Abyss).
  - **LSP Semantic Parity**: Synchronized 18 semantic token rules with TextMate grammars to eliminate token flickering or repainting when language servers (TypeScript, Pylance, Rust-Analyzer) initialize.
  - **Atmospheric Editor Details**: Added explicit styling for folding controls (`editorGutter.foldingControlForeground`), glowing links (`editorLink.activeForeground`), subtle column rulers, and whitespace indicators.

## [0.4.0] — 2026-07-30

### Added
- **4-Tier Depth Architecture (275 UI Keys per Theme)**: Complete elevation layering across all 8 themes (Crust `#07050E`, Mantle `#0A0816`, Base `#0D0A1A`, and floating Surface0/1/2 panels) with glowing command palette and modal dialogs.
- **Rich Syntax Color Spectrum (59 Rules per Theme)**: Expanded TextMate token rules to 59 rules per theme, giving distinct color identities to control flow keywords, function declarations vs calls vs library built-ins, regular expressions (`string.regexp`), parameters, readonly constants, interfaces, enums, structs, decorators, template literal expressions, and dunder methods across all 8 theme variants.
- **First-Class Frontend Syntax Highlighting**: Dedicated token coloring for React custom components (`<Header />`), JSX event props (`onClick`, `onChange`), CSS property names vs values vs units (`px`, `rem`, `%`), CSS class (`.class`) & ID (`#id`) selectors, pseudo-classes (`:hover`, `:focus`), CSS variables (`var(--bg)`), Tailwind utility classes & variants (`hover:`, `dark:`), Vue SFC tags & directives (`v-if`, `@click`), and Svelte directives (`on:click`, `bind:value`).

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
