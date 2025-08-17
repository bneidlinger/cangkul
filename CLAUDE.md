# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static website for the Cangkul (Cangkulan) card game, a traditional Indonesian follow-suit card game. The project consists of a single HTML file with embedded CSS styling and minimal JavaScript for print and clipboard functionality.

## Project Structure

- `cankgul.html` - Main HTML file containing game rules, how-to-play guide, and all styling
- `dog.png` - Image asset
- `game.png` - Image asset

## Development Guidelines

### CSS Variables
The project uses CSS custom properties for theming:
- `--bg`: Background color
- `--panel`: Panel background
- `--ink`: Main text color
- `--muted`: Muted text color
- `--accent`: Primary accent color
- `--accent2`: Secondary accent color
- `--bad`: Error/warning color

### Styling Conventions
- Uses system fonts with fallback chain
- Dark theme with gradient background
- Responsive grid layout using CSS Grid
- Border-radius for rounded corners
- Card suits have distinct colors (hearts: red, diamonds: orange, spades: blue, clubs: green)

### Interactive Elements
- Print button triggers `window.print()`
- Copy Link button uses `navigator.clipboard.writeText()`

## Browser Compatibility

The site uses modern CSS features including:
- CSS custom properties
- CSS Grid
- Linear gradients
- System font stack

Ensure changes maintain compatibility with modern browsers.