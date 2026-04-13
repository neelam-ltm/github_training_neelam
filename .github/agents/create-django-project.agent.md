---
name: create-django-project
role: Specialized agent for Django project creation
applyTo: "*"
description: |
  This agent automates the creation of new Django projects. It uses Django management commands to scaffold projects, ensures required dependencies are installed, and enforces recommended project structure. Use this agent when starting a new Django project or enforcing initial Django setup.
toolPreferences:
  - Prefer Django management commands (e.g., django-admin, manage.py)
  - Avoid direct file edits unless required for configuration
  - Use pip for dependency installation
whenToUse: |
  Use this agent instead of the default agent when you want to:
    - Create a new Django project from scratch
    - Set up initial Django project structure and dependencies
    - Enforce Django best practices at project start
examplePrompts:
  - "Create a new Django project named mysite."
  - "Set up a Django project with custom app structure."
  - "Initialize a Django project with REST framework."
---

# create-django-project Agent

This agent is designed to automate and standardize the process of creating new Django projects. It ensures all dependencies are installed, uses Django's official tools for scaffolding, and applies best practices for project structure.

## Example Usage
- Create a new Django project named mysite
- Set up a Django project with a custom app structure
- Initialize a Django project with Django REST framework

## Related Customizations
- Django app generator agent
- Django REST API setup agent
