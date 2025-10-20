# Contributing to AI4HPC

Thank you for your interest in contributing to AI4HPC! We welcome contributions from researchers, developers, and practitioners of all experience levels. This document outlines how you can get involved.

## Code of Conduct

Please note that this project is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold these standards and help us maintain a welcoming, inclusive community.

## Getting Started

### 1. Report Bugs or Suggest Features

Found a bug? Have an idea for improvement? Open an **Issue**:

1. Go to the relevant repository's **Issues** tab.
2. Check existing issues to avoid duplicates.
3. Click **New Issue** and provide:
   - **Clear title:** Briefly describe the bug or feature.
   - **Description:** Explain the problem or suggestion in detail.
   - **Steps to reproduce** (for bugs): How can we reproduce the issue?
   - **Expected vs. actual behavior** (for bugs): What should happen vs. what happens?
   - **Relevant context:** OS, Python/compiler version, dependencies, etc.
   - **Labels:** Tag as `bug`, `enhancement`, `documentation`, etc.

### 2. Contribute Code

We use a **Fork and Pull Request** workflow:

#### Step 1: Fork and Clone
```bash
# Fork the repository on GitHub (click the "Fork" button)
git clone https://github.com/YOUR-USERNAME/REPOSITORY.git
cd REPOSITORY
git remote add upstream https://github.com/AI4HPC/REPOSITORY.git
```

#### Step 2: Create a Branch
```bash
# Update your local main branch
git fetch upstream
git checkout main
git merge upstream/main

# Create a feature branch with a descriptive name
git checkout -b feature/your-feature-name
# or for bug fixes:
git checkout -b fix/issue-description
```

#### Step 3: Make Changes
- Write clear, well-commented code.
- Follow the project's coding style and conventions.
- Include tests for new functionality.
- Update documentation as needed.

#### Step 4: Commit
```bash
# Make atomic commits with clear messages
git add .
git commit -m "Brief description of changes

More detailed explanation if needed. Reference issues with #ISSUE_NUMBER."
```

#### Step 5: Push and Open a Pull Request
```bash
# Push your branch
git push origin feature/your-feature-name

# Go to GitHub and open a Pull Request
# - Provide a clear title and description
# - Reference related issues: "Fixes #123" or "Related to #456"
# - Explain the rationale and scope of changes
```

#### Step 6: Address Review
- Respond to feedback from maintainers.
- Make requested changes and push updates to your branch.
- We'll merge once approved.

### 3. Propose New Projects or Papers

Have a research project or paper to share? Propose it via an **Issue**:

1. Go to the organization's main repository or relevant sub-repository.
2. Open a **New Issue** with the title: **`[Proposal] Project/Paper Title`**
3. Use the **Proposal** template and include:
   - **Type:** Is this a project, paper, or resource?
   - **Title and description:** What is it about?
   - **Relevance:** How does it connect to AI and HPC?
   - **Repository/Link:** Where can we find it? (GitHub repo, arXiv, etc.)
   - **Maintainer:** Who will maintain/support this (if applicable)?
   - **Any special considerations:** License, dependencies, etc.

The community will review and discuss your proposal. Once approved, we'll help integrate it into the appropriate collection.

## Contribution Guidelines

### Code Quality
- Follow PEP 8 (Python) or your language's style guide.
- Write meaningful comments and docstrings.
- Test your code thoroughly before submitting.
- Aim for clear, readable code over clever code.

### Documentation
- Update README files if your changes affect functionality.
- Document new features and APIs.
- Include examples where helpful.

### Commit Messages
- Use clear, imperative language: `Add feature X` not `Added feature X`.
- Reference issues: `Fixes #123`.
- Keep the first line under 72 characters.

### Pull Request Reviews
- Expect constructive feedback—it's not personal!
- We value questions and collaboration.
- Review feedback is mandatory; all contributions go through peer review.

## Reporting Issues

When reporting issues, please provide:
- **Environment:** OS, relevant software versions.
- **Minimal reproducible example:** Code or steps that demonstrate the issue.
- **Error messages:** Full traceback or error output.
- **Context:** What were you trying to do?

## Questions or Need Help?

- Open a **Discussion** if you have questions.
- Tag maintainers if you need specific guidance.
- Reach out on GitHub Issues—we're here to help!

## Recognition

Contributors are recognized in repository README files and release notes. Thank you for helping advance the AI4HPC community!

---

**Happy contributing!** We look forward to your contributions to the future of AI and HPC.
