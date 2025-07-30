# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
and this project adheres to [Semantic Versioning](https://semver.org/).

---

## [2.2.0] – 2025-07-21

### Added
- Confirmation dialogs before clearing **Old BOM** or **New BOM** (OK/Cancel).
- Improved error handling during BOM collapsing:
  - Clear alerts instead of technical error messages.
  - Collapsing stops on error and returns to BOM editing.
- Better Excel file handling:
  - Informative alert if the file is locked by another program (e.g., Excel).
- **Portable version**: standalone EXE with embedded JRE. No Java installation required.

### Fixed
- Improved detection of partial duplicate entries when collapsing BOM.
- Correct handling of rows with empty references.

### Changed
- More strict duplicate detection during BOM collapsing.
- Increased stability when working with locked or opened Excel files.

---

## [2.1.0] – 2025-07-20

### Added
- **Session saving and loading**:
  - Saves collapsed BOMs and their file names.
  - New session format: **.bomds** (Bom Diff Session).
  - Full session recovery with data restored in tables.
- Save session dialog with automatic file naming and success confirmation.

### Fixed
- Minor UI and BOM loading stability improvements.

---

## [2.0.1] – 2025-07-20

### Added
- File names of **Old BOM** and **New BOM** are now displayed in the **Impact Summary** report.

### Changed
- Improved layout and readability of the **Impact Summary**:
  - Clear file name formatting and spacing.
  - Consistent table styles.

---

## [2.0.0] – 2025-07-19

### Highlights
- **First stable commercial release of BOM Diff**.
- Full BOM processing cycle:
  - Loading, collapsing, comparison by **Part Number** and **Reference**.
  - Change analysis with visual indicators.
  - Excel export with three dedicated pages:
    - **Impact Summary** – overall change impact levels.
    - **Part Number Comparison** – color-coded quantity comparison.
    - **Reference Comparison** – reference-level comparison with clear separation of old and new data.
- All critical bugs fixed. Reports optimized for commercial use.

---

## [1.15.0] – 2025-07-19

### Added
- Completed Excel report export:
  - Clear visual styles and consistent formatting.
  - Optimized for printing and PDF export.

---

## [1.14.3] – 2025-07-19

### Improved
- Added **Total** rows in change summary tables.
- Better spacing and page structure for improved readability.
- Correct page numbering for multi-page reports.

---

## [1.14.0 – 1.14.2] – 2025-07-18/19

### Improved
- Restored proper color coding and number display in **Change Impact Report**.
- Optimized print areas for correct PDF and paper output.

---

## [1.13.5] – 2025-07-17

### Added
- **Impact Level Bar** (VU-meter style):
  - Segmented scale with animated color transitions.
  - Highlights high-impact changes visually.

### Improved
- Cleaner and more concise **Change Impact Report** UI.

---

## [1.13.4] – 2025-07-16

### Added
- Full **Change Impact Report** dialog:
  - Detailed statistics for **Part Number** and **Reference** changes.
  - Visual severity indicators (Low / Moderate / High).
  - Change type icons and overall impact assessment.

---

## [1.13.1 – 1.13.3] – 2025-07-13

### Improved
- Change analysis recalculated on every run for up-to-date results.
- More structured change statistics, sorted by impact type.

---

## [1.12.0 – 1.12.9] – 2025-07-10/13

### Added
- Advanced change analysis:
  - Change severity levels for **Part Numbers** and **References**.
  - Detailed statistics and breakdown by change types.
- Configurable thresholds for impact evaluation.

### Improved
- Enhanced filtering and highlighting in BOM tables.

---

## [1.11.0] – 2025-07-09

### Added
- Color highlighting of rows affected by changes:
  - Quantity differences.
  - Reference differences.

---

## [1.10.0 – 1.10.9] – 2025-07-07/09

### Added
- Filtering and sorting for BOM tables and comparison results.
- Tooltips explaining change statuses.
- Color-coded icons for change types.

### Improved
- Overall table usability and navigation.

### Fixed
- Correct handling of null and empty values when comparing references.

---

## [1.9.0 – 1.9.1] – 2025-07-06

### Added
- Comparison by **Reference**:
  - Dedicated table view with icons for change types.

---

## [1.8.0 – 1.8.4] – 2025-07-04/05

### Added
- **CSV file support**.
- Independent import modes for Old and New BOM.
- Streamlined processing architecture for better stability and easier future updates.

---

## [1.7.0] – 2025-07-04

### Added
- Initial support for a flexible comparison architecture:
  - Multiple file formats.
  - Future extensibility for additional comparison modes.

---

## [1.6.0] – 2025-07-02

### Added
- Comparison by **Part Number**:
  - Color-coded results for new, removed, increased, and decreased parts.

---

## [1.5.0] – 2025-07-01

### Added
- Import and display of New BOM with adjustable column roles.
- Separate comparison table for New BOM.

---

## [1.4.0] – 2025-06-29

### Added
- Import of BOM files with customizable column roles.
- Quantity editing and validation in Old BOM table.
- Visual mismatch highlighting (quantity vs. references).

---

## [1.0.0] – 2025-06-01

### Initial Release
- Basic BOM loading and display.
- Editable BOM tables with quantity validation.

