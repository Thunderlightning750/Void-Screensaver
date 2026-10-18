# VOID Screensaver

A personal Windows screensaver project built with C++ and Direct2D.

VOID started as an experiment in making a minimalist, customizable screensaver for Windows. What began as a personal project grew into a learning experience involving Windows graphics, image processing, multi-monitor behavior, configuration files, and installation scripts.

This project is a work in progress.

## Features

- Native Windows screensaver (`.scr`)
- Direct2D rendering and DirectWrite text
- Clock, date, and system information
- Multi-monitor support
- Optional custom background image
- Optional image-edge feathering
- Configurable appearance through an INI file

**Note:** Features may vary by release. Check the current release notes for what has been tested and is working.

## Getting started

### Using a release

1. Download the latest tested release from the [Releases](../../releases) page.
2. Extract the ZIP file.
3. Follow the included installation instructions.
4. Customize `Void.ini` to adjust the available settings.

You should not need Visual Studio to install a precompiled release.

### Building from source

1. Install Visual Studio with the **Desktop development with C++** workload.
2. Open `VoidScreensaver.vcxproj`.
3. Select `Release` and `x64`.
4. Build the project.
5. Follow the repository's installation instructions.

## Background images

A custom background image is optional if the installed version supports running without one. You can use your own artwork and configure its path in `Void.ini`.

Please make sure you have the rights to use any images you add.

## Transparency and limitations

VOID is a personal project, and it is not a polished commercial product. Bugs, compatibility problems, and incomplete features are possible.

OLED displays are not currently recommended because static screen elements can contribute to image retention and burn-in. VOID does not guarantee burn-in protection. A timed display-off option may be considered in a future release.

The project has not been tested on every Windows configuration or display type.

## Development story

I built VOID as a personal project and learned along the way. I used AI assistance during development and debugging, including help with code, configuration, and installer scripts.

I'm sharing the project openly so others can inspect it, learn from it, report problems, and suggest improvements.

I don't want to misrepresent the project as more mature than it is. If something is broken or unfinished, I'd rather document that honestly and improve it over time.

## Contributing

Bug reports, suggestions, and constructive feedback are welcome. Please include your Windows version, steps to reproduce the issue, and any relevant error messages.

## License

See [LICENSE](LICENSE) for the terms under which this project may be used and redistributed.
