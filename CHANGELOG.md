# Change Log

All notable changes to the "erg-snippets" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [2.0.0] - 2026-01-20

### Added
- **New Components**: Added 12 new UI component snippets:
  - `erg-navbar` - Responsive navigation bar with mobile menu
  - `erg-card` - Versatile card component with image and footer support
  - `erg-table` - Sortable data table with custom cell rendering
  - `erg-spinner` - Loading spinner with multiple sizes
  - `erg-alert` - Dismissible alert with 4 variants (info, success, warning, error)
  - `erg-tabs` - Tab navigation component
  - `erg-footer` - Multi-column footer with social links
  - `erg-pagination` - Pagination with ellipsis support
  - `erg-avatar` - Avatar with initials fallback and status indicator
  - `erg-badge` - Badge/tag component with color variants
  - `erg-accordion` - Collapsible accordion sections
  - `erg-toast` - Toast notification system with React Context

### Improved
- **Login Page**: Added loading state, better form styling, and link to register
- **Register Page**: Added password validation, loading state, and link to login
- **404 Page**: Added "Go Back" button and better messaging
- **About Page**: Added hero section and team member cards
- **Button**: Added variants (primary, secondary, success, danger, outline) and sizes
- **Modal**: Added click-outside-to-close, scroll lock, and customizable footer
- **Search**: Added clear button and Enter key support
- **Search Select**: Added keyboard navigation (arrow keys, Enter, Escape)

### Changed
- Bumped version to 2.0.0
- Updated README with comprehensive documentation and examples

## [1.1.0] - 2026-01-20

### Changed
- **Breaking**: Removed Tailwind CSS dependency
- All snippets now use native styling (inline styles for React, scoped CSS for Vue, component styles for Angular)
- Updated package description to reflect changes
- Updated README to document the new styling approach

## [1.0.1] - Initial Release

### Added
- Initial snippets for React, Vue, Angular
- Login page snippet
- Register page snippet
- 404 page snippet
- About page snippet
- Button component
- Search component
- Search Select component
- Modal component
