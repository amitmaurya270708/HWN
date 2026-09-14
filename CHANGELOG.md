# Changelog

All notable changes to **HWN — Hand Written Notes** are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the project uses [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added

- Planned improvements to the study-resource browsing experience.
- Additional B.Tech subjects, chapters, and topics.
- Further improvements to PDF and image preview behavior.
- Additional responsive and accessibility improvements.

### Changed

- Future refinements to navigation and resource organization.

### Fixed

- Future bug fixes and deployment improvements.

## [1.0.0] — 2026-09-14

Initial public release of HWN — Hand Written Notes.

### Added

- B.Tech study resource hub.
- Hierarchical navigation:
  - Semester
  - Subject
  - Chapter
  - Topic
- PDF preview support.
- Image preview support for handwritten notes.
- Browser-friendly React interface.
- React Router based navigation.
- Vite development and production setup.
- GitHub Pages deployment.
- Production JavaScript obfuscation using `javascript-obfuscator`.
- Project documentation:
  - README
  - CONTRIBUTING guide
  - CODE OF CONDUCT
  - LICENSE
  - CHANGELOG

### Security Notes

- Production JavaScript may be obfuscated to make casual source inspection more difficult.
- Domain/origin restrictions may be used as an additional protection layer where implemented.
- These measures are not equivalent to encryption or server-side access control.
- Content delivered to a user's browser should not be considered secret.

### Known Issues

#### GitHub Pages deep links

Client-side routes may return a 404 when a nested URL is opened directly on GitHub Pages if SPA fallback handling is not configured.

#### WhatsApp and social previews

Nested client-rendered routes may not always produce the expected title, description, or thumbnail when shared through WhatsApp or other social platforms because social crawlers may not execute client-side JavaScript like a normal browser.
