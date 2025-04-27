# Changelog

All notable changes to the Memory Bank system will be documented in this file.

## [1.0.0] - 2025-04-27

### Added
- New docs/ folder for long-term documentation storage
- Required changelog.md for storing historical tasks
- File length monitoring for all Memory Bank files
- Cross-references between Memory Bank and docs/ files
- Alert system when files exceed recommended limits
- New documentation management workflow for Architect mode
- Mode-specific documentation referral mechanisms
- Specialized length awareness for each mode

### Changed
- Memory Bank files now have explicit size limits:
  - 2,000 word limit for productContext.md, activeContext.md, decisionLog.md, and systemPatterns.md
  - 20-task limit for progress.md
- Clarified projectBrief.md should remain in root directory
- Made projectBrief.md a read-only source document
- Updated all file paths to correctly use memory-bank/ prefix
- Redesigned update triggers to include length checking
- Limited documentation management responsibilities to Architect mode only
- Enhanced Orchestrator mode to consider Memory Bank maintenance as a potential subtask

### Fixed
- Prevented Memory Bank files from growing excessively large
- Corrected inconsistent file paths across different modes
- Clarified role boundaries to prevent inappropriate file modifications
- Resolved confusion around projectBrief.md location and management
- Fixed potential context loss issues due to file size limitations
- Addressed memory issues caused by excessive Memory Bank content
- Improved Memory Bank sustainability for long-term projects