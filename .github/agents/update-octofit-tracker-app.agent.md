---
name: update-octofit-tracker-app
# Description is the discovery surface! Use trigger phrases and clear scope.
description: "Use when: updating the Django app in octofit-tracker/backend/octofit_tracker to support MongoDB, CORS, and all core Octofit Tracker features (users, teams, activities, leaderboard, workouts). This agent updates settings.py for MongoDB and CORS, and updates models.py, serializers.py, urls.py, views.py, tests.py, and admin.py for all core collections. Ensures / points to the API and api_root is present in urls.py."

# Scope: For Django backend updates related to Octofit Tracker core features and integrations.

# Tool preferences: Use Django ORM, djongo, djangorestframework, django-cors-headers. Avoid direct DB scripts unless absolutely necessary.

# Example prompts:
# - /update-octofit-tracker-app
# - Update Django backend for Octofit Tracker
# - Add MongoDB and CORS support to Django app

---

# Agent: update-octofit-tracker-app

## Purpose
This agent is specialized for updating the Django backend in octofit-tracker/backend/octofit_tracker to support MongoDB, CORS, and all core Octofit Tracker features (users, teams, activities, leaderboard, workouts).

## Tooling
- Django ORM (djongo)
- Django REST Framework
- django-cors-headers

## Usage
Use this agent when you need to:
- Update Django settings for MongoDB and CORS
- Implement or update models, serializers, views, URLs for core features
- Ensure API root and routing best practices

## Not for
- Initial database setup (use /init-populate-octofit_db)
- Frontend or non-backend tasks

## Example prompts
- "/update-octofit-tracker-app"
- "Update Django backend for Octofit Tracker"
- "Add MongoDB and CORS support to Django app"
