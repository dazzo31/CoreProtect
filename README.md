![CoreProtect](https://userfolio.com/uploads/coreprotect-banner-v19.png)

[![Artistic License 2.0](https://img.shields.io/github/license/PlayPro/CoreProtect?&logo=github)](LICENSE)
[![GitHub Workflows](https://github.com/PlayPro/CoreProtect/actions/workflows/build.yml/badge.svg)](https://github.com/PlayPro/CoreProtect/actions)
[![Netlify Status](https://img.shields.io/netlify/c1d26a0f-65c5-4e4b-95d7-e08af671ab67)](https://app.netlify.com/sites/coreprotect/deploys)
[![CodeFactor](https://www.codefactor.io/repository/github/playpro/coreprotect/badge)](https://www.codefactor.io/repository/github/playpro/coreprotect)
[![Join us on Discord](https://img.shields.io/discord/348680641560313868.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/b4DZ4jy)

CoreProtect
===========

## ⚠️ Important Notice
**This is a community fork.** The original CoreProtect project is maintained by PlayPro:
- Original Repository: https://github.com/PlayPro/CoreProtect
- Official Website: https://coreprotect.net
- Official Documentation: https://docs.coreprotect.net

This fork provides Minecraft 1.21.10 support while the official version supports up to 1.21.1.

---

CoreProtect is a blazing fast data logging and anti-griefing tool for Minecraft servers.

For a detailed description of the plugin, please visit [coreprotect.net](https://coreprotect.net).

| Quick Links |  |
| --- | --- |
| CoreProtect Discord: | [discord.gg/b4DZ4jy](https://discord.gg/b4DZ4jy) |
| CoreProtect Patreon: | [patreon.com/coreprotect](https://www.patreon.com/coreprotect) |
| CoreProtect Documentation: | [docs.coreprotect.net](https://docs.coreprotect.net) |
| Downloads for MC 1.14 - 1.21.10: | [coreprotect.net/latest](https://coreprotect.net/latest/) |
| Downloads for MC 1.8 - 1.12: | [coreprotect.net/legacy](https://coreprotect.net/legacy/) |

bStats
------
[![bStats Graph Data](https://bstats.org/signatures/bukkit/CoreProtect.svg)](https://bstats.org/plugin/bukkit/CoreProtect)

API
------
### [API Documentation](https://docs.coreprotect.net/api/)

### Dependency Information
Maven
```xml
<repository>
    <id>playpro-repo</id>
    <url>https://maven.playpro.com</url>
</repository>
```
```xml
<dependency>
    <groupId>net.coreprotect</groupId>
    <artifactId>coreprotect</artifactId>
    <version>23.1</version>
    <scope>provided</scope>
</dependency>
```

Version 23.1 Changes
------
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

Contributing
------
CoreProtect is an open source project, and gladly accepts community contributions.

If you'd like to contribute, please read our contributing guidelines here: [CONTRIBUTING.md](CONTRIBUTING.md)

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CONTRIBUTING.md#code-of-conduct) 
