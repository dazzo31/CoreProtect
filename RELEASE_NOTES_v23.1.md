# CoreProtect v23.1 - Minecraft 1.21.10 Support

## ⚠️ Important Notice
This is a **community fork** of CoreProtect. The original project is maintained by PlayPro and can be found at:
- **Original Repository:** https://github.com/PlayPro/CoreProtect
- **Official Website:** https://coreprotect.net
- **Official Documentation:** https://docs.coreprotect.net

This fork provides Minecraft 1.21.10 support while the official version supports up to 1.21.1.

## Changes

### What's New
- **Minecraft 1.21.10 Support**: Full compatibility with Minecraft version 1.21.10
- **Updated Paper API**: Dependency updated to 1.21.4-R0.1-SNAPSHOT for latest compatibility
- **Removed Version Restrictions**: Community Edition version checks removed for fork flexibility
- **Maintained Backward Compatibility**: All existing 1.21 features remain unchanged:
  - Crafter blocks
  - Wolf variants
  - Copper chests

### Technical Changes
- Set `project.branch` to `stable` for production builds
- Removed Community Edition version validation check
- Removed patch version validation for fork compatibility
- Updated `LATEST_VERSION` constant to 1.21.10

## Installation
Place the `CoreProtect-23.1.jar` file in your server's plugins folder and restart the server.

## Compatibility
- **Minecraft:** 1.14 - 1.21.10
- **Server:** Spigot, Paper, or compatible forks
- **Java:** 11+

## Files
The compiled JAR file is located at:
`C:\Users\dazzo\OneDrive\GitHub\CoreProtect\target\CoreProtect-23.1.jar`

## Manual Release Creation Instructions
Since the GitHub CLI (`gh`) is not installed, please create the release manually:

1. Go to: https://github.com/dazzo31/CoreProtect/releases/new
2. Select the tag: `v23.1`
3. Set title: `CoreProtect v23.1 - Minecraft 1.21.10 Support`
4. Copy the content above (Changes, Installation, Compatibility sections) into the release notes
5. Upload the JAR file: `C:\Users\dazzo\OneDrive\GitHub\CoreProtect\target\CoreProtect-23.1.jar`
6. Click "Publish release"
