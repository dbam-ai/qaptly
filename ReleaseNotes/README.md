# Qaptly Release Notes

This directory contains simplified release notes for all Qaptly versions, synchronized from the main development repository.

## Purpose

- Provide a centralized location for all release notes in the public repository
- Maintain version history for easy reference
- Simplify the GitHub release process by having release notes ready in advance

## Structure

Each release note file is named `v<version>.md` and contains:
- What's New - Key features and improvements
- Bug Fixes - Important bug fixes
- Bundled Components - qaptly_mac_cmd version information
- Installation - Download links

## Relationship with Development Repo

- **Development Repo** (`local-agent-electron`): Contains detailed internal release notes with Jira tickets, technical details, and full documentation
- **Public Repo** (`qaptly`): Contains simplified release notes suitable for public GitHub releases

## Version Tags

Both repositories maintain synchronized version tags:
- Development repo: Internal tracking and detailed history
- Public repo: Public releases and distribution

## Usage

When creating a new release:
1. Write detailed release notes in the development repo (`docs/releases/`)
2. Extract simplified version (remove Jira tickets, internal details)
3. Copy simplified version to this directory
4. Create matching version tags in both repositories

See `local-agent-electron/docs/release_process.md` for complete release workflow.

## Release History

### Latest Versions

- **v0.14.7** (2025-12-17) - Visual Change Detection and Simplified Android Setup
- **v0.14.6** (2025-12-14) - Enhanced Android Support and Mobile Test Designer Improvements
- **v0.14.5** (2025-12-09) - Property Condition Editor and Mobile Analysis Enhancements
- **v0.14.4** (2025-12-04) - Mobile Test Settings, Android Input Mode, APK Update Notification
- **v0.14.3** (2025-12-04) - Mobile Test Designer Bug Fixes
- **v0.14.0** (2025-11-29) - MCP Integration and Spec V2 Workflow
- **v0.13.8** (2025-11-26) - Test Specification & Collection Enhancements
- **v0.13.7** (2025-11-24) - Google Sign-In Support
- **v0.13.6** (2025-11-24) - Two-Factor Authentication and Security Enhancements
- **v0.13.5** (2025-11-20) - Macro support
- **v0.13.3** (2025-11-19) - iOS Integration Improvements
- **v0.13.2** (2025-11-17) - Screenshot Upload Fix
- **v0.13.1** (2025-11-14) - Complete Internationalization & Bug Fixes
- **v0.13.0** (2025-11-13) - iOS Integration Enhancements

### Version Ranges

- **v0.14.x** (2025-11-29 onwards) - MCP (Model Context Protocol) integration, Spec V2 workflow, enhanced security
- **v0.12.x - v0.13.x** (2025-11-05 to 2025-11-28) - Mobile Test Designer development and iOS integration
- **v0.11.x** (2025-10-15 to 2025-11-04) - Mobile test execution framework and cross-platform support
- **v0.10.x** (2025-10-14 to 2025-10-15) - Early mobile testing features
- **v0.9.x** (2025-06-02 to 2025-10-08) - Desktop testing, initial Qaptly release
- **v0.8.x** (2025-04-14 to 2025-05-06) - Pre-mobile testing, macOS-only
- **v0.7.x** (2025-02-06 to 2025-04-11) - Desktop automation, **last Windows support (v0.7.37)**
- **v0.6.x** (2025-01-13 to 2025-02-05) - Desktop testing foundation, cross-platform
- **v0.5.x** (2025-01-05 to 2025-01-11) - Early testing features with browser automation support
- **v0.2.x** (2024-12-01) - Early beta releases

### Notable Milestones

- **v0.9.20** (2025-06-02) - First official release with version tag
- **v0.7.37** (2025-04-11) - **Last version to support Windows**
- **v0.8.x series** (2025-04) - Transition to macOS-only
- **v0.11.x series** (2025-10) - Mobile testing framework introduced
- **v0.13.0** (2025-11-13) - stable iOS support

See individual release notes for detailed information about each version.
