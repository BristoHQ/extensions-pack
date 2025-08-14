# 🤝 Contributing to BristoHQ VSCode Extension Packs

Thank you for your interest in contributing to our VS Code extension packs! We welcome contributions from the community and appreciate your help in making these extension packs even better.

## 📋 Table of Contents

- [Getting Started](#getting-started)
- [Ways to Contribute](#ways-to-contribute)
- [Suggesting New Extensions](#suggesting-new-extensions)
- [Proposing New Extension Packs](#proposing-new-extension-packs)
- [Improving Documentation](#improving-documentation)
- [Reporting Issues](#reporting-issues)
- [Development Setup](#development-setup)
- [Submission Guidelines](#submission-guidelines)
- [Code of Conduct](#code-of-conduct)

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/BristoHQ/extensions-pack.git
   cd extensions-pack
   ```
3. **Create a new branch** for your contribution:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 🛠 Ways to Contribute

### 1. Suggesting New Extensions

If you know of a great extension that would fit well in one of our existing packs:

1. **Check existing extensions** in the relevant pack's `package.json`
2. **Open an issue** with the template:
   - Extension name and publisher
   - Why it should be included
   - Which pack it belongs to
   - Brief description of its benefits

### 2. Proposing New Extension Packs

Have an idea for a completely new extension pack? We'd love to hear it!

**Requirements for new packs:**

- Must serve a specific developer audience or use case
- Should include 5-15 carefully curated extensions
- Must not overlap significantly with existing packs
- Should follow our naming convention: `[Technology/Use Case] [Type] Pack`

**Proposal should include:**

- Target audience and use case
- List of proposed extensions with justifications
- Pack name and description
- Icon suggestion (optional)

### 3. Improving Documentation

Help us improve our documentation by:

- Fixing typos or grammar errors
- Adding clearer explanations
- Updating outdated information
- Translating documentation (future feature)
- Adding usage examples

### 4. Reporting Issues

Found a bug or have a suggestion? Please check if an issue already exists before creating a new one.

**For bug reports, include:**

- VS Code version
- Operating system
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots (if applicable)

## 📝 Suggesting New Extensions

When suggesting extensions, consider:

### ✅ Good Extensions to Suggest:

- **Actively maintained** (updated within the last year)
- **High quality** (good ratings and reviews)
- **Widely used** by the target community
- **Lightweight** (doesn't significantly slow down VS Code)
- **Compatible** with VS Code's minimum version requirement
- **Unique functionality** not covered by existing extensions

### ❌ Extensions to Avoid:

- Deprecated or unmaintained extensions
- Extensions with known security issues
- Overly niche extensions used by very few developers
- Extensions that duplicate functionality of included extensions
- Extensions that require external dependencies not commonly available

## 📋 Submission Guidelines

### Pull Request Process:

1. **Ensure your branch is up to date**:

   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Make your changes** following our guidelines

3. **Test thoroughly** - install and test the pack locally

4. **Update version numbers** in `package.json` if adding/removing extensions

5. **Write a clear commit message**:

   ```
   feat: add [extension-name] to [pack-name]

   - Adds functionality for [specific use case]
   - Improves developer experience for [target audience]
   - Closes #[issue-number]
   ```

6. **Create a pull request** with:
   - Clear title and description
   - Reference to related issues
   - Screenshots (if UI changes)
   - Testing instructions

### Review Process:

- All PRs require review from maintainers
- We may request changes or ask questions
- Once approved, we'll merge and publish updates

## 📊 Extension Pack Guidelines

### Quality Standards:

- **Maximum 15 extensions** per pack (to avoid bloat)
- **Minimum 5 extensions** per pack (to provide value)
- All extensions must be **actively maintained**
- Extensions should have **good community ratings** (4+ stars preferred)
- Must work with **VS Code minimum version** specified in `package.json`

### Naming Conventions:

- Pack names should be descriptive and specific
- Use title case for display names
- Keep descriptions under 200 characters
- Include relevant keywords for discoverability

## 📞 Getting Help

Need help or have questions?

- **Create an issue** for questions about contributing
- **Join discussions** in existing issues
- **Email us** at [contact@bristohq.me](mailto:contact@bristohq.me)
- **Check our website** at [bristohq.me](https://bristohq.me)

## 🎉 Recognition

Contributors will be:

- Listed in our `CONTRIBUTORS.md` file
- Mentioned in release notes for significant contributions
- Given credit in pack descriptions where appropriate

## 📜 Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inclusive experience for everyone, regardless of background or identity.

### Expected Behavior:

- Be respectful and professional
- Use inclusive language
- Accept constructive feedback gracefully
- Focus on what's best for the community
- Show empathy towards others

### Unacceptable Behavior:

- Harassment or discrimination of any kind
- Offensive comments or personal attacks
- Spam or self-promotion unrelated to the project
- Publishing others' private information

### Enforcement:

Violations can be reported to [contact@bristohq.me](mailto:contact@bristohq.me). All complaints will be reviewed and investigated promptly and fairly.

---

## 🙏 Thank You!

Your contributions make these extension packs better for developers worldwide. Whether you're fixing a typo, suggesting an extension, or proposing a whole new pack, every contribution matters!

**Happy coding!** 🚀

---

_This project is maintained by [BristoHQ](https://bristohq.me) and is open source under the MIT License._
