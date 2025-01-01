---
title: Collaborator Management
layout: default
parent: Left Sidebar
grand_parent: Writing in Ream
nav_order: 3
---

# Collaborator Management

## Overview

The Collaborator Management panel in the left sidebar allows you to control access and permissions within your project. You can manage team members, set permission levels, and oversee project access all from one centralized location.

## How to Access

The Collaborator Management panel is located in the left sidebar of the Ream interface:

![Collaborator management panel](2130c9fe1e.png)

## Available Features

### Viewing Collaborators
- View a list of all current collaborators
- Access collaborator details (username and email) by selecting a collaborator
- Monitor permission levels for each team member

### Permission Roles

The system provides three permission levels:

#### Viewer
- Can view file contents
- Cannot edit files
- Cannot delete or rename the project

#### Editor
- Includes all Viewer permissions
- Can edit file contents
- Can leave suggestions
- Cannot rename or delete the project

#### Admin
- Includes all Editor permissions
- Can rename the project
- Can delete the project
- Can modify other collaborators' permissions

### Adding Collaborators

To add a new collaborator:

1. Click the "Add Collaborator" button in the collaborator panel
2. In the modal that appears, enter:
   - Collaborator's email address
   - Desired permission role (Viewer, Editor, or Admin)

### Managing Permissions

Admins can modify permissions by:
1. Selecting the collaborator
2. Changing their role to Viewer, Editor, or Admin as needed

Note: Only users with Admin permissions can modify other users' permission levels.

## Best Practices

- Regularly review collaborator access levels
- Maintain at least two admin users for backup access
- Remove inactive collaborators promptly
- Document permission changes for team transparency

## Project Leaving Rules

Important restrictions apply when attempting to leave a project:

- Regular collaborators can leave at any time
- Admins can leave only if there is at least one other admin in the project
- The last remaining admin cannot leave the project
  - In this case, they should delete the project instead if they wish to end their involvement