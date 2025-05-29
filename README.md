 [中文](README_zh_CN.md)

# SiYuan Note Header Auto Numbering Plugin

## Introduction

This is a header numbering plugin designed for SiYuan Note. It helps you add standardized numbering to document headers, making the document structure clearer.

## Features

1. **Hierarchical Numbering**
   - Level 1 headers: Chinese numerals (一、二、三...)
   - Level 2 headers: Numeric format (1.1, 1.2, 1.3...)
   - Level 3 and below headers: Multi-level numeric format (1.1.1, 1.1.2...)

2. **Manual Control**
   - Add numbering to the current document at any time
   - Remove numbering from the current document at any time
   - No automatic document modification to avoid accidental changes

3. **Format Standards**
   - Level 1 headers: Number directly followed by header text (e.g., 一、Introduction)
   - Level 2 and below headers: Number followed by a space (e.g., 1.1 Background)

## Usage

1. **Add Header Numbering**
   - Open the document you want to number
   - Click the numbering icon (⑪) in the top right corner
   - Select "Add numbering to current document" from the dropdown menu

2. **Remove Header Numbering**
   - Open the document you want to remove numbering from
   - Click the numbering icon (⑪) in the top right corner
   - Select "Remove numbering from current document" from the dropdown menu

## Notes

1. The plugin only processes the currently open document
2. Numbering operations cannot be undone, please use the remove function carefully
3. If the document already has numbering, the plugin will remove the existing numbering before adding new ones

## Installation

1. Download the release package
2. Extract to SiYuan Note's plugin directory
   - Windows: `%APPDATA%/SiYuan/plugins/`
   - MacOS: `~/Library/Application Support/SiYuan/plugins/`
   - Linux: `~/.config/SiYuan/plugins/`
3. Restart SiYuan Note

## Developer Information

- Author: [Your Name]
- License: MIT
- Project URL: [GitHub Repository URL]

## Changelog

### v1.0.0 (2024-01-xx)

- Initial release
- Implemented basic header numbering functionality
- Added support for manual adding and removing numbering