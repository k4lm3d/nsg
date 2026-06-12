# Changelog

All notable changes to the NSG website repository will be documented in this file.

---

## [Unreleased]

- Ongoing improvements and fixes

---

## [2026-06] - Added legal pages, licensing, Firebase integration, deployment automation, and navigation improvements.

### Added

* Added homepage exploration suggestions and explore options.
* Added email address to profile and site pages.
* Added navigation menu entries:
  * History
  * Privacy Policy
  * Terms of Use
  * Source Code
* Added Privacy Policy and Terms of Use pages.
* Added Community Principles page.
* Added History page.
* Added CONTRIBUTING.md.
* Added MIT License.
* Added licensing information to README.
* Added Firebase configuration values.
* Added Firebase Hosting configuration.
* Added GitHub Actions workflow for deploying Hugo site to Firebase Hosting.
* Enabled Firebase Views and Likes features through Firestore.

### Changed

* Updated footer navigation menus.
* Updated site menu configuration.
* Updated Privacy Policy content.
* Updated README documentation.
* Updated Hugo configuration.
* Updated Roles page and archived the previous version.
* Updated build settings, domains, and resource configuration.
* Updated GitHub Actions cherry-pick workflow.
* Reorganized Privacy Policy content structure.
* Updated various site pages and content.

### Fixed

* Fixed homepage menu link errors.

### Infrastructure

* Enabled Google Analytics and configured Measurement ID.
* Enabled deployment of Hugo site to Firebase Hosting.
* Added cherry-pick workflow and imported history-related content into legal branch.

### Documentation

* Added CONTRIBUTING guidelines.
* Added licensing and legal documentation.
* Added Privacy Policy and Terms of Use documentation.

---

## [2026-04] - Updated Blowfish theme

### Changed

* Updated Blowfish theme

---

## [2026-03] - Automation, Content Updates & Refinements

### Added
- Created GitHub workflows for changelog generation
- Added funding configuration (`funding.yml`)
- New member page: Jude
- Added aliases for members and documentation shortcuts
- Created content pages:
  - [DRAFT] `welcome.md`
  - [DRAFT] `roaster.md`
  - [DRAFT] `join.md`
  - [PUBLISHED] `history.md`
  - [PUBLISHED] `community-principles.md`
- Created CHANGELOG.md

### Changed
- Updated multiple documentation pages (contributions, contact, terminologies)
- Improved footer and layout components
- Updated baseURL and site configuration
- Enhanced terminologies with accordion UI
- Updated icons and formatting across docs
- Updated contributions.md and [DRAFT] join.md
- Updated history.md
- Updated news/logo-and-color
- Updated gaming-guidelines.md, gaming-protocol.md, server-roles.md, and community-principles.md
- Updated README.md
- Updated CHANGELOG.md

### Fixed
- Fixed errors in changelog workflow
- Fixed image URL issues
- General bug fixes in documentation

### Removed
- Removed redundant GitHub workflows
- Renamed/relocated files for clarity:
  - `content/server-rules.md` → `contents/news/server-rules.md`
  - `content/community-principles.md` → `content/news/community-principles.md`
  - `gaming-guidelines/index.md` → `content/gaming-guidelines.md`
  - `gaming-guidelines/old.md` → `archives/gaming-protocol.md`
  - `roles/old.md` → `archives/server-roles.md`
  - `content/roles/index.md` → `content/roles.md`

---

## [2026-02] - Structural Changes & Theme Management

### Added
- Added Blowfish theme as a submodule
- Created automation workflow for submodule updates
- Added build/render script

### Changed
- Updated Hugo configuration files
- Updated README and contributions
- Refactored site structure and content organization

### Removed
- Removed old theme directory
- Deleted outdated workflows

---

## [2026-01] - Major Content Expansion & Site Setup

### Added
- Legal pages (Privacy Policy, Terms of Service)
- Harewire section and assets (images, GIFs)
- Operations pages (Aqua Vista 2025, Golden Dragon 2025)
- Custom CSS and UI enhancements
- Navigation menus and layout extensions

### Changed
- Refactored content into structured directories
- Improved menus and navigation
- Updated leadership, about, and contributions pages

### Fixed
- General layout and configuration fixes

---

## [2025-12] - Operations & Content Organization

### Added
- Operations pages and security code page
- News section and branding assets

### Changed
- Reorganized content structure (roles, guidelines, ops)
- Updated Harewire information and links

---

## [2025-07] - Major Website Overhaul

### Added
- Gaming guidelines, server rules, and hop protocol pages
- Roles and leadership pages
- Member profiles (xythran, chief_marauder, en_roise)
- Contributions page

### Changed
- Massive updates to:
  - index pages
  - menus
  - configurations
  - terminologies
- Improved layout and structure
- Updated assets and media

### Removed
- Cleaned up old assets (favicons, GIFs, banners)
- Removed deprecated files and directories

---

## [2025-06] - Visual Updates

### Added
- New Nousagi gang banner

### Changed
- Updated homepage and parameters

---

## [2024-11] - Initial Development

### Added
- Initial project setup
- Members, roles, and contributions pages
- Terminologies page
- Navigation menus and configurations

### Changed
- Updated configurations and page structure

### Other
- First commit 🎉

---

## Notes
- This changelog is derived from commit history and grouped for clarity.
- Future updates should follow a consistent format:
  - Added
  - Changed
  - Fixed
  - Removed
