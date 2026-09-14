# HWN — Hand Written Notes

A clean, browser-friendly **B.Tech study resource hub** for organizing and accessing handwritten notes.


[![Live Website](https://img.shields.io/badge/Live-Website-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white)](https://amitmaurya270708.github.io/HWN/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Made for Students](https://img.shields.io/badge/Made_for-Students-blueviolet?style=for-the-badge&logo=readthedocs&logoColor=white)](#)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=git&logoColor=white)](CONTRIBUTING.md)

## Overview

**HWN (Hand Written Notes)** is a React + Vite study resource hub designed to make B.Tech notes easy to browse and access.

The content is organized through a simple hierarchy:

**Semester → Subject → Chapter → Topic**

The project is intended to provide a lightweight experience for students who want quick access to study material without unnecessary accounts or authentication.

## Features

- 📚 Hierarchical navigation:
  - Semester
  - Subject
  - Chapter
  - Topic
- 📄 PDF preview for study material
- 🖼️ Image preview for handwritten notes
- 🔗 Direct, browser-friendly routes
- 🚫 No user authentication required
- ⚡ Fast React + Vite frontend
- 📱 Responsive interface
- 🔒 Production build with JavaScript obfuscation
- 🌐 Hosted on GitHub Pages

## Tech Stack

- **React**
- **Vite**
- **React Router**
- **JavaScript**
- **javascript-obfuscator**

---

## Notes and Content Contributions

Contributors can help by:

- Adding useful B.Tech notes
- Improving navigation
- Fixing UI or accessibility issues
- Improving performance
- Adding useful frontend features
- Fixing bugs

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## Security / Source Protection

The production build may use `javascript-obfuscator` as an additional barrier against casual inspection of client-side JavaScript.

This is **not encryption** and does not make frontend code secret. Anything delivered to a user's browser should be considered potentially accessible.

The project may also use domain/origin checks where appropriate. These checks should be treated as a practical restriction rather than a complete security boundary.

## Known Issues

### GitHub Pages deep links

Because the application uses client-side routing, directly opening a nested route on GitHub Pages may result in a **404** unless the deployment is configured to handle SPA fallback behavior.

### WhatsApp / social previews

Client-rendered pages may not always generate the expected preview title, description, or thumbnail when a nested route is shared through WhatsApp or other social platforms. This can happen because social crawlers may not execute the application's JavaScript in the same way as a normal browser.

## Contributing

See:

- [CONTRIBUTING.md](CONTRIBUTING.md)
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for release history.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

Copyright © 2026 Amit Maurya.

## Author

**Amit Maurya**

- GitHub: https://github.com/AmitMaurya270708
- Project: https://github.com/AmitMaurya270708/HWN
- Live site: https://amitmaurya270708.github.io/HWN/

---

Made for students who want their handwritten study material to be easier to find and use.
