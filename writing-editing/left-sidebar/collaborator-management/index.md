---
title: Collaborator Management
layout: default
parent: Left Sidebar
grand_parent: Writing in Ream
nav_order: 3
---

# Collaborator Management

The collaborator management panel provides functionality for controlling access and permissions within a project. This documentation covers how to manage collaborators, including adding new users and understanding the different permission roles.

## Viewing Collaborators

The collaborator management panel appears in the left sidebar of the interface:

![Collaborator management panel](2130c9fe1e.png)

From this panel, you can:
- View existing collaborators
- See collaborator details (username and email) by clicking on a collaborator
- Add new collaborators
- Manage permissions

## Permission Roles

The system offers three permission levels, listed from least to most permissive:

### Viewer
- Can view file contents
- Cannot edit files
- Cannot delete or rename the project

### Editor
- Includes all Viewer permissions
- Can edit file contents
- Can leave suggestions
- Cannot rename or delete the project

### Admin
- Includes all Editor permissions
- Can rename the project
- Can delete the project
- Can modify other collaborators' permissions

## Adding Collaborators

To add a new collaborator:

1. Click the "Add Collaborator" button in the collaborator panel
2. In the modal that appears, enter:
   - Collaborator's email address
   - Desired permission role (Viewer, Editor, or Admin)

## Project Leaving Rules

Important restrictions apply when attempting to leave a project:

- Regular collaborators can leave at any time
- Admins can leave only if there is at least one other admin in the project
- The last remaining admin cannot leave the project
  - In this case, they should delete the project instead if they wish to end their involvement

## Managing Permissions

Admins can modify other collaborators' permission levels at any time by:
1. Selecting the collaborator
2. Changing their role to Viewer, Editor, or Admin as needed

Note: Only users with Admin permissions can modify other users' permission levels.