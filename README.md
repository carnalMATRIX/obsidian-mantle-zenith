# Zenith Theme (Desktop Only)

> [!IMPORTANT]
> **Desktop Only**: This theme is designed and optimized for the Obsidian desktop application. Mobile support is not currently a priority.

> [!CAUTION]
> **Status: Beta (v1.0.0)**  
> This theme is currently in Alpha. Visual elements and color tokens are subject to change.

Zenith is a modern, high-contrast Obsidian theme designed for performance and visual clarity. It serves as the aesthetic foundation for the **Project Mantle** ecosystem, featuring a unique "floating capsule" tab design and a sophisticated color palette.

## Design Philosophy
Zenith focuses on depth and interaction. It uses subtle glows, backdrop blurs, and smooth transitions to create a "live" feel. It is optimized for both Light Mode (Subtle Parchment) and Dark Mode (IDE Deep Blue), ensuring readability across all environments.

## Features
- **Floating Capsule Tabs**: A complete redesign of the workspace tab headers for a cleaner, modern look.
- **Cohesive Palette**: Carefully selected colors for headings (Spectrum logic) and interactive elements.
- **Mantle Optimized**: Designed to be the primary theme for all Mantle plugins (Kanban, Calendar, etc.), providing them with enhanced styling and integration.

## Installation

### Manual Installation
1. Download the `theme.css` and `manifest.json` from the latest release.
2. Create a folder named `Zenith` in your vault's `.obsidian/themes/` directory.
3. Move the downloaded files into that folder.
4. Open Obsidian and select **Zenith** in **Settings > Appearance > Themes**.

## Development

To modify this theme:
1. Navigate to this directory in your terminal.
2. Install dependencies: `npm install`
3. Build the theme: `npm run build` (This compiles the SCSS files into `theme.css`).
4. For active development, use: `npm run dev`

The theme source code is located in the `src/` directory and uses modular SCSS for maintainability.
