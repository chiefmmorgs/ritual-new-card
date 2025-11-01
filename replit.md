# Ritual Lab ID Generator

## Overview
A single-page web application for creating customizable Ritual Lab ID cards. Users can personalize their ID cards with different roles, auras, profile pictures, and export them as PNG images.

## Project Architecture
- **Type**: Static HTML/CSS/JavaScript application
- **Dependencies**: html2canvas (loaded via CDN)
- **Storage**: Browser localStorage for state persistence
- **No backend required**

## Features
- Customizable ID cards with multiple role types (Ritualist, Mage, Ascendant, etc.)
- Aura effects (Harmonic, Cursed, Blessed, Initiate)
- Profile picture upload with dominant color extraction
- Export as PNG or copy to clipboard
- Serial number generation and tracking
- State persistence across sessions

## Technical Stack
- Pure HTML/CSS/JavaScript
- html2canvas library for image export
- No build process required

## Recent Changes
- 2025-11-01: Updated core role names (Developer → RittyBitty, Summoner → Radiant Ritualist, Zealot → Ritty)
- 2025-10-09: Initial setup in Replit environment
