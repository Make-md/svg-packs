# SVG Icon Packs - Release Repository

[![Create Release](https://github.com/[YOUR_USERNAME]/svg-packs-release/actions/workflows/release.yml/badge.svg)](https://github.com/[YOUR_USERNAME]/svg-packs-release/actions/workflows/release.yml)
[![License: Various](https://img.shields.io/badge/License-Various-blue.svg)](https://github.com/[YOUR_USERNAME]/svg-packs-release)

This repository contains curated releases of popular open-source SVG icon packs, automatically organized by variants (filled, outlined, brands, etc.).

## 🚀 Quick Start

### Option 1: Download from Releases
Visit the [Releases page](https://github.com/[YOUR_USERNAME]/svg-packs-release/releases) to download individual variant zip files.

### Option 2: Clone Repository
```bash
git clone https://github.com/[YOUR_USERNAME]/svg-packs-release.git
```

## 📦 What's Included

- **20+ popular icon packs** including Bootstrap Icons, Font Awesome, Material Design Icons, etc.
- **Organized by variants** - separate files for filled, unfilled, outlined, brands, etc.
- **Original SVG files** with proper directory structure
- **All licenses included** for each icon pack

## 🔄 Automated Releases

This repository automatically creates a new GitHub release whenever changes are pushed to the main branch. Each release includes:
- All variant zip files as downloadable assets
- Automatic versioning based on date
- Complete changelog

## 📁 Repository Structure

```
├── README.md                 # This file
├── zips/                    # All icon pack zip files
│   ├── bootstrap-icons-filled.zip
│   ├── bootstrap-icons-unfilled.zip
│   └── ... (39+ variant zips)
└── svg-originals/           # Original SVG files with licenses
    ├── bootstrap-icons/
    ├── font-awesome/
    └── ... (20+ icon packs)
```

## 📄 Licenses

Each icon pack retains its original license. Check the `svg-originals/[pack-name]/LICENSE` file for specific licensing terms.

## 🤝 Contributing

This is an automated release repository. To contribute or report issues with the icon packs, please refer to the original repositories.

## ⚙️ GitHub Actions

This repository uses GitHub Actions to automatically create releases. The workflow:
1. Triggers on pushes to main branch
2. Generates a version number based on date
3. Creates a GitHub release
4. Uploads all zip files as release assets

To use this in your fork:
1. Fork this repository
2. Update the `[YOUR_USERNAME]` placeholders in README.md
3. Enable GitHub Actions in your fork
4. Push changes to trigger automatic releases
