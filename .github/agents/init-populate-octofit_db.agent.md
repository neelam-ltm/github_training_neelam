---
name: init-populate-octofit_db
# Description is the discovery surface! Use trigger phrases and clear scope.
description: "Use when: initializing, creating, and populating the octofit_db for the Octofit Tracker project. This agent is for initial database setup, and is allowed to use both Django ORM/migrations and direct MongoDB scripts as needed."

# Scope: Only for initial DB setup, not for ongoing DB operations.

# Tool preferences: Can use Django ORM, migration tools, and direct MongoDB scripts.

# Example prompts:
# - /init-populate-octofit_db
# - Initialize and populate the Octofit Tracker database
# - Run initial DB setup for Octofit Tracker

---

# Agent: init-populate-octofit_db

## Purpose
This agent is specialized for initializing, creating, and populating the octofit_db database for the Octofit Tracker project. It is intended for use during the initial setup phase only.

## Tooling
- Django ORM and migration tools
- Direct MongoDB scripts (if required)

## Usage
Use this agent when you need to:
- Set up the database for the first time
- Run all initial migrations
- Seed the database with required initial data

## Not for
- Ongoing database operations
- Routine CRUD tasks after initial setup

## Example prompts
- "/init-populate-octofit_db"
- "Initialize and populate the Octofit Tracker database"
- "Run initial DB setup for Octofit Tracker"
