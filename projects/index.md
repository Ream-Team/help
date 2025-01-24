---
title: Projects
layout: default
nav_order: 4
---

# Projects

This page describes how to work within a Project.

## Supported Upload File Types

Files that are imported when creating a new project or uploaded from within an existing project are subject to certain limits. 

Editable file types are typically text files under 7MB in size. Text files over 7MB will be viewable as read-only.

Image file types must have one of the following extensions:
- `.png`
- `.jpg`
- `.jpeg`
- `.gif`
- `.bmp`
- `.tiff`
- `.webp`

PDF file types must have the `.pdf` file extension.

## Searching across files

You can search for text content across files by clicking on the Search panel in the sidebar. You can also search by filename by opening the command palette, which is accessible by hitting `cmd+shift+p`.

## Compiler Engines

There are three compiler engines the user can select from the Settings panel of the left sidebar.

### PDF LaTeX (Default)
- Fast and reliable default choice
- Good support for basic LaTeX features
- Recommended for most standard documents

### XeTeX
- Enhanced Unicode support
- Better handling of modern fonts
- Recommended for:
  - Documents with non-Latin scripts
  - Projects requiring custom fonts

### LuaTeX
- Supports Lua scripting capabilities
- Handles modern typography features
- Best for:
  - Documents containing emojis
  - Projects requiring Lua scripting
  - Non-standard typography needs
- Note: Slower compilation compared to PDF LaTeX
