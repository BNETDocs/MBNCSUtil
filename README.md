# MBNCSUtil
**MBNCSUtil** (**M**anaged **BNCS** **U**tilities) provides Battle.net authentication services for managed applications.

[![GitHub watchers](https://img.shields.io/github/watchers/BNETDocs/MBNCSUtil?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/watchers)
[![GitHub Repo stars](https://img.shields.io/github/stars/BNETDocs/MBNCSUtil?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/BNETDocs/MBNCSUtil?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/network/members)
![GitHub contributors](https://img.shields.io/github/contributors/BNETDocs/MBNCSUtil?style=for-the-badge)

[![GitHub top language](https://img.shields.io/github/languages/top/BNETDocs/MBNCSUtil?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/search?l=c%23)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/BNETDocs/MBNCSUtil?style=for-the-badge)
[![GitHub Workflow Status (develop)](https://img.shields.io/github/workflow/status/BNETDocs/MBNCSUtil/.NET%20Core/develop?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/actions?query=workflow%3A%22.NET%20Core%22)

[![GitHub All Releases](https://img.shields.io/github/downloads/BNETDocs/MBNCSUtil/total?style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/releases/latest)
[![GitHub release (latest SemVer including pre-releases)](https://img.shields.io/github/v/release/BNETDocs/MBNCSUtil?include_prereleases&label=latest%20release&style=for-the-badge)](https://github.com/BNETDocs/MBNCSUtil/releases/latest)

## Authors

* Originally written by: [@robpaveza](https://github.com/robpaveza) a.k.a. MyndFyre, adapted from original [BNCSUtil](https://github.com/BNETDocs/bncsutil) source code at request of its author.
* Adapted to .NET Core 3.1 by: [@carlbennett](https://github.com/carlbennett) a.k.a. Caaaaarrrrlll, [@wjlafrance](https://github.com/wjlafrance) a.k.a. joe)x86(
* Special thanks to: [BNETDocs](https://bnetdocs.org)
* Honorable mention to: Valhalla Legends (a.k.a. vL), x86

## Setup

### Requirements

MBNCSUtil is built on the .NET Core 3.1 platform. Linux users may wish to install the Mono package which provides a `dotnet` commandline.

### Download

Go to [Releases](https://github.com/BNETDocs/MBNCSUtil/releases/latest) and download the correct package for your platform, or build from source if you're savvy enough.

### Compile from source

#### Windows

Users on the Windows platform must install Microsoft Visual Studio 2019 (or equivalent) which provides .NET Core 3.1 development SDK.

#### Linux

For Fedora or other Red Hat based systems:

1. Install .NET: `sudo dnf install dotnet`
2. Clone this repository: `git clone https://github.com/BNETDocs/MBNCSUtil.git`
3. Change directory: `cd MBNCSUtil/`
4. Build source: `dotnet build`
5. Run debugger: `dotnet run`
6. See `dotnet --help` for other compile options

## License

Copyright © Robert Paveza, 2005-2008. Adapted from BNCSUtil at the request of the author. Licensed under the modified BSD license. See [LICENSE.txt](./LICENSE.txt) for licensing details. Blizzard, Battle.net, Starcraft, Warcraft, Warcraft II: Battle.net Edition, The Tides of Darkness, Into the Dark Portal, Diablo, The Lord of Destruction, Brood War, The Reign of Chaos, and The Frozen Throne are trademarks or registered trademarks of Blizzard Entertainment Inc. in the United States and/or other countries. Other marks may be the trademarks or registered trademarks of their respective owners.
