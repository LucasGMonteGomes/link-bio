# Contributing to LinkBio

Thank you for your interest in contributing to this project.

We welcome improvements, fixes, and thoughtful suggestions that help make the profile page clearer, more accessible, and more useful.

## How to contribute

### 1. Open or review an issue

Before making changes, check if there is an existing issue related to your idea or bug report.

### 2. Fork the project

```bash
git clone https://github.com/LucasGMonteGomes/link-bio.git
cd link-bio
```

### 3. Create a branch

Use a clear and descriptive branch name:

```bash
git checkout -b feature/your-change
```

### 4. Make your changes

Keep edits focused and easy to review. For this project, common areas are:

- `src/index.html`
- `src/projetos.html`
- `src/style.css`
- images/assets under `src/assets/`

### 5. Validate locally

Install dependencies:

```bash
npm install
```

Run the app:

```bash
npm run dev
```

Check that the project still builds correctly:

```bash
npm run build
```

## Pull request guidelines

- Keep pull requests focused on a single change or improvement
- Include a clear description of what changed and why
- Mention any relevant screenshots if the design is affected
- Ensure the project still builds without errors
- Follow the existing code style and project structure

## Code quality expectations

- Use semantic, meaningful names for new classes or sections
- Maintain the project's visual simplicity and responsiveness
- Avoid unnecessary dependencies or over-engineering
- Preserve the accessibility of links and content

## Reporting issues

Please open a GitHub issue with:

- a clear description of the problem
- steps to reproduce it
- expected behavior
- actual behavior
- screenshots if applicable

## Community standards

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md) to keep the project respectful and welcoming.
