# Docx/PPTX to PDF Converter for macOS (Quick Action)

A Guide on how to make a macOS Quick Action that converts Microsoft Word (.docx) and PowerPoint (.pptx) files to PDF directly from Finder or even just from the Desktop.

## Features
- One-click conversion from Finder right-click menu
- Preserves original files
- Saves PDF in same folder as source file
- Supports batch conversion (select multiple files)
- Works with .docx and .pptx files

## Useful for
- Converting lecture notes from .docx to PDF
- Saving PowerPoint slides as PDF (preserves formatting)
- BASICALLY Anyone who receives .pptx from teacher instead of PDF (basically my motivation)


## Screenshots
<!-- TODO: Add screenshot of right-click menu showing "Convert to PDF" option -->
![Quick Action in Finder](screenshots/finder-menu.png)

<!-- TODO: Add screenshot of successful conversion -->
![Conversion Result](screenshots/conversion-result.png)

## Requirements
- **macOS** (tested on Ventura and later)
- **LibreOffice** (free, open-source)

## Installation

#### Using Homebrew
```bash
brew install --cask libreoffice
```
<br>
<br>
<br>
<br>
<br>

# No Homebrew installed???, oh mannn
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### After installation, add Homebrew to PATH (for Apple Silicon Macs)
```bash
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

### For Intel Macs, use instead:
```bash
echo 'eval "$(/usr/local/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/usr/local/bin/brew shellenv)"
```

# Verify installation
```bash
brew --version
```
