# Contributing to Open Hardware Initiative

Thank you for your interest in contributing to the Open Hardware Initiative repository! Contributions from the community are vital to making the Open Hardware Initiative a rich, diverse, and valuable resource for developers and technologists worldwide. This document outlines the steps and guidelines for contributing.

---

## How You Can Contribute

1. **Suggest Improvements**

Share ideas to improve the organization, structure, or functionality of the repo.

2. **Update Documentation**

Ensure that repo documentation (like descriptions, documents, etc.) stay current.

---

## Contribution Workflow

### Step 1: Fork the Repository

1. Click the "Fork" button in the top-right corner of this repository.
2. Clone your forked repository to your local machine:

```bash
git clone https://github.com/your-username/devHW.git
cd devHW
git remote add [nick] https://github.com/ORIGINAL-username/devHW.git

```
The [nick] is a name you can remember because you will use it in some fetch and
  pull commands. For instance, hybotix uses "hybo" for the [nick].

### Step 2: Create a New Branch

Create a branch for your changes:

```bash
git branch [branch name]
git checkout -b [branch name]
```

This will checkout your branch set you up to edit on that branch of the repo.

### Step 3: Make your Changes

**Tips:**
- Use descriptive and accurate information.
- Verify that the invite link is active and does not expire.
- Assign relevant tags and a category.

### Step 4: Commit Your Changes
Commit your changes with a clear message:

```bash
git add [changed document or directory name]
git commit -m "Added [changed document or directory name], [explain what you did]"
```

Note: You can also do
```bash
git commit
```

and edit the commit message inside your default editor.

### Step 5: Submit a Pull Request (PR)
1. Push your changes to your forked repository:

```bash
git push origin [branch name]
```

2. Go to the original repository and click "Compare & Pull Request."
3. Write a brief description of your changes and submit the pull request (PR).

---

## Review Process

- A maintainer will review your PR for accuracy and compliance with the guidelines.
- Feedback may be provided; please address it promptly to help merge your PR.
- Once approved, your changes will be merged into the main repository.

---

## Guidelines 

### General Rules

- All contributions must align with the Open Hardware Initiative's  vision of openness, collaboration, and innovation.
- Ensure your metadata is accurate, concise, and respectful.
- Do not include offensive, discriminatory, or inappropriate content.

### Technical Rules

- JSON files must be valid and adhere to the specified structure.
- Test your changes locally (if applicable) to avoid errors.

---

## Code of Conduct

By contributing, you agree to abide by the Code of Conduct. Please ensure all interactions are respectful and inclusive.

---

## Questions or Help?

If you need assistance, feel free to:

- Open a GitHub Issue.
- Join the devEco Discord server and ask in the #portal channel.

Thank you for helping build the Portal Network. Together, we’re creating something incredible! 🚀
