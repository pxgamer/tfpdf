# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]

## [v2.1.0]

### Added
- Password protected PDF generation possible when using ProtectedPDF class

## [v2.0.7]

### Fixes
- PHPDoc fixes

## [v2.0.6]

### Fixes
- Fixed unit test failing when using the default unifont files
- Font descriptor data was not utilised properly

### Changed
- New parameter added to MultiCell - which allows you to limit the number of lines the MultiCell should use at most. If the parameter is passed the Multicell will return a string with the remaining text, which did not fit.

## [v2.0.5]

### Fixes
- "U" style did not actually underline the text.

[Unreleased]: https://github.com/DocnetUK/tfpdf/compare/v2.1.0...HEAD
[v2.1.0]: https://github.com/DocnetUK/tfpdf/compare/v2.0.7...v2.1.0
[v2.0.7]: https://github.com/DocnetUK/tfpdf/compare/v2.0.6...v2.0.7
[v2.0.6]: https://github.com/DocnetUK/tfpdf/compare/v2.0.5...v2.0.6
[v2.0.5]: https://github.com/DocnetUK/tfpdf/compare/v2.0.4...v2.0.5
