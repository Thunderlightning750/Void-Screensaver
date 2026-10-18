# VOID — A Windows Screensaver

A little personal project that turned into a much bigger adventure than I expected.

VOID is a Windows screensaver I'm building in C++ using Direct2D and DirectWrite. It has a clock, system information, support for multiple monitors, customizable appearance, and optional background-image effects.

It's something I made because I wanted to create my own screensaver instead of just using whatever Windows already had.

## Why I made this

Honestly, I didn't start this project expecting to make some big piece of software. I wanted to make something that looked cool, worked the way I wanted, and that I could call my own.

Then one feature turned into another, and suddenly I was dealing with Windows graphics, image processing, configuration files, multi-monitor behavior, and installers. Some parts were fun. Other parts were me staring at a command window wondering why the installer had immediately died. 😭

But that's part of making something yourself, I guess.

## A little transparency

I used AI assistance throughout development, including help with writing and debugging code. I'm not going to pretend I wrote every line entirely on my own.

I still made the project decisions, worked through the problems on my computer, tested things, and figured out what I wanted VOID to become. Using AI was part of how I approached the project, not something I want to hide from people looking at it.

I'm still learning, and this project reflects that. There may be bugs, rough edges, or things that need to be improved. I'd rather be honest about that than pretend VOID is a finished product.

## What can it do?

- Display a clock, date, and system information.
- Render using Windows graphics APIs.
- Support multiple monitors.
- Use a custom background image.
- Apply optional feathered edges to the image.
- Customize supported appearance settings through an INI file.

Features and compatibility may change as development continues. Check the current source and release notes for the state of each feature.

## Getting started

The releases currently provide **source code**, not a ready-to-run screensaver.

If you want to try VOID, start with the installation and build instructions linked in the latest release. You'll need the appropriate Visual Studio C++ build tools to compile it.

I want to make the process as straightforward as possible, even for people who haven't built a C++ project before.

## Images and customization

Using your own background image is the idea. You don't need to include a character image if you'd rather have a simple screensaver, provided the version you're building supports running without one.

Please make sure you have permission to use any artwork you include. Not every image you find online is free to redistribute.

## Known limitations

VOID is still a work in progress. It hasn't been tested on every Windows system, graphics card, or display type.

OLED users should be especially cautious. Static screen elements can contribute to burn-in over time, and VOID does not currently guarantee protection against it. See the release notes for any additional display-related limitations.

## What's next?

I want to keep improving the project, making configuration easier, fixing bugs, and adding features where they make sense.

If you try VOID and run into a problem, feel free to report it. Constructive feedback is welcome, and bug reports help me figure out what needs attention.

Thanks for checking out my little project. Whether you're here to use it, look at the code, learn something, or just see what I've been working on, I appreciate it.

— The creator of VOID
