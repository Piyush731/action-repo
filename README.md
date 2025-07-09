# Action Repo - GitHub Webhook Trigger Demo

This repo is part of the TechStaX Developer Assessment.

It is used to:
- Simulate GitHub events: `push`, `pull_request`
- Trigger a webhook to a Flask server
- Send event details like author, branch info, and timestamps

## Triggering Events
- Push to the `main` branch
- Create a pull request
- Merge a pull request

## Workflow
On each GitHub action, a webhook is sent to the Flask server (`webhook-repo`) which stores data to MongoDB.
