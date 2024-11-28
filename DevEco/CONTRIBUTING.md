# Contributing to Portal Network Metadata

Thank you for your interest in contributing to the Portal Network Metadata repository! Contributions from the community are vital to making the Portal Network a rich, diverse, and valuable resource for developers and technologists worldwide. This document outlines the steps and guidelines for contributing.

---

## How You Can Contribute

1. **Add a Discord Server**

Help grow the Portal Network by adding a Discord server to the database. Follow the steps below to ensure your contribution meets our standards.

2. **Suggest Improvements**

Share ideas to improve the organization, structure, or functionality of the Portal Network.

3. **Update Metadata**

Ensure that server information (like descriptions or member counts) stays current by submitting updates.

---

## Contribution Workflow

### Step 1: Fork the Repository

1. Click the "Fork" button in the top-right corner of this repository.
2. Clone your forked repository to your local machine:

```bash
git clone https://github.com/your-username/Portal-Network-Metadata.git
cd Portal-Network-Metadata
```

### Step 2: Create a New Branch

Create a branch for your changes:

```bash
git checkout -b add-new-server
```

### Step 3: Make your Changes

- Add a new entry to the `servers.json` file located in the `/metadata/` directory.
- Follow this JSON structure:

```json
{
  "name": "Your Server Name",
  "invite": "https://discord.gg/yourinvitecode",
  "description": "A brief description of your community.",
  "tags": ["technology", "AI", "IoT"],
  "category": "Technology",
  "member_count": 1200
}
```

**Tips:**
- Use descriptive and accurate information.
- Verify that the invite link is active and does not expire.
- Assign relevant tags and a category.

### Step 4: Commit Your Changes
Commit your changes with a clear message:

```bash
git add metadata/servers.json
git commit -m "Added [Your Server Name] to servers.json"
```

### Step 5: Submit a Pull Request (PR)
1. Push your changes to your forked repository:

```bash
git push origin add-new-server
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

- All contributions must align with the Portal Network’s vision of openness, collaboration, and innovation.
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