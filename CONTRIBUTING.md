# Contributing to HWN

Thank you for your interest in contributing to **HWN — Hand Written Notes**.

Contributions are welcome in both **study content** and **software development**. Please follow the guidelines below so the project remains organized, maintainable, and useful for students.

## Code of Conduct

By participating in this project, you agree to follow the project's [Code of Conduct](CODE_OF_CONDUCT.md).

Be respectful, constructive, and welcoming to other contributors.

## Ways to Contribute

### 1. Notes and Study Content

You can contribute by:

- Adding useful B.Tech handwritten notes
- Improving note titles, descriptions, or categorization
- Adding missing subjects, chapters, or topics
- Reporting incorrect or broken note links
- Improving the organization of existing resources

Only contribute material that you have the right to share.

Do not upload copyrighted material that you do not have permission to redistribute.

### 2. Code and Technical Improvements

You can contribute by:

- Fixing bugs
- Improving the UI
- Improving responsive behavior
- Improving accessibility
- Improving performance
- Improving routing
- Improving note/PDF/image previews
- Improving project structure
- Updating dependencies responsibly
- Improving documentation

## Getting Started

### Fork the repository

Fork the repository on GitHub and clone your fork:

```bash
git clone https://github.com/<your-username>/HWN.git
cd HWN
```

Add the upstream repository:

```bash
git remote add upstream https://github.com/AmitMaurya270708/HWN.git
```

### Install dependencies

```bash
npm install
```

### Start development

```bash
npm run dev
```

Make your changes and test them locally before opening a pull request.

## Branches

Create a focused branch for your work.

Examples:

```bash
git checkout -b feat/add-subject-navigation
git checkout -b fix/pdf-preview
git checkout -b docs/update-readme
```

Avoid putting unrelated changes into the same branch.

## Commit Convention

This project follows the **Conventional Commits** style.

Use a commit type followed by a short description.

Examples:

```text
feat: add semester navigation
fix: correct broken PDF route
docs: update contribution guide
refactor: simplify note card component
style: improve mobile spacing
perf: optimize note loading
chore: update dependencies
```

Keep commits focused and descriptive.

## Pull Request Process

Before opening a pull request:

1. Make sure your branch contains only the intended changes.
2. Run the project locally.
3. Check the affected routes.
4. Test PDF/image previews if your changes affect them.
5. Run the production build:

```bash
npm run build
```

6. Update documentation when necessary.
7. Push your branch to your fork.
8. Open a pull request against the main repository.

### Pull Request Description

A useful pull request should explain:

- What changed
- Why it changed
- How it was tested
- Any known limitations

For UI changes, screenshots are helpful.

## Style Guide

### React

- Prefer functional React components.
- Keep components focused and reusable.
- Use clear component and variable names.
- Avoid unnecessary duplication.
- Keep data separate from presentation where practical.

### Formatting

Use:

- **2 spaces** for indentation
- **Single quotes** for JavaScript strings
- **Semicolons**
- **PascalCase** for React component filenames

Example:

```jsx
function NoteCard({ title }) {
  return (
    <article className='note-card'>
      <h2>{title}</h2>
    </article>
  );
}

export default NoteCard;
```

### Naming

React components:

```text
NoteCard.jsx
SubjectPage.jsx
ChapterList.jsx
```

Functions and variables should use descriptive camelCase names:

```js
const subjectList = [];
const getChapterById = () => {};
```

## Content Quality

When adding notes:

- Use accurate titles.
- Place content in the correct semester/subject/chapter/topic.
- Check that links work.
- Avoid duplicate resources.
- Do not intentionally upload malware or unsafe files.
- Do not upload material you are not legally permitted to distribute.

## Reporting Bugs

When reporting a bug, include:

- Browser and version
- Device/OS when relevant
- Route where the problem occurred
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshot or console error when useful

## Feature Requests

Feature requests are welcome.

Explain:

- The problem the feature solves
- How you expect it to work
- Why it would benefit students
- Any alternative solution you considered

## License

By contributing to this repository, you agree that your contributions may be distributed under the project's [MIT License](LICENSE), unless otherwise stated.

Thank you for helping make HWN better for students!
