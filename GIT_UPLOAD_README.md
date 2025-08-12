# IntelliJ Plugin - Git Repository Upload Guide

## Overview
This directory contains all the essential documentation and compliance files that should be uploaded to Git for the Element Insight IntelliJ Plugin project. This ensures proper IP protection and compliance documentation while keeping the main plugin source code separate.

## Files to Upload to Git

### 📋 Core Documentation
- **README.md** - Main project overview, features, and getting started guide
- **LICENSE** - MIT License with attribution requirements
- **RELEASE_NOTES.md** - Version history and release information
- **INSTALLATION.md** - Installation and setup instructions
- **DISTRIBUTION_README.md** - Distribution and deployment guide

### 🔒 Compliance & Legal
- **ATTRIBUTION.md** - Third-party library attributions and licenses
- **THIRD_PARTY_LICENSES.md** - Full license texts for all dependencies
- **COMPLIANCE_CHECKLIST.md** - Marketplace compliance verification
- **RUST_THIRD_PARTY_LICENSES.md** - Complete Rust crate license information

### ⚙️ Git Configuration
- **.gitignore** - Git ignore patterns for the repository

## What NOT to Upload
- Source code files (`src/` directory)
- Build artifacts (`build/` directory)
- Gradle configuration files
- Binary executables
- IDE-specific files (`.idea/`, `.gradle/`)

## Purpose
This structure allows you to:
1. **Protect IP**: Keep the main plugin source code private
2. **Maintain Compliance**: Document all licensing and attribution requirements
3. **Enable Collaboration**: Share documentation without exposing proprietary code
4. **Meet Marketplace Requirements**: Provide all necessary legal and compliance documents

## Upload Instructions
1. Initialize a new Git repository
2. Add all files from this `git-repo` directory
3. Commit with message: "Initial documentation and compliance files"
4. Push to your chosen Git hosting service

## File Maintenance
- Update these files whenever dependencies change
- Regenerate Rust license information after binary updates
- Keep compliance checklist current with marketplace requirements
- Ensure all third-party attributions are accurate and complete

## Contact
For questions about licensing or compliance, refer to the main project documentation or contact the development team.
