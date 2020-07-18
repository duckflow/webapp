# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.8.0] - 2020-07-18

### Added

- Additional "Puppeteer" template (experimental)
- Custom property panes for the "Puppeteer" template (experimental)
- Generate `jest-puppeteer` tests as JavaScript code for the "Puppeteer" template (experimental)
- Code folding for the Markup tab
- Code folding for the Code tab

### Changed

- Rename "Code" tab to "Markup"
- New "Code" tab for custom code generators (Puppeteer as an example)

### Fixed

- Fix default namespaces in the process templates

## [0.7.0] - 2020-06-21

### Added

- Application blog released (<https://blog.duckflow.app>)
- Link to a Blog within the application menu and toolbar
- GitHub Gist Viewer (`/gist/<id>` route)
- Display "Map" and "Properties" panel in the tabs header
- GitHub and Twitter links on the app menu

### Fixed

- Correctly display shortcuts on macOS and Windows platforms
- Fix issues with keyboard handling outside the Diagram

### Changed

- Increase the size of Properties panel

## [0.6.0] - 2020-06-09

### Added

- New "Add tab" button that allows to create a new process fast
- Pinned tabs, allow pin/unpin one or more editor tabs
- Drag and drop ".bpmn" files to the application
- Navigation sidebar with access to all workspace files

### Removed

- Recent Files menu (replaced by the navigation sidebar)
- Recent Files dropdown in the Tabs

## [0.5.0] - 2020-05-29

### Added

- Backup and download entire workspace (.zip)
- Restore the workspace from the backup (.zip)

### Fixed

- Selection menu items now depend on the selected state
- Cut/Copy and Color tools now depend on the selected state

### Changed

- Changed "Export to XML" to "Export to BPMN" menu

## [0.4.0] - 2020-05-22

### Added

- New "Selection" menu
- Distribute Elements (Horizontally, Vertically)
- Align Elements (Left, Center, Right, Top, Middle, Bottom)

### Fixed

- Undo/Redo menu items disabled when action not available
- Improved upgrades to the next versions

### Changed

- Lazy loading for Code Editor
- Various code improvements

## [0.3.0] - 2020-05-14

### Added

- Find functionality ( `Cmd+F` / `Ctrl+F` )
- Set color for shapes
- Context Menus for Tabs
  - Close editor
  - Close all editors
  - Close all other editors

### Fixed

- Exporter version now matches the application version

### Changed

- Improved keyboard handling
- Improved Properties Panel layout
- Improved main page layout

## [0.2.0] - 2020-05-07

### Added

- Zoom controls via application menu and keyboard shortcuts
  - Zoom In ( `Cmd+` / `Ctrl+` )
  - Zoom Out ( `Cmd-` /`Ctrl-` )
  - Reset Zoom ( `Cmd+0` / `Ctrl+0` )
  - Zoom to Fit ( `Cmd+9` / `Ctrl+9` )
- New `Edit` menu with editor actions
  - Undo ( `Cmd+Z` / `Ctrl+Z` )
  - Redo ( `Cmd+Shift+Z` / `Ctrl+Shift+Z` )
  - Copy ( `Cmd+C` / `Ctrl+C` )
  - Cut (`Cmd+X` / `Ctrl+X` )
  - Paste ( `Cmd+V` / `Ctrl+V` )
  - Select All ( `Cmd+A` / `Ctrl+A` )
  - Remove Selected (`Backspace`)
- New `Edit / Tools` menu
  - Hand Tool ( `H` )
  - Space Tool ( `S` )
  - Global Connect Tool ( `C` )
  - Edit Label Tool ( `E` )
- Navigate open editors
  - activate previous open editor ( `Cmd+[` / `Ctrl+[` )
  - activate next open editor ( `Cmd+]` / `Ctrl+]` )

### Changed

- Rename "File/Save" to "File/Download"
- Rename "File/Load" to "File/Open"
- Rename "File/Delete" to "File/Delete File"

## [0.1.0] - 2020-05-03

- Initial preview release
