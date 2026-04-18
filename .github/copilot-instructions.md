# Copilot Instructions for ToolsHub Workspace

## Overview
This workspace contains multiple web projects organized by theme and function. The main components are:
- `ToolsHub/`: Central hub for tools, shopping, and account management
- `CV/`: Personal CV and related assets
- `valentine/`: Interactive Valentine surprise web app
- `assets/`: Shared resources (documents, images, videos)

## Architecture & Patterns
- Each major folder is a standalone web project with its own `index.html`, `styles.css`, and `script.js`.
- Shared assets are stored in `assets/` and referenced as needed.
- No backend/server code; all logic is client-side (HTML/CSS/JS).
- Responsive design is prioritized across projects.

## Developer Workflows
- **No build step required**: Open any `index.html` directly in a browser to view.
- **No tests or CI/CD**: Manual testing by opening pages and interacting.
- **Debugging**: Use browser dev tools (F12) for JS/CSS inspection.

## Project-Specific Conventions
- Folder names reflect project purpose (e.g., `ToolsHub`, `CV`, `valentine`).
- Each project keeps its own assets in a subfolder (e.g., `Images/`, `Documents/`).
- CSS files are named after their function (e.g., `shopByBrand.css`, `createAccount.css`).
- JavaScript files are named `script.js` per project.
- HTML files are named for their feature (e.g., `shopByBrand.html`, `create_account.html`).

## Integration Points
- Projects are loosely coupled; cross-project links are via relative paths.
- Shared images/videos are referenced from `assets/`.
- No external dependencies (no npm, no package.json).

## Examples
- To add a new tool: Create a new HTML/CSS/JS file in `ToolsHub/` and link from `index.html`.
- To update CV: Edit `CV/index.html`, `CV/styles.css`, and add assets to `CV/assets/`.
- To add a new surprise: Create a new folder (like `valentine/`) with its own web files.

## Key Files & Directories
- `ToolsHub/index.html`: Main entry for tools
- `ToolsHub/script.js`: Core JS logic for tools
- `ToolsHub/main-design.css`: Shared styles for ToolsHub
- `CV/index.html`: Personal CV
- `valentine/index.html`: Valentine surprise app
- `assets/`: Shared resources

## Special Notes
- License restrictions: See `valentine/README.md` for usage limits.
- No commercial use for `valentine/` project.

---

**Update this file as new projects or conventions are added.**
