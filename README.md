# VOID — A Windows Screensaver

A personal Windows screensaver project made with C++ and Direct2D.

VOID started as an idea for a screensaver I wanted to make myself. Somewhere along the way, it turned into a much bigger project involving Windows graphics, image processing, multi-monitor support, configuration files, and the wonderful experience of debugging Windows batch scripts. 😭

It isn't a big commercial product. It's something I wanted to build, experiment with, and share.

## What is VOID?

VOID is a Windows screensaver featuring a clock, date, system information, and customizable visual elements.

Depending on the version, features include:

- Hardware-accelerated rendering through Direct2D where supported.
- Text rendered using DirectWrite.
- Clock, date, and system information.
- Multi-monitor support.
- Optional custom background images.
- Optional feathered image edges.
- Configurable appearance through an INI file.
- Animated particles, where supported by the build.

## Getting started

You don't need to compile the project to use a release that already includes `Void.scr`.

1. Download the latest release ZIP.
2. Extract it to a folder.
3. Run `Install.bat` and approve the Windows administrator prompt.
4. Follow the installation instructions included with the release.

The installer places the screensaver in the Windows system directory and creates a separate folder in your Documents directory for VOID's settings and background image.

**[Read the installation and uninstallation guide](INSTALLATION.md)** for the full explanation of what happens and how to remove it.

## Customization

VOID supports a configuration file named `Void.ini`. Depending on the version, you can use it to adjust options such as the background image, image-edge processing, and particle appearance.

The installed settings and image are stored in a dedicated `Documents\VOID` folder, rather than mixed in with your other documents.

You can edit the configuration file using Notepad. You shouldn't need to reinstall VOID every time you change a supported setting or replace the background image.

## A little about how this came together

This project was a learning experience for me. I made decisions about how I wanted VOID to look and behave, tested it on my own PC, and worked through problems as they appeared.

I also used AI assistance during development, including help with C++ code, debugging, configuration, and installer scripts. It helped me get further with the project, but it didn't remove the need to figure out what I wanted, test changes, and deal with things that didn't work as expected.

Some parts took much longer than I expected. The installer alone was enough to remind me that getting software to run correctly on someone else's Windows installation is a different challenge from getting it to work on your own computer. 💀

I'm sharing VOID because I wanted to make something of my own and let other people try it, look at the code, or learn from it.

## Limitations

VOID is a personal project, and it may have bugs or compatibility issues. It hasn't been tested on every Windows configuration, GPU, or monitor setup.

OLED displays deserve particular caution. Static screen elements can contribute to burn-in over time. VOID should not be considered burn-in protection, and users should take that risk into account before leaving it running on an OLED display for long periods.

## About future updates

I may return to VOID to fix bugs or improve things when I have the time and feel like working on it. I don't have a release schedule or a promise of ongoing updates.

If something doesn't work, you're welcome to report it. I can't guarantee how quickly I'll respond, but useful reports help identify problems.

Thanks for checking out VOID!
