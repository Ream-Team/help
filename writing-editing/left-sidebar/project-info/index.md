---
title: Project Info
layout: default
parent: Left Sidebar
grand_parent: Writing in Ream
nav_order: 5
---

# Project Info

This documentation covers the project information settings and management options available in the LaTeX editor.

## PDF Compiler Engine Selection

The editor provides three different PDF compiler engine options through a dropdown menu:

![Project Info Settings Panel](e51acccefc.png)

### Available Compiler Engines

#### PDF LaTeX (Default)
- Fast and reliable default choice
- Good support for basic LaTeX features
- Recommended for most standard documents

#### XeTeX
- Enhanced Unicode support
- Better handling of modern fonts
- Recommended for:
  - Documents with non-Latin scripts
  - Projects requiring custom fonts

#### LuaTeX
- Supports Lua scripting capabilities
- Handles modern typography features
- Best for:
  - Documents containing emojis
  - Projects requiring Lua scripting
  - Non-standard typography needs
- Note: Slower compilation compared to PDF LaTeX

## Project Management Features

### Project Completion Status
The "Mark as Completed" button allows you to:
- Toggle the completion status of your current project
- Easily track project progress from the homepage
- Filter between in-progress and completed projects

### Project Export
The "Download Project as .zip" button enables you to:
- Download all project source files in a compressed format
- Back up your work locally
- Share the complete project with others

## Best Practices
- Choose PDF LaTeX for standard documents unless you specifically need features from other engines
- Use XeTeX when working with non-Latin scripts or custom fonts
- Select LuaTeX only when necessary for special typography or Lua scripting needs
- Regularly mark projects as completed to maintain an organized workspace
- Download project archives for backup purposes or when sharing with collaborators
