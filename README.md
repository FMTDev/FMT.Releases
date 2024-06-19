<div align=center>

</div>

---

<div align=center style="text-align: center">
  
<h1 style="text-align: center"> Frostbite Modding Tool </h1>
The Frostbite Modding Tool (FMT) is a tool to create mods for FIFA, Madden and other Frostbite Engine games.

</div>

---

<div align="center">

  ![TotalDownloads][downloads-total-shield]
  ![LatestDownloads][downloads-latest-shield]

</div>

<!-- MARKDOWN LINKS & IMAGES -->
[downloads-total-shield]: https://img.shields.io/github/downloads/FMTDev/FMT.Releases/total?style=for-the-badge

[downloads-latest-shield]: https://img.shields.io/github/downloads/FMTDev/FMT.Releases/latest/total?style=for-the-badge

## Background
The Frostbite Modding Tool (FMT) was born out of necessity when the "Frosty Toolsuite" development team decided not to continue after FIFA 20. Mainly due to the lead developer going to work for DICE.

The original `code` for this tool was developed from using ILSpy to dump the badly decompiled "Frosty" `code` into a .NET Framework 4.5 library. 
This code was then cleaned up, fixed and converted into the `FrostySdk` library. However, all the "Frosty" User Interface was unusable!

FMT in its infancy was the first tool available to create some fairly simple mods for FIFA 21.

This tool is used & developed for a hobby. It is a great suite of code to learn new C# .NET features and best practices. 

## Credits
- EA Sports & DICE - Without their engine and suite of games, this tool and the addiction to modding them wouldnt exist. Many thanks to all those who develop it and Frostbite!
- [@CadeEvs / Frosty Toolsuite](https://github.com/CadeEvs/FrostyToolsuite) development team. All the `existing code` for `FrostySdk`,`SDK Generator` and `Modding` came decompilation of their Toolsuite using ILSpy when their tool was decomissioned in 2019. As of September 2022, Frosty Toolsuite is open source on [GitHub](https://github.com/CadeEvs/FrostyToolsuite). I highly recommend that tool for most Frostbite games.
- [FIFA Editor Tool](https://www.fifaeditortool.com/) development team. This tool adds support to compile to FIFA Mod Manager *.fifamod files.
- [DirectXTexNet](https://github.com/deng0/DirectXTexNet) - Used library and rewrote parts for latest Chunk File Collection texture import [LICENSE](https://raw.githubusercontent.com/deng0/DirectXTexNet/master/LICENSE)
- [CSharpImageLibrary](https://github.com/KFreon/CSharpImageLibrary) - Exceptionally helpful in creating a library for importing/exporting in game images & textures

## Supported Games
### 100% supported
- FIFA 21

### 99% supported - Minor issues
- FIFA 22 (Mesh Import is not working as expected, use [FIFA Editor Tool](https://www.fifaeditortool.com/) to create these mods instead)
- FIFA 23 (Mesh Import is not working as expected, use [FIFA Editor Tool](https://www.fifaeditortool.com/) to create these mods instead)
- EA Sports FC 24 (Mesh Import is not working as expected, use [FIFA Editor Tool](https://www.fifaeditortool.com/) to create these mods instead)

### 25% supported - Likely missing or broken major features
- MADDEN 21

### Read Only Support
- Dead Space (Read only)
- EA Sports PGA Tour (Read only)
- FIFA 17 (Read only)
- Madden NFL 23 (Read only)
- Madden NFL 24 (Read only)
- NFS Unbound (Read only)
- Star Wars Squadrons (Read only)

### Potential to be supported (Plugins, SDK and Profiles may exist but not tested)
- Battlefield 4
- Battlefield 5
- Battlefield 2042
- FIFA 18
- FIFA 19
- FIFA 20
- MADDEN 20
- MADDEN 22
