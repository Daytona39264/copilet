# Copilot Instructions for AI Coding Agents

## Project Overview
This repository demonstrates how to use GitHub Copilot in VS Code and Codespaces, focusing on JavaScript workflows. The main files are:
- `skills.js`: Example JavaScript file for Copilot suggestions
- `member.js`: (to be created) For Copilot multi-suggestion activity
- `README.md`: Step-by-step instructions for using Copilot and Git workflows

## Architecture & Workflow
- **Single-folder structure**: All code and documentation are in the root directory.
- **No build system**: There is no package.json, build scripts, or test framework. All code is plain JavaScript.
- **Manual file creation**: New files (e.g., `member.js`) are created manually as part of Copilot learning exercises.

## Developer Workflow
- **Git operations**: Use `git pull`, `git add`, `git commit`, and `git push` for version control. See `README.md` for exact commands.
- **Copilot usage**: Follow the steps in `README.md` to trigger Copilot suggestions and use the Completions Panel for multi-suggestion workflows.
- **No automated tests**: There are no test scripts or CI/CD pipelines. All validation is manual.

## Project-Specific Conventions
- **Function naming**: Functions follow the pattern `skillsMember` or similar, as shown in the Copilot activities.
- **Commit messages**: Use descriptive commit messages like "Copilot second commit" as suggested in the workflow.
- **Documentation-driven**: The `README.md` is the primary source of truth for workflow and conventions.

## Integration Points
- **Copilot integration**: The project is designed for Copilot demonstration and does not integrate with external APIs or services.
- **No external dependencies**: No npm modules or third-party libraries are used.

## Key Files
- `README.md`: Contains all instructions for using Copilot and managing code in this repository.
- `skills.js`: Example file for Copilot suggestions.
- `member.js`: To be created as part of the Copilot workflow.

## Example Workflow
1. Create `member.js` and add a function header (see `README.md`).
2. Use Copilot to generate suggestions and accept one.
3. Stage, commit, and push changes using the provided git commands.

## Guidance for AI Agents
- Prioritize following the workflow in `README.md`.
- Do not introduce build tools, test frameworks, or external dependencies unless explicitly requested.
- Keep all code and documentation in the root directory.
- Use clear, descriptive commit messages.
- Reference `README.md` for any workflow or convention questions.
