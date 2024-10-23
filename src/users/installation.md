# Installation

To get the most out of Heliosphere, you can install the companion plugin. This
will allow you to receive automatic updates (or just check for them if you don't
want it to be automatic) and install mods directly into Penumbra with one click.

## Install XIVLauncher

1. [Click here][xivlauncher-setup] to download the latest XIVLauncher installer (or
go to their [latest release page][xivlauncher-release] and download
`Setup.exe`).

2. Launch `Setup.exe`.

3. Follow the instructions to install, then sign in and launch your game.

## Add the Sea of Stars repository

1. Log in to a character, then press `Esc` and click on "Dalamud Settings" (or use
the `/xlsettings` command).

![image of the system menu in ffxiv](images/installation/dalamud-settings.avif)

2. Click the "Experimental" tab at the top of the settings window.

![image of dalamud settings](images/installation/experimental.avif)

3. Under the third-party repositories section, paste the following URL in the
empty text box.

```
https://raw.githubusercontent.com/Ottermandias/SeaOfStars/main/repo.json
```

<details>
<summary>Individual repositories (not recommended)</summary>

If you prefer to use individual repositories instead of the combined Sea of Stars repository, you can find them below.

```
https://raw.githubusercontent.com/xivdev/Penumbra/master/repo.json
```
```
https://repo.heliosphere.app/
```
</details>

![image of third-party repository settings](images/installation/box.avif)

4. Click the plus (+) button.

5. Click "Save and Close".

## Install Penumbra

1. Press `Esc` and click "Dalamud Plugins" (or use the `/xlplugins` command).
2. Click "All plugins" and either scroll down to or search for Penumbra.
3. Click on Penumbra, then click install.

## Set up Penumbra

Use the `/penumbra` command and follow the tutorial. You must set a mod
directory or mods will not work. If you still would like more help after the
tutorial, you can read the unaffiliated [guide][reni-guide] for more
information.

## Install Heliosphere

1. Follow the same procedure as installing Penumbra, but install Heliosphere
instead.
2. Open the first-time setup and follow the prompts.

[xivlauncher-setup]: https://github.com/goatcorp/FFXIVQuickLauncher/releases/latest/download/Setup.exe
[xivlauncher-release]: https://github.com/goatcorp/FFXIVQuickLauncher/releases/latest
[reni-guide]: https://reniguide.info/