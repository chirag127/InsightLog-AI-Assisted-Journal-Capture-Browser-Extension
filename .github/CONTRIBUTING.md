# Contributing to InsightLog-AI-Assisted-Journal-Capture-Browser-Extension

We are thrilled you're considering contributing to **InsightLog-AI-Assisted-Journal-Capture-Browser-Extension**! Your efforts help us build a more powerful, insightful, and user-friendly knowledge capture tool. This document outlines the guidelines for contributing to ensure a smooth and effective collaboration for everyone.

Please note that this project adheres to the [Code of Conduct](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension/blob/main/.github/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## 🚀 Getting Started

To get started with contributing, follow these steps:

1.  **Fork the Repository:** Click the "Fork" button at the top right of the [repository page](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension).
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension.git
    cd InsightLog-AI-Assisted-Journal-Capture-Browser-Extension
    
3.  **Install Dependencies:** This project uses `pnpm` for package management. If you don't have it, install it globally:
    bash
    npm install -g pnpm
    pnpm install
    
4.  **Start Development Server:**
    bash
    pnpm dev
    
    This will typically start a development server and build the extension in watch mode, allowing for live reloading during development. Refer to the `package.json` scripts for more specific commands.

## 🌿 Branching Strategy

We use a feature-branch workflow:

*   **`main`**: This branch always contains the latest stable, production-ready release. Direct commits are strictly forbidden.
*   **`develop`**: This branch is where all active development and integration happens. All feature branches should be merged into `develop`.
*   **Feature Branches (`feature/your-feature-name`)**: Create a new branch from `develop` for each new feature or significant enhancement.
*   **Bugfix Branches (`bugfix/issue-number-short-description`)**: Create a new branch from `develop` for each bug fix.

Always ensure your `develop` branch is up-to-date with the upstream `develop` before creating new branches or pushing changes.

## 💬 Commit Message Guidelines

We enforce [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for clear, descriptive commit messages. This helps with automatic changelog generation and understanding the history.

**Examples:**
*   `feat: add content summarization feature`
*   `fix(background): resolve memory leak in history capture`
*   `docs: update contributing guidelines`
*   `chore: upgrade WXT to v0.10`

## 📦 Pull Request Process

When you're ready to submit your changes, please follow these steps:

1.  **Ensure Quality:**
    *   Run linting and formatting checks (`pnpm lint`, `pnpm format`).
    *   Ensure all tests pass (`pnpm test`).
    *   Verify the extension builds correctly and functions as expected in a browser.
2.  **Push Your Branch:**
    bash
    git push origin your-feature-branch
    
3.  **Open a Pull Request:**
    *   Go to the [InsightLog-AI-Assisted-Journal-Capture-Browser-Extension repository](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension) on GitHub.
    *   Click "New pull request" and select your branch.
    *   **Target Branch:** Ensure your PR is targeting the `develop` branch.
    *   **Description:** Provide a clear, concise description of your changes.
        *   Reference any related issues (e.g., `Fixes #123`, `Closes #456`).
        *   Include screenshots or GIFs for UI changes.
        *   Explain the "why" behind your changes, not just the "what."
4.  **Address Feedback:** Our team will review your PR. Be responsive to feedback and make necessary adjustments. Once approved, your changes will be merged!

## 🛠 Development Workflow & Standards

### Tech Stack
This project is built as a modern browser extension using:
*   **Framework:** WXT (for building cross-browser extensions)
*   **Language:** TypeScript (for type safety and maintainability)
*   **Bundler:** Vite (for fast development and optimized builds)
*   **Styling:** TailwindCSS (for utility-first CSS, if applicable)

### Linting & Formatting
We use [Biome](https://biomejs.dev/) for blazing-fast linting and formatting.
*   **Lint & Format Check:** `pnpm lint`
*   **Auto-fix Formatting:** `pnpm format` (this will automatically fix most formatting issues)

### Testing
We strive for comprehensive test coverage to ensure reliability.
*   **Unit & Integration Tests:** Powered by [Vitest](https://vitest.dev/).
    *   Run all tests: `pnpm test`
    *   Run tests in watch mode: `pnpm test:watch`
*   **End-to-End (E2E) Tests:** Powered by [Playwright](https://playwright.dev/).
    *   Run E2E tests: `pnpm test:e2e`

### Architecture Principles
We adhere to established architectural principles such as:
*   **SOLID Principles:** For maintainable and scalable code.
*   **DRY (Don't Repeat Yourself):** To avoid redundancy.
*   **YAGNI (You Aren't Gonna Need It):** To prevent over-engineering.
*   **Feature-Sliced Design (FSD):** For clear separation of concerns in the extension's codebase (e.g., `app`, `entities`, `features`, `pages`, `shared`, `widgets`).

## 🐞 Reporting Bugs & Requesting Features

*   **Bugs:** If you encounter a bug, please open an issue using the [Bug Report template](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension/issues/new?assignees=&labels=bug&projects=&template=bug_report.md&title=%5BBug%5D%3A+). Provide clear steps to reproduce, expected behavior, and actual behavior.
*   **Feature Requests:** Have a great idea for a new feature? Open an issue using the [Feature Request template](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension/issues/new?assignees=&labels=enhancement&projects=&template=feature_request.md&title=%5BFeature%5D%3A+). Describe the feature, its benefits, and potential use cases.

## 🛡 Security Vulnerabilities

If you discover a security vulnerability, please report it responsibly by following our [Security Policy](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension/blob/main/.github/SECURITY.md). Do not open a public issue.

---

Thank you for helping to improve **InsightLog-AI-Assisted-Journal-Capture-Browser-Extension**! We appreciate your contributions.
