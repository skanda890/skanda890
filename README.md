# About My GitHub Account

- **Username**: skanda890 (also known as SkandaBT)
- **Location**: Sanjaynagar, Bangalore, Karnataka, India (UTC +05:30)
- **Hobbies**: Playing Football, Rock collecting and Coding

## Some of The Repositories I Have Forked or Created

1. **UnigetUI**
   # <img src="https://raw.githubusercontent.com/marticliment/WingetUI/main/src/wingetui/Assets/Images/icon.png" height="40">WingetUI (soon UniGetUI)

[![Downloads@latest](https://img.shields.io/github/downloads/marticliment/WingetUI/2.2.0/total?style=for-the-badge)](https://github.com/marticliment/WingetUI/releases/latest/download/WingetUI.Installer.exe)
[![Release Version Badge](https://img.shields.io/github/v/release/marticliment/WingetUI?style=for-the-badge)](https://github.com/marticliment/WingetUI/releases)
[![Issues Badge](https://img.shields.io/github/issues/marticliment/WingetUI?style=for-the-badge)](https://github.com/marticliment/WingetUI/issues)
[![Closed Issues Badge](https://img.shields.io/github/issues-closed/marticliment/WingetUI?color=%238256d0&style=for-the-badge)](https://github.com/marticliment/WingetUI/issues?q=is%3Aissue+is%3Aclosed)<br>

The main goal of this project is to create an intuitive GUI for the most common CLI package managers for Windows 10 and Windows 11, such as [Winget](https://learn.microsoft.com/en-us/windows/package-manager/), [Scoop](https://scoop.sh/), [Chocolatey](https://chocolatey.org/), [Pip](https://pypi.org/), [Npm](https://www.npmjs.com/), [.NET Tool](https://learn.microsoft.com/en-us/dotnet/core/tools/dotnet-tool-install) and [PowerShell Gallery](https://www.powershellgallery.com/).
With this app, you'll be able to easily download, install, update and uninstall any software that's published on the supported package managers — and much more!

Check out the [Supported Package Managers Table](#supported-package-managers) for more details!

**This is WingetUI's official repository. If you are searching for WingetUI's homepage, please refer to [https://www.marticliment.com/wingetui/](https://www.marticliment.com/wingetui/)**

**Disclaimer:** This project has no connection with any of the supported package managers — it's completely unofficial. Be aware of the fact that I, the developer of WingetUI, am NOT responsible for the downloaded apps.

![Endpoint Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fmarticliment.com%2Fresources%2Fbadges%2Fdev-status.json)
 
## Table of contents
 - **[WingetUI Homepage](https://www.marticliment.com/wingetui/)**
 - [Table of contents](#table-of-contents)
 - [Installation](#installation)
 - [Update WingetUI](#update-wingetui)
 - [Support the developer](#support-the-developer)
 - [Features](#features)
   - [Supported Package Managers](#supported-package-managers)
 - [Translating WingetUI](#translating-wingetui-to-other-languages)
   - [Currently supported languages](#currently-supported-languages)
 - [Contributors](#contributors)
 - [Screenshots](#screenshots)
 - [Frequently Asked Questions](#frequently-asked-questions)

 
## Installation
<p>There are multiple ways to install WingetUI — choose whichever one you prefer!<br</p>

**Download WingetUI installer (recommended):**
<p align="left"><b><a href="https://github.com/marticliment/WingetUI/releases/latest/download/WingetUI.Installer.exe">Click here to download WingetUI</a></b></p>

**Install WingetUI through Winget:**    
```cmd
winget install SomePythonThings.WingetUIStore
```

**Install WingetUI through Scoop:**
```cmd
scoop bucket add extras
```
```cmd
scoop install wingetui
```

**Install WingetUI through Chocolatey:**    
```cmd
choco install wingetui
```


## Update WingetUI

WingetUI has a built-in autoupdater. However, it can also be updated like any other package within WingetUI (since WingetUI is available through Winget and Scoop).


## Support the developer

It really does make a big difference, and is very much appreciated. Thanks :)

<a href='https://ko-fi.com/martinet101' target='_blank'><img style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>


## Features

 - Install, update and remove software from your system easily at one click: WingetUI combines the packages from the most used package managers for windows: Winget, Chocolatey, Scoop, Pip, Npm and .NET Tool.
 - Discover new packages and filter them to easily find the package you want.
 - View detailed metadata about any package before installing it. Get the direct download URL or the name of the publisher, as well as the size of the download.
 - Easily bulk-install, update or uninstall multiple packages at once selecting multiple packages before performing an operation
 - Automatically update packages, or be notified when updates become available. Skip versions or completely ignore updates in a per-package basis.
 - Manage your available updates at the touch of a button from the **Widgets pane** or from **Dev Home** pane with [WingetUI Widgets](https://apps.microsoft.com/detail/9NB9M5KZ8SLX)*.
 - The system tray icon will also show the available updates and installed package, to efficiently update a program or remove a package from your system.
 - Easily customize how and where packages are installed. Select different installation options and switches for each package. Install an older version or force to install a 32bit architecture. \[But don't worry, those options will be saved for future updates for this package*]
 - Share packages with your friends to show them off that program you found. Here is an example: [Hey \@friend, Check out this program!](https://marticliment.com/wingetui/share/?pname=Google%20Chrome&pid=Google.Chrome&psource=Winget:%20winget)
 - Export custom lists of packages to then import them to another machine and install those packages with previously-specified, custom installation parameters. Setting up machines or configuring a specific software setup has never been easier.
 - Backup your packages to a local file to easily recover your setup in a matter of seconds when migrating to a new machine*

## Supported Package Managers

**NOTE:** All package managers do support basic install, update and uninstall processes, as well as checking for updates, finding new packages and retrieving details from a package.

| Manager | Skip integrity checks | Interactive installation | Install Older Versions | Install a PreRelease Version | Install a Custom Architecture | Install on a Custom Scope | Custom Install Location | Custom Package Sources | Supported since |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Winget** | ✅ | ⚠️³ | ✅ | ☑️² | ✅ | ⚠️¹ | ⚠️¹ | ✅ | 0.1.0 |
| **Scoop** | ✅ | ❌ | ❌ | ☑️² | ✅ | ✅ | ❌ | ✅ | 0.1.0 |
| **Chocolatey** | ✅ | ⚠️³ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | 1.6.0 |
| **Npm** | ❌ | ❌ | ✅ | ❌ | ❌ | ✅ | ❌ | ❌ | 2.0.0 |
| **Pip** | ❌ | ❌ | ✅ | ✅ | ❌ | ✅ | ❌ | ❌ | 2.0.0 |
| **.NET Tool** | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ | ❌ | ❌ | 2.1.0 |
| **PowerShell** | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ❌ | ✅ | 2.2.0 |

✅: Supported on WingetUI<br>
☑️: Not directly supported but can be easily achieved<br>
⚠️: Some packages might not follow this setting<br>
❌: Not supported by the Package Manager<br>
<br>
**1\.** Some packages do not support installing to a custom location or scope and will ignore this setting<br>
**2\.** Despite the Package Manager may not support _PreReleases_, some packages can be found duplicated, with one of the copies being the beta version of it.<br>
**3\.** Some installers do not have a GUI, and will ignore the `interactive` flag<br>

# Translating WingetUI to other languages
In order to translate WingetUI to other languages or to update an old translation, please see [Translating WingetUI - WingetUI Wiki](https://github.com/marticliment/WingetUI/wiki#translating-wingetui) for more info.


## Currently Supported languages
<!-- Autogenerated translations -->
| Language | Translated | Translator(s) |
| :-- | :-- | --- |
| <img src='https://flagcdn.com/sa.svg' width=20> &nbsp; Arabic - عربي‎ | 80% | [Abdu11ahAS](https://github.com/Abdu11ahAS), [Abdullah-Dev115](https://github.com/Abdullah-Dev115), [FancyCookin](https://github.com/FancyCookin), [mo9a7i](https://github.com/mo9a7i) |
| <img src='https://flagcdn.com/bg.svg' width=20> &nbsp; Bulgarian - български | 63% | Vasil Kolev |
| <img src='https://flagcdn.com/bd.svg' width=20> &nbsp; Bangla - বাংলা | 87% | [fluentmoheshwar](https://github.com/fluentmoheshwar), [itz-rj-here](https://github.com/itz-rj-here), Mushfiq Iqbal Rayon, Nilavra Bhattacharya |
| <img src='https://flagcdn.com/ad.svg' width=20> &nbsp; Catalan - Català | 100% | [marticliment](https://github.com/marticliment) |
| <img src='https://flagcdn.com/cz.svg' width=20> &nbsp; Czech - Čeština | 100% | [mlisko](https://github.com/mlisko), [panther7](https://github.com/panther7) |
| <img src='https://flagcdn.com/dk.svg' width=20> &nbsp; Danish - Dansk | 79% | [AAUCrisp](https://github.com/AAUCrisp), [mikkolukas](https://github.com/mikkolukas), [yrjarv](https://github.com/yrjarv) |
| <img src='https://flagcdn.com/de.svg' width=20> &nbsp; German - Deutsch | 100% | [1270o1](https://github.com/1270o1), [alxhu-dev](https://github.com/alxhu-dev), [CanePlayz](https://github.com/CanePlayz), [Datacra5H](https://github.com/Datacra5H), [ebnater](https://github.com/ebnater), [michaelmairegger](https://github.com/michaelmairegger), [Seeloewen](https://github.com/Seeloewen), [yrjarv](https://github.com/yrjarv) |
| <img src='https://flagcdn.com/gr.svg' width=20> &nbsp; Greek - Ελληνικά | 99% | [antwnhsx](https://github.com/antwnhsx), [thunderstrike116](https://github.com/thunderstrike116), [wobblerrrgg](https://github.com/wobblerrrgg) |
| <img src='https://flagcdn.com/gb.svg' width=20> &nbsp; English - English | 100% | [marticliment](https://github.com/marticliment), [ppvnf](https://github.com/ppvnf) |
| <img src='https://flagcdn.com/es.svg' width=20> &nbsp; Spanish - Castellano | 100% | [apazga](https://github.com/apazga), [dalbitresb12](https://github.com/dalbitresb12), [evaneliasyoung](https://github.com/evaneliasyoung), [guplem](https://github.com/guplem), [JMoreno97](https://github.com/JMoreno97), [marticliment](https://github.com/marticliment), [rubnium](https://github.com/rubnium), [uKER](https://github.com/uKER) |
| <img src='https://flagcdn.com/ir.svg' width=20> &nbsp; Persian - فارسی‎ | 66% | [Imorate](https://github.com/Imorate), [itsarian](https://github.com/itsarian), [Mahdi-Hazrati](https://github.com/Mahdi-Hazrati), [smsi2001](https://github.com/smsi2001) |
| <img src='https://flagcdn.com/fi.svg' width=20> &nbsp; Finnish - Suomi | 1% |  |
| <img src='https://flagcdn.com/fr.svg' width=20> &nbsp; French - Français | 100% | BreatFR, Evans Costa, [PikPakPik](https://github.com/PikPakPik), Rémi Guerrero, [W1L7dev](https://github.com/W1L7dev) |
| <img src='https://flagcdn.com/in.svg' width=20> &nbsp; Hindi - हिंदी | 56% | [atharva_xoxo](https://github.com/atharva_xoxo), [satanarious](https://github.com/satanarious) |
| <img src='https://flagcdn.com/hr.svg' width=20> &nbsp; Croatian - Hrvatski | 60% | Stjepan Treger |
| <img src='https://flagcdn.com/il.svg' width=20> &nbsp; Hebrew - עִבְרִית‎ | 50% | Oryan |
| <img src='https://flagcdn.com/hu.svg' width=20> &nbsp; Hungarian - Magyar | 100% | [gidano](https://github.com/gidano) |
| <img src='https://flagcdn.com/it.svg' width=20> &nbsp; Italian - Italiano | 100% | David Senoner, [giacobot](https://github.com/giacobot), [maicol07](https://github.com/maicol07), [mapi68](https://github.com/mapi68), [mrfranza](https://github.com/mrfranza), Rosario Di Mauro, [supertost100](https://github.com/supertost100) |
| <img src='https://flagcdn.com/id.svg' width=20> &nbsp; Indonesian - Bahasa Indonesia | 88% | [arthackrc](https://github.com/arthackrc), [joenior](https://github.com/joenior) |
| <img src='https://flagcdn.com/jp.svg' width=20> &nbsp; Japanese - 日本語 | 91% | [nob-swik](https://github.com/nob-swik), sho9029, [tacostea](https://github.com/tacostea), Yuki Takase |
| <img src='https://flagcdn.com/kr.svg' width=20> &nbsp; Korean - 한국어 | 82% | [minbert](https://github.com/minbert), [shblue21](https://github.com/shblue21) |
| <img src='https://flagcdn.com/mk.svg' width=20> &nbsp; Macedonian - Македонски | 66% | LordDeatHunter |
| <img src='https://flagcdn.com/no.svg' width=20> &nbsp; Norwegian (bokmål) | 99% | [yrjarv](https://github.com/yrjarv) |
| <img src='https://flagcdn.com/no.svg' width=20> &nbsp; Norwegian (nynorsk) | 99% | [yrjarv](https://github.com/yrjarv) |
| <img src='https://flagcdn.com/nl.svg' width=20> &nbsp; Dutch - Nederlands | 100% | [abbydiode](https://github.com/abbydiode), [Stephan-P](https://github.com/Stephan-P) |
| <img src='https://flagcdn.com/pl.svg' width=20> &nbsp; Polish - Polski | 99% | [KamilZielinski](https://github.com/KamilZielinski), [kwiateusz](https://github.com/kwiateusz), [RegularGvy13](https://github.com/RegularGvy13) |
| <img src='https://flagcdn.com/br.svg' width=20> &nbsp; Portuguese (Brazil) | 99% | [maisondasilva](https://github.com/maisondasilva), [ppvnf](https://github.com/ppvnf), [Rodrigo-Matsuura](https://github.com/Rodrigo-Matsuura), [wanderleihuttel](https://github.com/wanderleihuttel) |
| <img src='https://flagcdn.com/pt.svg' width=20> &nbsp; Portuguese (Portugal) | 100% | [PoetaGA](https://github.com/PoetaGA), [Tiago_Ferreira](https://github.com/Tiago_Ferreira) |
| <img src='https://flagcdn.com/ro.svg' width=20> &nbsp; Romanian - Română | 99% | [SilverGreen93](https://github.com/SilverGreen93), TZACANEL |
| <img src='https://flagcdn.com/ru.svg' width=20> &nbsp; Russian - Русский | 98% | [bropines](https://github.com/bropines), [DvladikD](https://github.com/DvladikD), [flatron4eg](https://github.com/flatron4eg), [katrovsky](https://github.com/katrovsky), Sergey, sklart |
| <img src='https://flagcdn.com/rs.svg' width=20> &nbsp; Serbian - Srpski | 70% | [daVinci13](https://github.com/daVinci13), Nemanja Djurcic |
| <img src='https://flagcdn.com/lk.svg' width=20> &nbsp; Sinhala - සිංහල | 6% | [SashikaSandeepa](https://github.com/SashikaSandeepa) |
| <img src='https://flagcdn.com/si.svg' width=20> &nbsp; Slovene - Slovenščina | 100% | [rumplin](https://github.com/rumplin) |
| <img src='https://flagcdn.com/ph.svg' width=20> &nbsp; Tagalog - Tagalog | 15% | lasersPew |
| <img src='https://flagcdn.com/th.svg' width=20> &nbsp; Thai - ภาษาไทย | 70% | [apaeisara](https://github.com/apaeisara), [dulapahv](https://github.com/dulapahv) |
| <img src='https://flagcdn.com/tr.svg' width=20> &nbsp; Turkish - Türkçe | 99% | [ahmetozmtn](https://github.com/ahmetozmtn), [dogancanyr](https://github.com/dogancanyr), [gokberkgs](https://github.com/gokberkgs) |
| <img src='https://flagcdn.com/ua.svg' width=20> &nbsp; Ukranian - Yкраї́нська | 59% | Artem Moldovanenko, Operator404 |
| <img src='https://flagcdn.com/vn.svg' width=20> &nbsp; Vietnamese - Tiếng Việt | 99% | [legendsjoon](https://github.com/legendsjoon), [txavlog](https://github.com/txavlog) |
| <img src='https://flagcdn.com/cn.svg' width=20> &nbsp; Simplified Chinese (China) | 100% | Aaron Liu, adfnekc, [arthurfsy2](https://github.com/arthurfsy2), [bai0012](https://github.com/bai0012), BUGP Association, ciaran, CnYeSheng, Cololi, [FloatStream](https://github.com/FloatStream), [SpaceTimee](https://github.com/SpaceTimee), Yisme |
| <img src='https://flagcdn.com/tw.svg' width=20> &nbsp; Traditional Chinese (Taiwan) | 85% | Aaron Liu, CnYeSheng, Cololi, [Henryliu880922](https://github.com/Henryliu880922), [yrctw](https://github.com/yrctw) |

Last updated: Fri Apr  5 00:11:00 2024
<!-- END Autogenerated translations -->


# Contributions
 WingetUI wouldn't have been possible without the help of our dear contributors. From the person who fixed a typo to the person who improved half of the code, WingetUI wouldn't be possible without them! :smile:<br><br>

## Contributors:
 [![My dear contributors](https://contrib.rocks/image?repo=marticliment/WingetUI)](https://github.com/marticliment/WingetUI/graphs/contributors)<br><br>
 

# Screenshots
 
![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_1.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_2.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_3.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_4.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_5.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_6.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_7.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_8.png)

![image](https://raw.githubusercontent.com/marticliment/WingetUI/main/media/winget_9.png)


# Frequently asked questions

**Q: I am unable to install or upgrade a specific Winget package! What should I do?**<br>

A: This is likely an issue with Winget rather than WingetUI. 

Please check if it's possible to install/upgrade the package through PowerShell or the Command Prompt by using the commands `winget upgrade` or `winget install`, depending on the situation (for example: `winget upgrade --id Microsoft.PowerToys`). 

If this doesn't work, consider asking for help at [Winget's own project page](https://github.com/microsoft/winget-cli).<br>

#

**Q: The name of a package is trimmed with ellipsis — how do I see its full name/id?**<br>

A: This is a known limitation of Winget. 

See more details on issue https://github.com/microsoft/winget-cli/issues/2603.<br>

#

**Q: My antivirus is telling me that WingetUI is a virus! / My browser is blocking the download of WingetUI!**<br>

A: A common reason apps (i.e., executables) get blocked and/or detected as a virus — even when there's nothing malicious about them, like in the case of WingetUI — is because they're not being used by a relatively large amount of people.

Combine that with the fact that you might be downloading something recently released, and simply blocking unknown apps is in many cases a good precaution to take to prevent actual malware.

Since WingetUI is open source and safe to use, simply whitelist the app in the settings of your antivirus/browser.<br>

#

**Q: Are Winget/Scoop packages safe?**<br>

A: WingetUI, Microsoft and Scoop aren't responsible for the packages available for download, which are provided by third parties and can theoretically be compromised.

To mitigate the risks of downloading malware, Microsoft has implemented a few checks for the software available on Winget. Even so, It's recommended to only download software from publishers that you trust. 

<br><p align="center"><i>Check out the <a href="https://github.com/marticliment/WingetUI/wiki">Wiki</a> for more information!</i></p>

## Command-line parameters:
`--daemon`: Start WingetUI without spawning a new window. WingetUI will run minimized on the system tray. WingetUI is called with this parameter when launched at startup. **Autostart WingetUI in the notifications area** must be enabled for this parameter to work.<br>
`--welcomewizard` (or simply `--welcome`): Show a window to choose which package managers to use.<br>
`--updateapps`: Enable automatic installation of available updates.
`--report-all-errors`: May help debug crashes (WingetUI 3.0 and newer)

### Installer command-line parameters:
The installer is inno-setup based, so it supports regular Inno Setup command-line parameters. Additionally, it also supports the following parameters:
 <br>`/NoAutoStart`: Will not launch WingetUI after installing it.
<br> `/ALLUSERS`: Install WingetUI for every user
<br> `/CURRENTUSER`: Install WingetUI for the current user only

2. **CodePark**
    - A personal repository made by skanda890.

3. **Dev Home**
s![dev-home-readme-header](https://github.com/microsoft/devhome/blob/main/src/Assets/Preview/StoreDisplay-150.png)

# Welcome to the Dev Home repo!

Dev Home is a new experience from Microsoft aiming to give developers more power on Windows.

This repository contains the source code for:

* [Dev Home](https://aka.ms/devhome)
* Dev Home core widgets

Related repositories include:

* [Dev Home GitHub Extension](https://github.com/microsoft/devhomegithubextension)
* [Dev Home Azure Extension](https://github.com/microsoft/devhomeazureextension)

## Installing and running Dev Home

> **Note**: Dev Home requires Windows 11 21H2 (build 22000) or later.

If you are running Windows 11 23H2 (build 22621.2361) or later, you can install and run Dev Home just by finding it in the Start menu.

Otherwise, you can install [Dev Home from the Microsoft Store](https://aka.ms/devhome).
This allows you to always be on the latest version when we release new builds with automatic upgrades. Note that widgets may not work on older versions of Windows.

This is our preferred method.

### Other install methods

#### Via GitHub

For users who are unable to install Dev Home from the Microsoft Store, released builds can be manually downloaded from this repository's [Releases page](https://github.com/microsoft/devhome/releases).

#### Via Windows Package Manager CLI (aka winget)

[winget](https://github.com/microsoft/winget-cli) users can download and install the latest Dev Home release by installing the `Microsoft.DevHome` package:

```powershell
winget install --id Microsoft.DevHome -e
```

---

## Dev Home roadmap

The plan for Dev Home can be found in our [roadmap](docs/roadmap.md).

---

## Dev Home overview

Please take a few minutes to review the overview below before diving into the code:

### Dashboard

The Dev Home dashboard displays Windows widgets. These widgets are built using the Windows widget platform, which relies on Adaptive Cards.

### Machine configuration

The machine configuration tool utilizes the Dev Home GitHub Extension, but isn't required to clone and install apps. The app installation tool is powered by winget.

#### Popular apps

The machine configuration tool provides a list of popular apps when selecting applications to install. This is currently a hard-coded list of applications that have been popular with developers on Windows. Popularity was determined by high levels of installation and usage. As this is a moment in time, we are not accepting submissions for this list. We're looking to improve the experience with [Suggested Apps](https://github.com/microsoft/devhome/issues/375) so the list can be optimized for developers.

---

## Documentation

Documentation for Dev Home can be found at https://aka.ms/devhomedocs.

---

## Contributing

We are excited to work alongside you, our amazing community, to build and enhance Dev Home!

***BEFORE you start work on a feature/fix,*** please read & follow our [Contributor's Guide](CONTRIBUTING.md) to help avoid any wasted or duplicate effort.

## Communicating with the team

The easiest way to communicate with the team is via GitHub issues.

Please file new issues, feature requests, and suggestions but **DO search for similar open/closed preexisting issues before creating a new issue.**

If you would like to ask a question that you feel doesn't warrant an issue (yet), please reach out to us via Twitter:

* [Kayla Cinnamon](https://github.com/cinnamon-msft), Senior Product Manager: [@cinnamon_msft](https://twitter.com/cinnamon_msft)
* [Clint Rutkas](https://github.com/crutkas), Principal Product Manager: [@clintrutkas](https://twitter.com/clintrutkas) 
* [Leeza Mathew](https://github.com/mathewleeza), Engineering Lead: [@leezamathew](https://twitter.com/leezamathew)

## Developer guidance

* You must be running Windows 11 21H2 (build >= 10.0.22000.0) to run Dev Home
* You must [enable Developer Mode in the Windows Settings app](https://docs.microsoft.com/en-us/windows/uwp/get-started/enable-your-device-for-development)

## Building the code

1. Clone the repository
2. Configure your system
   * Please use the [configuration file](.configurations/configuration.dsc.yaml). This can be applied by either:
     * Dev Home's machine configuration tool
     * WinGet configuration. If you have WinGet version [v1.6.2631 or later](https://github.com/microsoft/winget-cli/releases), run `winget configure .configurations/configuration.dsc.yaml` in an elevated shell from the project root so relative paths resolve correctly
   * Alternatively, if you already are running the minimum OS version, have Visual Studio installed, and have developer mode enabled, you may configure your Visual Studio directly via the .vsconfig file. To do this:
     * Open the Visual Studio Installer, select “More” on your product card and then "Import configuration"
     * Specify the .vsconfig file at the root of the repo and select “Review Details”

## Running & debugging

In Visual Studio, you should be able to build and debug Dev Home by hitting <kbd>F5</kbd>. Make sure to select either the `x64` or the `x86` platform and set DevHome as the selected startup project.

---

## Code of conduct

We welcome contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos is subject to those third-parties' policies.

## Thanks to our contributors

<a href="https://github.com/microsoft/devhome/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=microsoft/devhome" />
</a>

4.**MSEdge**

# Microsoft Edge and Chromium Open Source: Our Intent
Authors: Microsoft Edge Team
Last Updated: 2018-12-06

## Why this document 
For the past few years, Microsoft has meaningfully increased participation in the open source software (OSS) community, becoming one of the world’s largest supporters of OSS projects. We are starting down a path to adopt Chromium open source in the development of Microsoft Edge on the desktop, becoming a larger contributor and user of its open source so that we can create better web compatibility for our customers and less fragmentation of the web for all web developers. 

**This document exists to clarify our thinking on how that work will proceed**: we want to explain our plans and intentions related to Microsoft Edge and the Chromium open-source project. The audiences we think will find this document most relevant and useful are (a) the people working on Chromium as approvers/maintainers and leading that project (b) the companies and engineers who build other browsers and will be interested in the contributions we plan to make, and (c) the broader community of web developers, corporate IT managers and partners we work with on Windows and Microsoft Edge. And of course, we and all those audiences care primarily about the end-user, who is ultimately the audience this work is intended to benefit.

### TL;DR
Working with open source is not new for Microsoft Edge. Our new mobile browser has been based on open source from its beginnings over a year ago. We’ve also used open source for various features of Microsoft Edge on the desktop (e.g. ANGLE, Web Audio, Brotli) and we’ve begun making contributions to the Chromium project to help move browsing forward on new ARM-based Windows devices. In that context, we have been thinking through plans to adopt the Chromium open source project in the development of Microsoft Edge on the desktop to create better web-compatibility for our customers and less fragmentation of the web for all its developers, and we’re now ready to move forward.

As part of this, we hope and intend to become a significant contributor to Chromium, in a way that can make not just Microsoft Edge - but other browsers as well - better on both PCs and other devices. We’ve written down our “OSS Principles for Microsoft Edge” below and “What Happens Next” to clearly outline our approach to contributions.

Our plan is to engage in a way that embraces the well-established open source model that’s been working effectively for years: meaningful and positive contributions which align with long-standing thoughtfully-designed architecture, collaborative engineering, and keeping in mind that we, together as a community, seek the best outcome for all people who use the web across many devices.

## Microsoft and The Web Today 
Our *intent* is profoundly informed by our context. Historically, Microsoft has focused on three primary constituencies: end-users, developers, and enterprises/organizations. These audiences have informed the investments we have made in Internet Explorer in the past, and now inform the investments we make in Microsoft Edge. As we have listened to these customers over the last few years, a consistent theme they echo is the increased complexity of their environments, and a desire for consistency, simplicity, reliability, compatibility. 

We have effectively partnered with Google and other browser vendors over the years, first in the W3C and now even more closely through the WHATWG, to create common standards for the web platform to reduce this complexity and to improve the overall web experience. While browser vendors across the industry have made significant progress in aligning to these common standards, the underlying implementations and differing release schedules have created difficulties for our developers to fully benefit from the promises of the open web.

We see an opportunity now to move forward in a deeper way on a common compatible web platform that will serve Microsoft’s customers well and will provide mutual benefit for the larger web community while maintaining the marketplace benefits of competitive diversity in the browser ecosystem. Consider the following opportunities as we view them across our customer segments:

* *End-users* - Although Microsoft Edge has very high web compatibility for both standards-based HTML and for capabilities added by highly-used browsers like Chrome, our unique web-platform codebase still faces occasional compatibility problems as web developers focus less on HTML standards and rationally focus on widely used platforms like Chrome to develop and validate experiences for their customers. While we work hard to make updates and fix these issues continuously, our implementation of Microsoft Edge as a component that ships solely on the same schedule as the full Windows operating system has slowed our ability to update, causing platform fragmentation and exposing compatibility gaps. We think greater use of open source software (OSS) can improve this experience for our end-users. 

* Outside the Microsoft Edge browser, users of *other browsers* on Windows PCs sometimes face inconsistent feature-sets and performance/battery-life across device types. Some browsers have had slower-progress to embrace new Windows capabilities like touch and ARM processors. As you know, we’ve recently started making contributions that provide these types of hardware support to Chromium-based browsers, and we believe that this approach can be generalized: we think we can help to accelerate the web and users’ experience of it by contributing new capabilities to Chromium open source for the benefit of all these browsers and users.

* *Developers* – as the web has grown in usage across an ever-widening array of device-types, the complexity and overhead involved in testing web-sites have exploded. Since web developers - particularly those at small companies - need to test so many different systems, it’s nearly impossible to ensure that interesting sites will work well across all device types and all browsers. We hope to simplify this matrix for web developers by aligning Microsoft Edge web-platform with other Chromium-browsers and to provide meaningful, aligned capabilities on Windows that can be used by any browser.

* *Corporate IT* - IT managers face the downstream-complexity of users with many different device types, using both new and old sites, on devices owned both personally and by the corporation. We see meaningful value in creating better web compatibility and an aligned web-platform across browsers for Corp IT, regardless of device platform.

*What’s common across all these audiences is the two-sided benefit we believe we can bring them when we (a) engineer valuable new capabilities into a shared open-source project, for the benefit of multiple browsers, and (b) increasingly use that shared open-source ourselves in the browser we distribute at scale. We intend to do both of these.*

### Recent Investments in Web-focused Open Source
Over the last year, we’ve started to engage in the Chromium and WebRTC open source projects (among other OSS areas more broadly at Microsoft), and our efforts have been ramping up as we consider a wider range of device types. Some examples include…

* **Porting Chromium to ARM64**: We’ve done significant work in collaboration with Google engineers to enable Chromium-based browsers to compile and run natively on Windows on ARM devices. Because of our engineering investment, Chromium-based browsers will soon be able to ship native implementations for ARM-based Windows PCs, which significantly improves their performance and battery life. This is a great example of us making investments in Chromium to move-forward the web experience across a range of browsers on these new types of PCs.

* **Enabling WebRTC to work for Windows UWP apps**: For more than a year, we have been working on [WebRTC for Universal Windows Platform (UWP)](https://github.com/webrtc-uwp/webrtc-uwp-sdk). This offers developers a WebRTC solution for all our Windows 10 platforms, including desktop, Xbox, HoloLens/VR and IoT. Last week, we announced our agreement with Google to push the UWP fork of WebRTC Lib back to the WebRTC.org repo. 

* **Improving ANGLE**: In the past, we have made improvements to ANGLE’s D3D11 backend and improve its performance. More recently, we collaborated with Intel and the ANGLE team on additional improvements to make ANGLE the official backend for WebGL in Microsoft Edge. 

We recognize that these are modest-but-still-meaningful examples of web-oriented open source contributions. Both have provided us with a valuable perspective on how we can collaboratively use and contribute to Chromium in a healthy way. Across Microsoft, our OSS expertise and focus has grown – and our web teams are excited to take these lessons and move the web experience for millions of people forward.

## Microsoft Edge + open source: a new direction for Microsoft
Getting down to brass tacks ... we have put this document together to be transparent to relevant OSS contributors and partners about our intent.

### Use of OSS in the Microsoft Edge Browser
While we’ve been consumers of Chromium open source for shipping our Microsoft Edge mobile browser and for some components of Microsoft Edge desktop, we’ve made the decision to move much more of Microsoft Edge desktop to use Chromium open source and to increase our contributions back to this community. 

The key aspects of this evolution in direction for Microsoft Edge are: 

1. *We will adopt Chromium as the web platform for Microsoft Edge desktop*. Our desire here is to align Microsoft Edge’s web platform both (a) with web standards and (b) with other Chromium-based browsers, for improved compatibility and a simpler test-matrix for developers.

2. *We will evolve the Microsoft Edge app architecture, enabling distribution to all supported versions of Windows including Windows 7 and Windows 8, as well as Windows 10. We will also bring Microsoft Edge to other desktop platforms, such as macOS*. Improving the web experience for end-users (better compatibility) and developers (less fragmentation) requires a consistent web-platform as widely available as possible. To accomplish this, we will use Chromium’s cross-platform app-technology along with a change in our distribution model, so that the Microsoft Edge experience and web-platform become available across all supported operating systems.

3. *We will offer our Windows platform expertise to improve the experience of all Chromium-based browsers on Windows*. Our philosophy of greater participation in Chromium open source will embrace the contribution of beneficial new tech, consistent with some of the work we described above. We recognize that making the web better on Windows is good for our customers, partners and our business – and we intend to actively contribute to that end. We welcome the opportunity to partner with the Chromium community in the areas of battery life, touch, accessibility, security, and other areas of mutual interest.

### Our contributions: Principles and expectations 
A key goal in providing this document to the teams and people who are already immersed in Chromium OSS is to indicate how we plan to contribute and to kick-start the engineering planning needed to bring valuable new tech into Chromium browsers.

We're excited to engage more deeply with the broader Chromium project. This has been a heavily-weighed decision and one that we believe is the right next step. That said, we're taking that step in the spirit of learning. We know we have a lot to learn as we increase our use and contributions to Chromium, and we look forward to engaging and contributing back to the broader community in a collaborative way. We are looking forward to evolving the nature and scope of our involvement over time. 

### Our OSS principles for Microsoft Edge
1. *We are making this decision for the long term*. We expect our engineers to learn and over time become experts in the Chromium project and grow into active and responsible members of the community. We are eager to increase our contributions to the Chromium project and will continue to maintain any contributions we make.

2. *When seeking improvements in the web platform, our default position will be to contribute*. We are focused on delivering a world-class browser with Microsoft Edge through its differentiated user experience features and connected services, but where new platform capabilities are concerned, we will seek a ‘rising tide that floats all boats’. We will get started with bug fixes and meaningful contributions in such areas as ARM64 support, accessibility, security, touch input and power enhancements on Windows.

3. *We recognize and will respect the architecture requirements and engineering approach that are intrinsic in web open-source projects and have made Chromium successful*. There are many aspects that have governed Chromium OSS and other projects: multi-device support, multi-OS support, rigorous real-time engineering, etc. Although our company has historically had a focus on Windows PCs and we believe we can make contributions that improve browsers on Windows, we also understand that web OSS projects embrace a wide range of device-types, including Android, and that contributions must accommodate this device diversity. We will contribute in a way that is consistent with the architectural design that meets Chromium’s cross-platform and cross-device needs. 

4. *We believe the evolution of the open web is best served though the standards communities and the open web benefits from the open debate from a wide variety of perspectives*. We will remain deeply and vigorously engaged in the standards discussions in the context of the W3C, ECMA and the WHATWG where the perspectives of vendors developing competing browsers and the larger web community can be heard and considered. 

### Contribution: Initial Areas of Focus
As we’ve progressed our OSS work and considered the places where our engineering expertise can make the biggest difference for users and developers, we’ve put together an initial list of contribution “areas of focus”. 

We’d like to underscore that we view this list simply as the starting point - some areas where we can learn/practice together and create meaningful value in the Chromium codebase for all its consumers. 

* *ARM64* - Our plans here are to continue/finish the porting work that brings the Chromium codebase to support for ARM-64 and thus browsers can be shipped which support these devices natively. 

* *Accessibility* - To serve the needs of all our customers, we intend to build upon the accessibility of the Chromium codebase by adding Microsoft UI Automation (UIA) interfaces to support Narrator and other assistive technologies on Windows, integrating with Windows Ease of Access settings such as high contrast and caption styling, improving controls accessibility, and supporting caret browsing.

* *PC-hardware evolution* for modern input types (e.g. touch) - We can help improve desktop touch, gesture recognition and scroll/panning smoothness, particularly on newer, more modern Windows devices.

* *Security* - It is, of course, of paramount importance to all browser vendors that web users are kept as safe and secure as possible. In support of this shared goal, we are looking forward to partnering closely with the Chromium Security team and contributing our experience with building secure software in general, and our expertise with the Windows platform, in particular. 

## What Happens Next
This is a big step for Microsoft, for the Microsoft Edge team, and we recognize it will be a big step for the Chromium project as well. We are enthusiastic about the benefit we believe this will bring to the larger web community. We are eager to begin engaging with our counterparts at Google and the other contributors to the Chromium project, and in the Chromium project generally, on how we can move forward together on a common web platform. At the same time, we recognize the value of competition and intend to bring-to-life our best vision for a Microsoft Edge browser that builds on Chromium open source via differentiated user experience features and connected services.

We already have positive working relationships with many Chromium contributors based on our work in the standards bodies and in prior shared engineering efforts. We look forward to building on those relationships and learning-as-we-go how we can best contribute to this implementation of the open web.

To provide a more specific sense of what actions we’ll take with and following this memo, here’s the short-list:
1. We will start by contacting the engineering owners of various parts of the Chromium project to engage on how we can begin contributing in the areas listed above. This includes Google as well as other companies.
2. We will inform other key partners about this evolution in our Microsoft Edge strategy: e.g., WHATWG, the W3C… as well as our OEM partners, high-interaction development partners and others.
3. We’ll make a public announcement via blog post so that the external community of people interested will have a transparent view of our strategy change. 
4. We’ll post this document to GitHub so any interested developer or web-community member can read about our plans directly.

We invite your comments, advice, and feedback as we begin to engage with you on the Chromium project!

5. **Terminal**

   ![terminal-logos](https://github.com/microsoft/terminal/assets/91625426/333ddc76-8ab2-4eb4-a8c0-4d7b953b1179)

# Welcome to the Windows Terminal, Console and Command-Line repo

This repository contains the source code for:

* [Windows Terminal](https://aka.ms/terminal)
* [Windows Terminal Preview](https://aka.ms/terminal-preview)
* The Windows console host (`conhost.exe`)
* Components shared between the two projects
* [ColorTool](./src/tools/ColorTool)
* [Sample projects](./samples)
  that show how to consume the Windows Console APIs

Related repositories include:

* [Windows Terminal Documentation](https://docs.microsoft.com/windows/terminal)
  ([Repo: Contribute to the docs](https://github.com/MicrosoftDocs/terminal))
* [Console API Documentation](https://github.com/MicrosoftDocs/Console-Docs)
* [Cascadia Code Font](https://github.com/Microsoft/Cascadia-Code)

## Installing and running Windows Terminal

> [!NOTE]
> Windows Terminal requires Windows 10 2004 (build 19041) or later

### Microsoft Store [Recommended]

Install the [Windows Terminal from the Microsoft Store][store-install-link].
This allows you to always be on the latest version when we release new builds
with automatic upgrades.

This is our preferred method.

### Other install methods

#### Via GitHub

For users who are unable to install Windows Terminal from the Microsoft Store,
released builds can be manually downloaded from this repository's [Releases
page](https://github.com/microsoft/terminal/releases).

Download the `Microsoft.WindowsTerminal_<versionNumber>.msixbundle` file from
the **Assets** section. To install the app, you can simply double-click on the
`.msixbundle` file, and the app installer should automatically run. If that
fails for any reason, you can try the following command at a PowerShell prompt:

```powershell
# NOTE: If you are using PowerShell 7+, please run
# Import-Module Appx -UseWindowsPowerShell
# before using Add-AppxPackage.

Add-AppxPackage Microsoft.WindowsTerminal_<versionNumber>.msixbundle
```

> [!NOTE]
> If you install Terminal manually:
>
> * You may need to install the [VC++ v14 Desktop Framework Package](https://docs.microsoft.com/troubleshoot/cpp/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages).
>   This should only be necessary on older builds of Windows 10 and only if you get an error about missing framework packages.
> * Terminal will not auto-update when new builds are released so you will need
>   to regularly install the latest Terminal release to receive all the latest
>   fixes and improvements!

#### Via Windows Package Manager CLI (aka winget)

[winget](https://github.com/microsoft/winget-cli) users can download and install
the latest Terminal release by installing the `Microsoft.WindowsTerminal`
package:

```powershell
winget install --id Microsoft.WindowsTerminal -e
```

> [!NOTE]
> Dependency support is available in WinGet version [1.6.2631 or later](https://github.com/microsoft/winget-cli/releases). To install the Terminal stable release 1.18 or later, please make sure you have the updated version of the WinGet client.

#### Via Chocolatey (unofficial)

[Chocolatey](https://chocolatey.org) users can download and install the latest
Terminal release by installing the `microsoft-windows-terminal` package:

```powershell
choco install microsoft-windows-terminal
```

To upgrade Windows Terminal using Chocolatey, run the following:

```powershell
choco upgrade microsoft-windows-terminal
```

If you have any issues when installing/upgrading the package please go to the
[Windows Terminal package
page](https://chocolatey.org/packages/microsoft-windows-terminal) and follow the
[Chocolatey triage process](https://chocolatey.org/docs/package-triage-process)

#### Via Scoop (unofficial)

[Scoop](https://scoop.sh) users can download and install the latest Terminal
release by installing the `windows-terminal` package:

```powershell
scoop bucket add extras
scoop install windows-terminal
```

To update Windows Terminal using Scoop, run the following:

```powershell
scoop update windows-terminal
```

If you have any issues when installing/updating the package, please search for
or report the same on the [issues
page](https://github.com/lukesampson/scoop-extras/issues) of Scoop Extras bucket
repository.

---

## Installing Windows Terminal Canary
Windows Terminal Canary is a nightly build of Windows Terminal. This build has the latest code from our `main` branch, giving you an opportunity to try features before they make it to Windows Terminal Preview.

Windows Terminal Canary is our least stable offering, so you may discover bugs before we have had a chance to find them.

Windows Terminal Canary is available as an App Installer distribution and a Portable ZIP distribution.

The App Installer distribution supports automatic updates. Due to platform limitations, this installer only works on Windows 11.

The Portable ZIP distribution is a portable application. It will not automatically update and will not automatically check for updates. This portable ZIP distribution works on Windows 10 (19041+) and Windows 11.

| Distribution  | Architecture    | Link                                                 |
|---------------|:---------------:|------------------------------------------------------|
| App Installer | x64, arm64, x86 | [download](https://aka.ms/terminal-canary-installer) |
| Portable ZIP  | x64             | [download](https://aka.ms/terminal-canary-zip-x64)   |
| Portable ZIP  | ARM64           | [download](https://aka.ms/terminal-canary-zip-arm64) |
| Portable ZIP  | x86             | [download](https://aka.ms/terminal-canary-zip-x86)   |

_Learn more about the [types of Windows Terminal distributions](https://learn.microsoft.com/windows/terminal/distributions)._

---

## Windows Terminal Roadmap

The plan for the Windows Terminal [is described here](/doc/roadmap-2023.md) and
will be updated as the project proceeds.

## Project Build Status

Project|Build Status
---|---
Terminal|[![Terminal Build Status](https://dev.azure.com/ms/terminal/_apis/build/status/terminal%20CI?branchName=main)](https://dev.azure.com/ms/terminal/_build?definitionId=136)
ColorTool|![Colortool Build Status](https://microsoft.visualstudio.com/_apis/public/build/definitions/c93e867a-8815-43c1-92c4-e7dd5404f1e1/17023/badge)

---

## Terminal & Console Overview

Please take a few minutes to review the overview below before diving into the
code:

### Windows Terminal

Windows Terminal is a new, modern, feature-rich, productive terminal application
for command-line users. It includes many of the features most frequently
requested by the Windows command-line community including support for tabs, rich
text, globalization, configurability, theming & styling, and more.

The Terminal will also need to meet our goals and measures to ensure it remains
fast and efficient, and doesn't consume vast amounts of memory or power.

### The Windows Console Host

The Windows Console host, `conhost.exe`, is Windows' original command-line user
experience. It also hosts Windows' command-line infrastructure and the Windows
Console API server, input engine, rendering engine, user preferences, etc. The
console host code in this repository is the actual source from which the
`conhost.exe` in Windows itself is built.

Since taking ownership of the Windows command-line in 2014, the team added
several new features to the Console, including background transparency,
line-based selection, support for [ANSI / Virtual Terminal
sequences](https://en.wikipedia.org/wiki/ANSI_escape_code), [24-bit
color](https://devblogs.microsoft.com/commandline/24-bit-color-in-the-windows-console/),
a [Pseudoconsole
("ConPTY")](https://devblogs.microsoft.com/commandline/windows-command-line-introducing-the-windows-pseudo-console-conpty/),
and more.

However, because Windows Console's primary goal is to maintain backward
compatibility, we have been unable to add many of the features the community
(and the team) have been wanting for the last several years including tabs,
unicode text, and emoji.

These limitations led us to create the new Windows Terminal.

> You can read more about the evolution of the command-line in general, and the
> Windows command-line specifically in [this accompanying series of blog
> posts](https://devblogs.microsoft.com/commandline/windows-command-line-backgrounder/)
> on the Command-Line team's blog.

### Shared Components

While overhauling Windows Console, we modernized its codebase considerably,
cleanly separating logical entities into modules and classes, introduced some
key extensibility points, replaced several old, home-grown collections and
containers with safer, more efficient [STL
containers](https://docs.microsoft.com/en-us/cpp/standard-library/stl-containers?view=vs-2022),
and made the code simpler and safer by using Microsoft's [Windows Implementation
Libraries - WIL](https://github.com/Microsoft/wil).

This overhaul resulted in several of Console's key components being available
for re-use in any terminal implementation on Windows. These components include a
new DirectWrite-based text layout and rendering engine, a text buffer capable of
storing both UTF-16 and UTF-8, a VT parser/emitter, and more.

### Creating the new Windows Terminal

When we started planning the new Windows Terminal application, we explored and
evaluated several approaches and technology stacks. We ultimately decided that
our goals would be best met by continuing our investment in our C++ codebase,
which would allow us to reuse several of the aforementioned modernized
components in both the existing Console and the new Terminal. Further, we
realized that this would allow us to build much of the Terminal's core itself as
a reusable UI control that others can incorporate into their own applications.

The result of this work is contained within this repo and delivered as the
Windows Terminal application you can download from the Microsoft Store, or
[directly from this repo's
releases](https://github.com/microsoft/terminal/releases).

---

## Resources

For more information about Windows Terminal, you may find some of these
resources useful and interesting:

* [Command-Line Blog](https://devblogs.microsoft.com/commandline)
* [Command-Line Backgrounder Blog
  Series](https://devblogs.microsoft.com/commandline/windows-command-line-backgrounder/)
* Windows Terminal Launch: [Terminal "Sizzle
  Video"](https://www.youtube.com/watch?v=8gw0rXPMMPE&list=PLEHMQNlPj-Jzh9DkNpqipDGCZZuOwrQwR&index=2&t=0s)
* Windows Terminal Launch: [Build 2019
  Session](https://www.youtube.com/watch?v=KMudkRcwjCw)
* Run As Radio: [Show 645 - Windows Terminal with Richard
  Turner](https://www.runasradio.com/Shows/Show/645)
* Azure Devops Podcast: [Episode 54 - Kayla Cinnamon and Rich Turner on DevOps
  on the Windows
  Terminal](http://azuredevopspodcast.clear-measure.com/kayla-cinnamon-and-rich-turner-on-devops-on-the-windows-terminal-team-episode-54)
* Microsoft Ignite 2019 Session: [The Modern Windows Command Line: Windows
  Terminal -
  BRK3321](https://myignite.techcommunity.microsoft.com/sessions/81329?source=sessions)

---

## FAQ

### I built and ran the new Terminal, but it looks just like the old console

Cause: You're launching the incorrect solution in Visual Studio.

Solution: Make sure you're building & deploying the `CascadiaPackage` project in
Visual Studio.

> [!NOTE]
> `OpenConsole.exe` is just a locally-built `conhost.exe`, the classic
> Windows Console that hosts Windows' command-line infrastructure. OpenConsole
> is used by Windows Terminal to connect to and communicate with command-line
> applications (via
> [ConPty](https://devblogs.microsoft.com/commandline/windows-command-line-introducing-the-windows-pseudo-console-conpty/)).

---

## Documentation

All project documentation is located at [aka.ms/terminal-docs](https://aka.ms/terminal-docs). If you would like
to contribute to the documentation, please submit a pull request on the [Windows
Terminal Documentation repo](https://github.com/MicrosoftDocs/terminal).

---

## Contributing

We are excited to work alongside you, our amazing community, to build and
enhance Windows Terminal\!

***BEFORE you start work on a feature/fix***, please read & follow our
[Contributor's
Guide](./CONTRIBUTING.md) to
help avoid any wasted or duplicate effort.

## Communicating with the Team

The easiest way to communicate with the team is via GitHub issues.

Please file new issues, feature requests and suggestions, but **DO search for
similar open/closed preexisting issues before creating a new issue.**

If you would like to ask a question that you feel doesn't warrant an issue
(yet), please reach out to us via Twitter:

* Christopher Nguyen, Product Manager:
  [@nguyen_dows](https://twitter.com/nguyen_dows)
* Dustin Howett, Engineering Lead: [@dhowett](https://twitter.com/DHowett)
* Mike Griese, Senior Developer: [@zadjii@mastodon.social](https://mastodon.social/@zadjii)
* Carlos Zamora, Developer: [@cazamor_msft](https://twitter.com/cazamor_msft)
* Pankaj Bhojwani, Developer
* Leonard Hecker, Developer: [@LeonardHecker](https://twitter.com/LeonardHecker)

## Developer Guidance

## Prerequisites

* You must be running Windows 10 2004 (build >= 10.0.19041.0) or later to run
  Windows Terminal
* You must [enable Developer Mode in the Windows Settings
  app](https://docs.microsoft.com/en-us/windows/uwp/get-started/enable-your-device-for-development)
  to locally install and run Windows Terminal
* You must have [PowerShell 7 or later](https://github.com/PowerShell/PowerShell/releases/latest) installed
* You must have the [Windows 11 (10.0.22621.0)
  SDK](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/)
  installed
* You must have at least [VS
  2022](https://visualstudio.microsoft.com/downloads/) installed
* You must install the following Workloads via the VS Installer. Note: Opening
  the solution in VS 2022 will [prompt you to install missing components
  automatically](https://devblogs.microsoft.com/setup/configure-visual-studio-across-your-organization-with-vsconfig/):
  * Desktop Development with C++
  * Universal Windows Platform Development
  * **The following Individual Components**
    * C++ (v143) Universal Windows Platform Tools
* You must install the [.NET Framework Targeting Pack](https://docs.microsoft.com/dotnet/framework/install/guide-for-developers#to-install-the-net-framework-developer-pack-or-targeting-pack) to build test projects

## Building the Code

This repository uses [git
submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) for some of its
dependencies. To make sure submodules are restored or updated, be sure to run
the following prior to building:

```shell
git submodule update --init --recursive
```

OpenConsole.sln may be built from within Visual Studio or from the command-line
using a set of convenience scripts & tools in the **/tools** directory:

### Building in PowerShell

```powershell
Import-Module .\tools\OpenConsole.psm1
Set-MsBuildDevEnvironment
Invoke-OpenConsoleBuild
```

### Building in Cmd

```shell
.\tools\razzle.cmd
bcz
```

## Running & Debugging

To debug the Windows Terminal in VS, right click on `CascadiaPackage` (in the
Solution Explorer) and go to properties. In the Debug menu, change "Application
process" and "Background task process" to "Native Only".

You should then be able to build & debug the Terminal project by hitting
<kbd>F5</kbd>. Make sure to select either the "x64" or the "x86" platform - the
Terminal doesn't build for "Any Cpu" (because the Terminal is a C++ application,
not a C# one).

> 👉 You will _not_ be able to launch the Terminal directly by running the
> WindowsTerminal.exe. For more details on why, see
> [#926](https://github.com/microsoft/terminal/issues/926),
> [#4043](https://github.com/microsoft/terminal/issues/4043)

### Coding Guidance

Please review these brief docs below about our coding practices.

> 👉 If you find something missing from these docs, feel free to contribute to
> any of our documentation files anywhere in the repository (or write some new
> ones!)

This is a work in progress as we learn what we'll need to provide people in
order to be effective contributors to our project.

* [Coding Style](./doc/STYLE.md)
* [Code Organization](./doc/ORGANIZATION.md)
* [Exceptions in our legacy codebase](./doc/EXCEPTIONS.md)
* [Helpful smart pointers and macros for interfacing with Windows in WIL](./doc/WIL.md)

---

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of
Conduct][conduct-code]. For more information see the [Code of Conduct
FAQ][conduct-FAQ] or contact [opencode@microsoft.com][conduct-email] with any
additional questions or comments.

[conduct-code]: https://opensource.microsoft.com/codeofconduct/
[conduct-FAQ]: https://opensource.microsoft.com/codeofconduct/faq/
[conduct-email]: mailto:opencode@microsoft.com
[store-install-link]: https://aka.ms/terminal

7. **Winget-Cli**

   # ![WinGet Icon](.github/images/WindowsPackageManager_Assets/ICO/PNG/_40.png) Windows Package Manager

## WinGet Client

![winget install wingetcreate](.github/images/WingetInstall.gif)

If you are new to the Windows Package Manager, you might want to [Explore the Windows Package Manager tool](https://docs.microsoft.com/learn/modules/explore-windows-package-manager-tool/?WT.mc_id=AZ-MVP-5004737). The client has access to packages from two default sources. The first is "msstore" the Microsoft Store (free Apps rated "e" for everyone). The second is "winget" the [WinGet community repository](https://github.com/microsoft/winget-pkgs).

> **Note**: Group policy may be configured and modify configured sources. Run `winget --info` to see any configured policies.

## Installing The Client

> **Note**: The client requires Windows 10 1809 (build 17763) or later at this time. Windows Server 2019 is not supported as the Microsoft Store is not available nor are updated dependencies. It may be possible to install on Windows Server 2022, this should be considered experimental (not supported), and requires dependencies to be manually installed as well.

### Microsoft Store [Recommended]

The client is distributed within the [App Installer](https://www.microsoft.com/p/app-installer/9nblggh4nns1) package.

### Development Releases

There are two methods to get development releases:

* Install a [Windows 10 or Windows 11 Insider](https://insider.windows.com/) build.
* Join the Windows Package Manager Insider program by [signing up](http://aka.ms/winget-InsiderProgram).

> **Note**: It may take a few days to get the updated App Installer after you receive e-mail confirmation from joining the Windows Package Manager Insider program. If you decide to install the latest release from GitHub, and you have successfully joined the insider program, you will receive updates when the next development release has been published in the Microsoft Store.

Once you have received the updated App Installer from the Microsoft Store you should be able to execute `winget features` to see experimental features. Some users have reported [issues](https://github.com/microsoft/winget-cli/issues/210) with the client not being on their PATH.

### Manually Update

The same Microsoft Store package will be made available via our [Releases](https://github.com/microsoft/winget-cli/releases). Note that installing this package will give you the WinGet client, but it will not enable automatic updates from the Microsoft Store if you have not joined the Windows Package Manager Insider program.

> **Note**: You may need to install the [VC++ v14 Desktop Framework Package](https://docs.microsoft.com/troubleshoot/cpp/c-runtime-packages-desktop-bridge#how-to-install-and-update-desktop-framework-packages).
> This should only be necessary on older builds of Windows 10 and only if you get an error about missing framework packages.

### Troubleshooting

Please read our [troubleshooting guide](/doc/troubleshooting/README.md).

## Administrator Considerations

Installer behavior can be different depending on whether you are running **winget** with administrator privileges.

* When running **winget** without administrator privileges, some applications may [require elevation](https://docs.microsoft.com/windows/security/identity-protection/user-account-control/how-user-account-control-works) to install. When the installer runs, Windows will prompt you to [elevate](https://docs.microsoft.com/windows/security/identity-protection/user-account-control/how-user-account-control-works#the-uac-user-experience). If you choose not to elevate, the application will fail to install.

* When running **winget** in an Administrator Command Prompt, you will not see [elevation prompts](https://docs.microsoft.com/windows/security/identity-protection/user-account-control/how-user-account-control-works#the-uac-user-experience) if the application requires it. Always use caution when running your command prompt as an administrator, and only install applications you trust.

### Build your own

You can also [build the client yourself](#building-the-client). While the client should be perfectly functional, we are not ready to provide full support for clients running outside of the official distribution mechanisms yet. Feel free to file an [Issue](https://github.com/microsoft/winget-cli/issues/new/choose), but know that it may get lower prioritization.

## Build Status

[![Build Status](https://dev.azure.com/ms/winget-cli/_apis/build/status/microsoft.winget-cli?branchName=master)](https://dev.azure.com/ms/winget-cli/_build/latest?definitionId=344&branchName=master)

## Windows Package Manager Release Roadmap

The plan for delivering next Windows Package Manager releases is described included in our [discussions](https://github.com/microsoft/winget-cli/discussions/2063), and will be updated as the project proceeds.

## Overview of the  Windows Package Manager

The **Windows Package Manager** is a tool designed to help you quickly and easily discover and install those packages that make your PC environment special.  By using the **Windows Package Manager**, from one command, you can install your favorite packages:

`winget install <package>`

## Overview

### Client Repository

This winget-cli repository includes the source code designed to build the client.  You are encouraged to participate in the development of this client. We have plenty of backlog features in our [Issues](https://github.com/microsoft/winget-cli/issues?q=is%3Aopen+is%3Aissue+milestone%3ABacklog-Client). You can upvote the ones you want, add more, or even [get started on one.](https://github.com/orgs/microsoft/projects/137)

### Sources

The client is built around the concept of sources; a set of packages effectively. Sources provide the ability to discover and retrieve the metadata about the packages, so that the client can act on it.

* The default "winget" source includes packages in the [Windows Package Manager Community Repository](https://github.com/microsoft/winget-pkgs).
* The default "msstore" source includes packages in the Microsoft Store.
* It is also possible to host your own private [REST based](https://github.com/microsoft/winget-cli-restsource) source.

## Building the client

1. Clone the repository
2. Configure your system, please use the [configuration file](.configurations/configuration.dsc.yaml). This can be applied by either:
   * [Dev Home](https://github.com/microsoft/devhome)'s machine configuration tool
   * WinGet configuration. If you have the experimental feature enabled, run `winget configure .configurations/configuration.dsc.yaml` from the project root so relative paths resolve correctly

### Prerequisites

* Windows 10 1809 (17763) or later
* [Developer Mode enabled](https://docs.microsoft.com/windows/uwp/get-started/enable-your-device-for-development)
* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
  * Or use winget to install it ;) (although you may need to adjust the workloads via Tools->Get Tools and Features...)
* The following workloads:
  * .NET Desktop Development
  * Desktop Development with C++
  * Universal Windows Platform Development
* [Windows 10 SDK, version 2004 (10.0.19041.0)](https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/)
  > **Note**: You can also get it through `winget install Microsoft.WindowsSDK --version 10.0.19041.685` (use --force if you have a newer version installed) or via Visual Studio > Get Tools and Features > Individual Components > Windows 10 SDK (10.0.19041.0)
* The following extensions:
  * [Microsoft Visual Studio Installer Projects](https://marketplace.visualstudio.com/items?itemName=VisualStudioClient.MicrosoftVisualStudio2022InstallerProjects)

### Building

Open `winget-cli\src\AppInstallerCLI.sln` in Visual Studio and build. We currently only build using the solution; command line methods of building a VS solution should work as well. After the build finishes, deploy the solution from Build > Deploy Solution. You can then run the client from the command line using `wingetdev`.

## Credit

We would like to thank [Keivan Beigi (@kayone)](https://github.com/kayone) for his work on AppGet which helped us on the initial project direction for Windows Package Manager.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com. More
information is available in our [CONTRIBUTING.md](/CONTRIBUTING.md) file.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information, please refer to the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Data/Telemetry

The winget.exe client is instrumented to collect usage and diagnostic (error) data and sends it to Microsoft to help improve the product.

If you build the client yourself the instrumentation will not be enabled and no data will be sent to Microsoft.

The winget.exe client respects machine wide privacy settings and users can opt-out on their device, as documented in the Microsoft Windows privacy statement [here](https://support.microsoft.com/help/4468236/diagnostics-feedback-and-privacy-in-windows-10-microsoft-privacy). In addition, you may also explicitly block telemetry using [settings](https://docs.microsoft.com/windows/package-manager/winget/settings)

In short to opt-out, do one of the following:

**Windows 11**: Go to `Start`, then select `Settings` > `Privacy & security` > `Diagnostics & feedback` > `Diagnostic data` and unselect `Send optional diagnostic data`.

**Windows 10**: Go to `Start`, then select `Settings` > `Privacy` > `Diagnostics & feedback`, and select `Required diagnostic data`.

See the [privacy statement](PRIVACY.md) for more details.

7.**Winget-Pkgs**

# Windows Package Manager Community Repository

[![Gitter](https://img.shields.io/gitter/room/Microsoft/winget-pkgs)](https://gitter.im/Microsoft/winget-pkgs)
[![Validation Pipeline Badge](https://img.shields.io/endpoint?url=https://winget-pme.azurefd.net/api/GetServiceComponentStatusBadge?component=ValidationPipeline 'Validation Pipeline Badge')](https://dev.azure.com/ms/winget-pkgs/_build?definitionId=337)
[![Publish Pipeline Badge](https://img.shields.io/endpoint?url=https://winget-pme.azurefd.net/api/GetServiceComponentStatusBadge?component=PublishPipeline 'Publish Pipeline Badge')](https://dev.azure.com/ms/winget-pkgs/_build?definitionId=338)
[![GitHub Status](https://img.shields.io/endpoint?url=https://api.bittu.eu.org/github-status-badge-endpoint)](https://www.githubstatus.com)

This repository contains the manifest files for the **Windows Package Manager** default source. You are highly encouraged to submit manifests for your favorite application.

> [!IMPORTANT]
> At this time installers must be MSIX, MSI, APPX, or .exe application installers. Script-based installers and fonts are not currently supported.

The **Windows Package Manager** is an [open source client](https://github.com/microsoft/winget-cli) designed for command-line usage. If you are interested in exploring private repositories offering private WinGet package hosting, see [private repositories](doc/private/README.md).

# Documentation

Please check the [overview](doc/README.md) for detailed topics. Common topics for the WinGet Community repository are available below:
* [Authoring a manifest](doc/README.md#authoring-a-manifest)
* [Testing a manifest](doc/README.md#testing-a-manifest)
* [Submitting a manifest](doc/README.md#submitting-a-manifest)
* [Requesting a new package](doc/Issues.md#Request-a-New-Package)
* [Requesting a new package version](doc/Issues.md#Request-a-New-Package-Version)

## Repology
[Repology](https://repology.org/), the packaging hub monitors package repositories comparing package versions and other information.

[![Repository status](https://repology.org/badge/repository-big/winget.svg)](https://repology.org/repository/winget)

# Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Follow the instructions provided by the bot. You will only need to do this once across all Microsoft repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
See the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments. More information is available in our [Contributing document](CONTRIBUTING.md).

To avoid doubt, you may not make any Submissions linking to third party materials if such Submission is prohibited by the applicable third party and/or otherwise violates such third party's rights.

8. **Skanda890**
    - The repository you are reading this from.

9. **Potify-Music-Player**

 # A Mini Music Player - HTML, CSS and Javascript.

<img width="1448" alt="Screenshot 2023-08-14 at 5 34 24 PM" src="https://github.com/developerrahulofficial/Potify-mini-Music-Player/assets/83329806/315cf8f8-9998-43c2-b5f8-36e530536f7c">

In this example, we'll create a simple music player interface using HTML, CSS, and Vue.js for the interactions. Here's how you can do it:

**Step 1: Setting Up the HTML Structure**
Create an HTML file named `index.html` and set up the basic structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Music Player</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper" id="app">
    <!-- Your content will go here -->
  </div>
</body>
</html>
```

**Step 2: Creating the CSS Styles**
Create a file named `style.css` to define the styles for your music player:

```css
/* Define your CSS styles here */
```

**Step 3: Adding the JavaScript Code**
In the `index.html` file, add the Vue.js library and your custom JavaScript code at the end of the `<body>` section:

```html
<!-- Load Vue.js library -->
<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.min.js"></script>

<!-- Your JavaScript code -->
<script src="script.js"></script>
```

**Step 4: Implementing the Vue.js App**
Create a file named `script.js` and add the following JavaScript code:

```javascript
new Vue({
  el: '#app',
  data: {
    // Your data properties here
  },
  methods: {
    // Your methods here
  },
  computed: {
    // Your computed properties here
  }
});
```

**Step 5: Adding the Music Player UI**
Replace the content of the `<div class="wrapper" id="app">` with the provided HTML code.

```html
<div class="wrapper" id="app">
  <!-- Provided HTML code here -->
</div>
```

**Step 6: Styling the Music Player**
In the `style.css` file, add styles to make your music player visually appealing. You can use the provided CSS code as a starting point and customize it according to your preferences.

**Step 7: Implementing Vue.js Logic**
In the `script.js` file, fill in the Vue.js data, methods, and computed properties according to the interactions and logic you want to implement. You can use Vue.js directives like `v-if`, `v-for`, and event listeners like `@click` to bind your app's behavior to the UI elements.

**Step 8: Testing Your Music Player**
Open the `index.html` file in a web browser to see your music player interface in action. Make sure to test all the interactions and functionalities you've implemented.

That's it! You've successfully created a music player interface using HTML, CSS, and Vue.js. Remember to customize and enhance the code as needed to fit your design and requirements.        

9. **Dictionary-App**

# Dictionary Web App - Frontend Mentor Challenge
![Screenshot](./screenshot.webp)

It appears that the project you're trying to run uses Vite as its build tool and development server. Here are the steps to run the `fem-dictionary-web-app` project on your localhost:

1. **Clone the Repository:**
   If you haven't already, clone the repository as mentioned earlier:

   ```sh
   git clone https://github.com/developerrahulofficial/dictionary-app.git
   ```

2. **Navigate to the Project Directory:**
   Move into the project directory:

   ```sh
   cd dictionary-app
   ```

3. **Install Dependencies:**
   Install the project's dependencies using npm:

   ```sh
   npm install
   ```

4. **Run the Development Server:**
   To start the development server, use the following command:

   ```sh
   npm start
   ```

   This command will run Vite's development server, and the application will be accessible at a local URL, usually `http://localhost:8080` or a similar port.

   Alternatively, you can use the specific `preview` script:

   ```sh
   npm run 
   ```

   This will also start the development server.

5. **Access the Application:**
   Open your web browser and navigate to the local URL where the development server is running (e.g., `http://localhost:8080`). You should be able to see and interact with the web application.

Keep in mind that the available scripts and their functionality are defined in the project's `package.json` file. The above instructions assume that you have Node.js and npm installed on your system.

If you encounter any issues during this process, please refer to the project's documentation or README for troubleshooting steps specific to the `fem-dictionary-web-app`.

10. **Hackbook**

# Hackbook
An Application for Tamilnadu police cyber cell Department according to their problem Statement
# Getting Started with Create React App and Redux

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app), using the [Redux](https://redux.js.org/) and [Redux Toolkit](https://redux-toolkit.js.org/) template.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

11. **Windows Dev Docs**

 <h1>Windows Development Documentation</h1>
        <p>Learn how to design, develop, and deploy apps and solutions for Windows PCs and other devices.</p>
        <p>Explore the <a href="https://learn.microsoft.com/en-us/windows/apps/">full documentation</a> for detailed information.</p>

Feel free to explore my work on GitHub! 🚀
