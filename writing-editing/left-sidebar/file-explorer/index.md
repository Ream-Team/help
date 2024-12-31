---
title: File Explorer
layout: default
parent: Left Sidebar
grand_parent: Writing in Ream
nav_order: 1
---

# File Explorer Documentation

## Overview
The File Explorer is a core component that allows users to create, modify, and manage files within a project. This documentation covers the main features and functionality of the File Explorer interface.

## Basic Interface
![File Explorer Interface](5c0db99ccb.png)

The File Explorer is located in the left sidebar and displays all files in your project. The main interface includes:
- A "+" button for file operations
- A file listing area
- A "View deleted files" button at the bottom

## File Management

### Adding New Files
The "+" button provides three options:
1. Add a new file
2. Add a new folder
3. Upload files

#### File Upload Specifications
- Maximum file size: 50MB
- Supports all file types
- Upload interface appears in a modal window

### File Types

The system handles two main types of files:

#### 1. Editable Files
- Can be opened and modified in the editor
- Includes formats like:
  - LaTeX
  - Markdown
  - Plain text
- Size limitations apply for editability

#### 2. Static Files
- Read-only files
- Typically includes:
  - PNG images
  - PDF documents
  - Large text files
- Used for referencing within projects

## File Operations

### Context Menu
Right-clicking on a file reveals a context menu with the following options:
- Show history (editable files only)
- Rename
- Delete
- Download
- Copy file path

### File History

The file history feature provides:
- Timestamp of changes
- Author information
- Option to restore previous versions
- Version comparison capabilities

### Deleted Files Management
![Deleted Files Modal](7df94976d6.png)

- Access through "View deleted files" button
- Shows list of all deleted files
- Provides option to restore deleted files
- Displays deletion timestamp

## Integration Features

### AI Chat Integration
- Files can be referenced in the AI chat window
- Both static and editable files can be linked
- Provides additional context for AI assistance

### File Path Usage
- Copy file path feature assists in:
  - Including files as project inputs
  - Referencing graphics in documents
  - Creating file references in LaTeX projects

## Additional Notes
- File editability may be limited based on file size
- File paths can be used for cross-referencing within projects
- All operations maintain project history for tracking changes