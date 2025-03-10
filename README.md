> [!CAUTION]
> This fork of Bloxstrap was made after the allegations of the [current] owner, Matt (bluepillgreat) came out.

<p align="center">
    <img src="https://github.com/MadeByRedPCat/Rostruct/raw/main/Images/Bloxstrap-full-dark.png#gh-dark-mode-only" width="420">
    <img src="https://github.com/MadeByRedPCat/Rostruct/raw/main/Images/Bloxstrap-full-light.png#gh-light-mode-only" width="420">
</p>

<div align="center">

[![License][shield-repo-license]][repo-license]
[![GitHub Workflow Status][shield-repo-workflow]][repo-actions]
<!-- [![Crowdin][shield-crowdin-status]][crowdin-project] -->
[![Downloads][shield-repo-releases]][repo-releases]
[![Version][shield-repo-latest]][repo-latest]
<!-- [![Discord][shield-discord-server]][discord-invite] -->

</div>

----

Rostruct is a third-party replacement for the standard Roblox bootstrapper & Bloxstrap, providing additional useful features and improvements.

<!-- Running into a problem or need help with something? [Check out the Wiki](https://github.com/MadeByRedPCat/Rostruct/wiki). If you can't find anything, or would like to suggest something, please [submit an issue](https://github.com/MadeByRedPCat/Rostruct/issues). -->

Rostruct is only available for Windows currently.

## Frequently Asked Questions

**Q: Is this malware?**

**A:** No. The source code here is viewable to all, and it'd be impossible for us to slip anything malicious into the downloads without anyone noticing. Just be sure you're downloading it from an official source. The only official source is this GitHub repository.

**Q: Can using this get me banned?**

**A:** No, it shouldn't. Rostruct doesn't interact with the Roblox client in the same way that exploits do. <!-- [Read more about that here.](https://github.com/MadeByRedPCat/Rostruct/wiki/Why-it's-not-reasonably-possible-for-you-to-be-banned-by-Rostruct) -->

## Features

- Hassle-free Discord Rich Presence to let your friends know what you're playing at a glance
- Simple support for modding of content files for customizability (death sound, mouse cursor, etc)
- See where your server is geographically located (courtesy of [ipinfo.io](https://ipinfo.io))
- Ability to configure graphics fidelity and UI experience

## Installing
Download the [latest release of Rostruct](https://github.com/MadeByRedPCat/Rostruct/releases/latest), and run it. Configure your preferences if needed, and install. That's about it!

You will also need the [.NET 6 Desktop Runtime](https://aka.ms/dotnet-core-applaunch?missing_runtime=true&arch=x64&rid=win11-x64&apphost_version=6.0.16&gui=true). If you don't already have it installed, you'll be prompted to install it anyway. Be sure to install Rostruct after you've installed this.

It's not unlikely that Windows Smartscreen will show a popup when you run Rostruct for the first time. This happens because it's an unknown program, not because it's actually detected as being malicious. To dismiss it, just click on "More info" and then "Run anyway".

Once installed, Rostruct is added to your Start Menu, where you can access the menu and reconfigure your preferences if needed.

## Code

Rostruct uses the [WPF UI](https://github.com/lepoco/wpfui) library for the user interface design. We currently use the Bloxstrap version of WPF UI at [bloxstraplabs/wpfui](https://github.com/bloxstraplabs/wpfui).


[shield-repo-license]:  https://img.shields.io/github/license/MadeByRedPCat/Rostruct
[shield-repo-workflow]: https://img.shields.io/github/actions/workflow/status/MadeByRedPCat/Rostruct/ci-release.yml?branch=main&label=builds
[shield-repo-releases]: https://img.shields.io/github/downloads/MadeByRedPCat/Rostruct/latest/total?color=981bfe
[shield-repo-latest]:   https://img.shields.io/github/v/release/MadeByRedPCat/Rostruct?color=7a39fb

[shield-crowdin-status]: https://badges.crowdin.net//localized.svg
[shield-discord-server]: https://img.shields.io/discord/1099468797410283540?logo=discord&logoColor=white&label=discord&color=4d3dff

[repo-license]:  https://github.com/MadeByRedPCat/Rostruct/blob/main/LICENSE
[repo-actions]:  https://github.com/MadeByRedPCat/Rostruct/actions
[repo-releases]: https://github.com/MadeByRedPCat/Rostruct/releases
[repo-latest]:   https://github.com/MadeByRedPCat/Rostruct/releases/latest

[crowdin-project]: https://crowdin.com/project/bloxstrap
[discord-invite]:  https://discord.gg/nKjV3mGq6R
