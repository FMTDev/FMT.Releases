<div align=center style="text-align: center">
  
<h1 style="text-align: center"> Frostbite Modding Tool </h1>
The Frostbite Modding Tool (FMT) is a tool that has been in development since 2019 to create mods for EA / DICE Frostbite Engine games that can be deployed to multiple platforms.

</div>

---

<div align="center">

  ![LatestDownloads][downloads-latest-shield]
  ![Release][release-shield]

</div>

[downloads-latest-shield]: https://img.shields.io/github/downloads/FMTDev/FMT.Releases/latest/total?style=for-the-badge

[release-shield]: https://img.shields.io/github/v/release/FMTDev/FMT.Releases?style=for-the-badge

## Summary

This tool enables you to modify game assets, graphics, font, text and tweak gameplay mechanics to generate mod files to use within the in-built mod manager. It supports the 
deployments to multiple platforms including PC (with Registry Support for game detection), Playstation 4 and Nintento Switch.

Join the growing community of modders and share your creations with the world. Don't forget to star Frostbite Modding Tool on GitHub. Stay updated with the latest releases and enhancements by following the repository.

## Credits
- EA Sports & DICE - Without their engine and suite of games, this tool and the addiction to modding them wouldnt exist. Many thanks to all those who develop it and Frostbite!
- [@CadeEvs / Frosty Toolsuite](https://github.com/CadeEvs/FrostyToolsuite) development team. As of September 2022, Frosty Toolsuite is open source on [GitHub](https://github.com/CadeEvs/FrostyToolsuite) but seems to be unmaintained? I would recommend that tool for most older Frostbite games.
- [FIFA Editor Tool](https://www.fifaeditortool.com/) development team. This tool adds support to compile to FIFA Mod Manager *.fifamod files.
- [DirectXTexNet](https://github.com/deng0/DirectXTexNet) - Used library and rewrote parts for latest Chunk File Collection texture import [LICENSE](https://raw.githubusercontent.com/deng0/DirectXTexNet/master/LICENSE)
- [CSharpImageLibrary](https://github.com/KFreon/CSharpImageLibrary) - Exceptionally helpful in creating a library for importing/exporting in game images & textures

## Supported Games

**24th March 2025: FMT is going through a major restructure and architecture process. This is so it can become a more open suite of Nuget Packages to enable other developers to make their own tools. As a consequence of this, some games will either lose support entirely or be supported again in the future. See this list below to know which release will work for your game**

| Game         | Platform     | Supported    | Notes           |
|--------------|--------------|--------------|-----------------|
| Dead Space   | PC           | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| Dragon Age:VG| PC           | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| FC 24        | PC           | 100%         | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| FC 24        | Switch       | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| FC 24        | PS4          | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| FC 25        | PC           | 100%         |                 |
| FC 25        | Switch       | 50%          | EXPERIMENTAL    |
| FC 25        | PS4          | 50%          | EXPERIMENTAL    |
| FC 26        | PC           | 50%          | EXPERIMENTAL    |
| FIFA 17      | PC           | 50%          | READ ONLY       |
| FIFA 18      | PC           | 0%           | NO PROFILE      |
| FIFA 19      | PC           | 0%           | NO PROFILE      |
| FIFA 20      | PC           | 0%           | NO PROFILE      |
| FIFA 21      | PC           | 100%         | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.14.9170.27631)                |
| FIFA 22      | PC           | 75%          | NO MESH SUPPORT |
| FIFA 23      | PC           | 100%         | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.14.9170.27631)                |
| MADDEN 21    | PC           | 0%           | NO PROFILE       |
| MADDEN 22    | PC           | 0%           | NO PROFILE      |
| MADDEN 23    | PC           | 0%           | NO PROFILE      |
| MADDEN 24    | PC           | 0%           | NO PROFILE      |
| MADDEN 25    | PC           | 0%           | NO PROFILE      |
| NFS Unbound  | PC           | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| NHL 22       | PS4          | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| NHL 23       | PS4          | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| NHL 24       | PS4          | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| PGA Tour     | PC           | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |
| SWSquadrons  | PC           | 50%          | [Last supported release](https://github.com/FMTDev/FMT.Releases/releases/tag/FMT-25.17.9240.24186)    |

## Discord

[Join the little Discord server](https://discord.gg/zAUc6eHVS3)

## Nuget Packages generated by this project

| Name         | Url     |
|--------------|--------------|
| FMT.Db   | https://www.nuget.org/packages/FMT.Db/ |
| FMT.Ebx   | https://www.nuget.org/packages/FMT.Ebx/ |
| FMT.FileTools   | https://www.nuget.org/packages/FMT.FileTools/ |
| FMT.Hash   | https://www.nuget.org/packages/FMT.Hash/ |
| FMT.InitfsSupport   | https://www.nuget.org/packages/FMT.InitfsSupport/ |
| FMT.Logging   | https://www.nuget.org/packages/FMT.Logging/ |
| FMT.Models.Assets   | https://www.nuget.org/packages/FMT.Models.Assets/ |
| FMT.PluginInterfaces   | https://www.nuget.org/packages/FMT.PluginInterfaces/ |
| FMT.ProfileSystem   | https://www.nuget.org/packages/FMT.ProfileSystem/ |
| FMT.Registry   | https://www.nuget.org/packages/FMT.Registry/ |
| FMT.ServicesManagers   | https://www.nuget.org/packages/FMT.ServicesManagers/ |

## Video Tutorials

### Generating an SDK for a supported Profile
[![Watch the video](https://img.youtube.com/vi/3LAIs9cAF8I/maxresdefault.jpg)](https://youtu.be/3LAIs9cAF8I)

### Installing Mods
[![Watch the video](https://img.youtube.com/vi/Z-OLVsXOwyY/maxresdefault.jpg)](https://youtu.be/Z-OLVsXOwyY)

### Making your own Mods for FC 25
[![Watch the video](https://img.youtube.com/vi/2r7jW2PU81M/maxresdefault.jpg)](https://youtu.be/2r7jW2PU81M)

#FrostbiteModdingTool #FrostbiteEngine #GameModding #ModdingTool #Gaming #GameDevelopment #FrostbiteMods #ModdingCommunity #OpenSource #GitHub

