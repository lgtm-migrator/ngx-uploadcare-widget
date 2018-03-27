# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 0.2.1 - 2018-03-28
Fix release.

### Changed
* Fixed issue of reinit component on IE
* Updated unit tests. Coverage summary up to 100%
* Updated [Demo](/demo) projects with usage examples.

## 0.2.0 - 2018-03-14
Added support for interactions

### Added
* `clearUploads()` a method that removes all current uploads from the widget: "clears" it.
**Please note:** When you remove current uploads from a widget, the files are not removed from your UC project defined by its public key.
* `reset()` a method allowing for the manual widget reset.

### Changed
* The component is now interactive: your widget accepts the changes in input parameters.
* Updated README with info about install, usage, etc.
* Updated [Demo](/demo) projects with usage examples.

## 0.1.3 - 2018-02-08
Initial public release.

### Added
* The `ngx-uploadcare-widget` component.
* README with info about install, usage, etc.