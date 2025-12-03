---
name: "🚀 Feature Request or 🛠️ Bug Fix"
about: Propose a new feature, improvement, or fix a bug for InsightLog.
title: "[TYPE]: Short description of the change (e.g., [FEAT]: Implement AI content summarization)"
labels: ['needs-review', 'enhancement']
assignees: []
---

## ✨ Pull Request Checklist

Please ensure you've completed the following tasks before submitting your pull request. This helps us review and merge your changes efficiently.

- [ ] I have read and followed the project's [CONTRIBUTING.md](https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension/.github/CONTRIBUTING.md) guidelines.
- [ ] I have checked for existing issues/PRs to avoid duplication.
- [ ] My code follows the established coding style and linting rules (enforced by Biome).
- [ ] I have added or updated unit (Vitest) and/or end-to-end (Playwright) tests for my changes, and all existing tests pass.
- [ ] I have updated the documentation (README.md, comments, etc.) where necessary.
- [ ] My changes are atomic and focused on a single concern.
- [ ] I have self-reviewed my own code thoroughly.
- [ ] I have tested my changes locally in a browser environment (Chrome/Firefox) and they work as expected.

## 📝 Description

Please provide a detailed description of the changes introduced in this pull request.
Explain the *why* behind your changes, not just the *what*.

*What does this PR accomplish?*
*Why was this change necessary?*
*How has this feature/fix been validated?*

## 🔗 Related Issues

Please link any related issues here. Use keywords like `Closes #ISSUE_NUMBER` or `Fixes #ISSUE_NUMBER` to automatically close issues when the PR is merged.

*   Closes #000 (if applicable)
*   Relates to #000 (if applicable)

## 🎯 Type of Change

Please mark with an `x` all the types of changes that apply to this PR:

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update
- [ ] Refactor (code restructuring, no new features or bug fixes)
- [ ] Chore (dependency updates, configuration changes, etc.)
- [ ] Tests (adding or updating tests)
- [ ] Performance improvement

## 🚀 How to Test

Provide detailed steps on how to test this change within the browser extension environment. Include any specific setup instructions or configurations needed.

1.  **Clone the repository:** `git clone https://github.com/chirag127/InsightLog-AI-Assisted-Journal-Capture-Browser-Extension.git`
2.  **Navigate to the project directory:** `cd InsightLog-AI-Assisted-Journal-Capture-Browser-Extension`
3.  **Install dependencies:** `npm install` (or `yarn install` / `pnpm install`)
4.  **Build the extension:** `npm run build` (or equivalent for development build)
5.  **Load unpacked extension:**
    *   Open your browser (Chrome/Firefox) and navigate to `chrome://extensions` (or `about:addons` for Firefox).
    *   Enable Developer mode.
    *   Click "Load unpacked" and select the `dist` (or `build`) folder.
6.  **Specific Test Steps:**
    *   [Detailed step 1]
    *   [Detailed step 2]
    *   ...

## 📸 Screenshots / Videos (Optional)

If your changes include UI modifications, please provide screenshots or a short video demonstrating the changes. This helps reviewers understand the impact quickly.

---
