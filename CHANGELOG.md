# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Help wanted page
- `single-content` layout for pages without a multi-card layout.

### Changed

### Removed
- `margin-left` on the first nav `li` 

## [0.0.1-beta.4] - 2022-07-16
### Added
- Collapsing navbar in mobile with burger trigger
- Bundler as package manager

### Changed
- Use borders instead of hrs for header and footer rules.
- Using `transform` instead of `position: relative` for button "hop" 
- `nav` mixin has been split into `nav-base` and `flex-end-center`
- Nav links now use `data-` attributes for current state.
- Config now excludes unused files in livereload.

### Removed
- `home` layout in favour of `default` layout with the content of home in [`index.md`](index.md)