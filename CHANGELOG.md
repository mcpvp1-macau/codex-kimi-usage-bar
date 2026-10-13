# Changelog

All notable changes to this project will be documented in this file.

## [2.7.20] - 2026-10-13

### Changed

- Replaced the legacy application icon with an original minimalist line-art cat mark created for this independent project.
- Regenerated every macOS AppIcon size so the new mark is consistent in Finder, Dock, menu bar, and installers.

## [2.0.0] - 2026-08-30

### Added

- Native macOS menu bar usage display.
- Five-hour and weekly remaining quota with reset times.
- Configurable menu bar icon and text sizing.
- Launch-at-login support.
- Native menu presentation and settings window.
- Touch Bar usage progress, percentages, reset times, and refresh action.
- Optional automatic Touch Bar presentation while Codex is frontmost.

### Notes

- Usage data is read from the locally installed Codex app-server.
- Persistent Touch Bar presentation relies on an undocumented AppKit selector.
