# Copilot / Agent Instructions — weyland-yutani-theme

This repository contains a custom theme for Emacs or another text editor/application.

## Code Style
- **Elisp**: Use `lexical-binding: t` and standard `;;;` headers if theme is Emacs-based.
- **CSS/SCSS**: Follow consistent indentation (2 spaces) and use descriptive color/style names.
- Document color schemes and intended use cases.

## Architecture
- Theme definition files (e.g., `theme.el` for Emacs or CSS files for web/editor).
- Configuration for various UI elements, syntax highlighting, and accents.
- Optional documentation of color palette and supported elements.

## Build and Test
- For Emacs themes: load with `emacs -Q -l theme-file.el`.
- For CSS themes: include in project configuration or test in target application.
- Manually verify visual appearance across supported modes or applications.

## Common Patterns
- Define base colors in a centralized location (often at the top of theme file).
- Use consistent naming for related colors (e.g., `bg`, `fg`, `accent`).
- Test in multiple environments to ensure readability and accessibility.

## Quick Checklist
1. Read README.md for supported platforms or applications.
2. Verify color contrast for accessibility.
3. Test the theme in the intended application/environment.
4. Document any dependencies or setup requirements.

---

For theme-specific details, see the README and theme configuration files.
