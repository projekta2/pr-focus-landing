# Contributing to PR Focus

Thanks for your interest in contributing! This document outlines how to get started.

## Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/). By participating, you agree to uphold this code.

## Getting Started

1. Fork the repository.
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/pr-focus-landing.git`
3. Install dependencies (if any). PR Focus is a Chrome extension with no external dependencies beyond the Chrome APIs.
4. Load the extension in Chrome:
   - Go to `chrome://extensions`
   - Enable "Developer mode"
   - Click "Load unpacked" and select the folder containing `manifest.json`

## Development Workflow

- Make changes in a feature branch: `git checkout -b feature/my-feature`
- Test thoroughly: open the popup, test on real PRs (use a test GitHub account).
- Commit with clear messages.
- Push and open a PR against `main`.

## Reporting Issues

- Use the issue template.
- Include steps to reproduce and screenshots if possible.

## Feature Requests

- Open an issue with the `enhancement` label.
- Describe the problem you're solving, not just the feature you want.

## Code Style

- Use 2 spaces for indentation.
- Use meaningful variable names.
- Comment complex logic.

## Submitting a PR

1. Link the issue you're solving (e.g., `Fixes #123`).
2. Write a clear description of your changes.
3. Ensure the extension still works after your changes.
4. Wait for review.

## Need Help?

Open a discussion issue with the `question` label.

---

Thanks for being here! 🚀
