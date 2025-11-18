# mcpmark-cicd

This repository contains the CI/CD pipeline for the mcpmark project.

## Issue Management

This repository uses an automated issue management workflow to triage and process issues. The workflow automatically:

- Applies category labels (bug, epic, maintenance)
- Assigns priority labels (critical, high, medium, low)
- Creates sub-tasks for epic issues
- Posts auto-responses based on issue type
- Sets milestones for high priority issues

For more information, see the [Issue Management Automation Workflow](.github/workflows/issue-automation.yml).