# AI Components Index

This document serves as a comprehensive index of all AI-related components in this repository.

## GitHub Copilot Configurations

| Component | Description | Documentation |
|-----------|-------------|---------------|
| [.github/copilot/config.yml](/.github/copilot/config.yml) | Main configuration file for GitHub Copilot | [GitHub Copilot Overview](https://docs.github.com/en/copilot/overview-of-github-copilot) |
| [.github/copilot/chat-config.yml](/.github/copilot/chat-config.yml) | Configuration for GitHub Copilot Chat | [GitHub Copilot Chat](https://docs.github.com/en/copilot/github-copilot-chat/about-github-copilot-chat) |
| [.github/copilot/cli-config.yml](/.github/copilot/cli-config.yml) | Configuration for GitHub Copilot CLI | [GitHub Copilot in the CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli/about-github-copilot-in-the-cli) |
| [.github/copilot/environment-variables.json](/.github/copilot/environment-variables.json) | Environment variables for Copilot agent | [Copilot Agent Environment](https://docs.github.com/en/copilot/customizing-copilot/customizing-the-development-environment-for-copilot-coding-agent) |
| [.github/copilot/commands.json](/.github/copilot/commands.json) | Custom commands for Copilot agent | [Copilot Agent Commands](https://docs.github.com/en/copilot/customizing-copilot/customizing-the-development-environment-for-copilot-coding-agent) |

## GitHub Workflows

| Workflow | Description | Documentation |
|----------|-------------|---------------|
| [.github/workflows/copilot-for-issues.yml](/.github/workflows/copilot-for-issues.yml) | Workflow for GitHub Copilot for Issues integration | [GitHub Copilot for Issues](https://docs.github.com/en/copilot/github-copilot-for-issues/about-github-copilot-for-issues) |
| [.github/workflows/copilot-pr-feedback.yml](/.github/workflows/copilot-pr-feedback.yml) | Workflow for GitHub Copilot PR feedback (currently disabled) | [GitHub Copilot for Pull Requests](https://docs.github.com/en/copilot/github-copilot-for-pull-requests/about-github-copilot-for-pull-requests) |

## Repository Configuration

| File | Description | Documentation |
|------|-------------|---------------|
| [.github/CODEOWNERS](/.github/CODEOWNERS) | Defines ownership for Copilot-related files | [About CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) |
| [.github/copilot-instructions.md](/.github/copilot-instructions.md) | Custom instructions for GitHub Copilot | [Repository Custom Instructions](https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot) |

## Documentation

| Document | Description | Documentation |
|----------|-------------|---------------|
| [COPILOT.md](/COPILOT.md) | User guide for GitHub Copilot features in this repository | [GitHub Copilot Documentation](https://docs.github.com/en/copilot) |
| [docs/COPILOT_IMPLEMENTATION.md](/docs/COPILOT_IMPLEMENTATION.md) | Implementation details for GitHub Copilot integration | [GitHub Copilot Documentation](https://docs.github.com/en/copilot) |

## Removed Components

The following components were removed as they could not be referenced to official documentation:

- `.github/copilot/workspace-config.yml`
- `.github/copilot/advanced-config.yml`
- "GitHub Copilot Workspace" feature

These files or features contained custom configurations or references that are not currently documented in the official GitHub Copilot documentation.