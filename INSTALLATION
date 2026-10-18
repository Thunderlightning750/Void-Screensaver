# VOID — Installation and Uninstallation Guide

This guide explains how to install VOID, where its files go, what the installer changes, and how to remove it later.

You do **not** need Visual Studio or a C++ compiler to use a release that already includes `Void.scr`.

## What you'll need

- A Windows PC.
- The VOID release ZIP.
- Permission to install a screensaver in the Windows system directory.

## 1. Download and extract VOID

1. Open the VOID GitHub repository.
2. Go to **Releases** and download the release ZIP.
3. Extract the ZIP to a folder you can find easily.
4. Check that `Install.bat` and the compiled `Void.scr` are present.

Keep the files together in the extracted folder until installation is complete.

## 2. Install VOID

1. Double-click `Install.bat`, or right-click it and choose **Run as administrator**.
2. Windows will ask for administrator permission. Review the prompt and approve it if you trust the copy of VOID you downloaded.
3. Wait for the installer to finish.
4. Read the final messages in the command window.

Administrator permission is needed because the installer places the screensaver in a protected Windows system directory.

## 3. Where does VOID install?

The installer uses two main locations.

### Screensaver program

`C:\Windows\System32\Void.scr`

This is the compiled screensaver Windows runs. The installer copies the program here so it can be selected through Windows' screensaver settings.

### Your VOID settings and image

The installer finds your Windows Documents folder and creates a folder named `VOID` inside it.

Typically, the folder is:

`%USERPROFILE%\Documents\VOID`

If your Documents folder is redirected or managed by OneDrive, the actual location may differ.

The folder contains files such as:

- `Void.ini` — configuration settings.
- `background.png` — your background image, if one was provided.

The installer copies the default INI and image only when those files don't already exist. This prevents a normal reinstall from overwriting your existing VOID settings or image.

If no image is included, the installer can still create the folder and install the program. Whether the screensaver can run without an image depends on the version being used.

## 4. What does the installer change?

The installer performs these actions:

1. Requests administrator permission.
2. Copies `Void.scr` to the Windows system directory.
3. Creates the dedicated `Documents\VOID` folder if needed.
4. Copies the default configuration and background image when they are available and the destination files don't already exist.
5. Registers/selects VOID through Windows' screensaver installation mechanism.

The last step can change which screensaver Windows has selected. You can change that selection in Windows Settings afterward.

The installer is not intended to edit your other personal documents, photos, projects, or unrelated files. Its file operations are limited to the VOID program location and its dedicated settings/image folder. As with any script, inspect the code if you want to verify its behavior before running it.

## 5. Select or preview the screensaver

After installation:

1. Open Windows Settings.
2. Go to **Personalization → Lock screen**.
3. Open **Screen saver** settings. On some Windows versions, you can also search for “Change screen saver” from Start.
4. Select VOID if it isn't already selected.
5. Choose the wait time and other Windows screensaver options you want.
6. Use **Preview** to test it.

The available configuration options depend on the version installed. Edit `Void.ini` in the `Documents\VOID` folder to change supported settings.

After changing the image or configuration, restart the screensaver to see the changes.

## 6. How to uninstall VOID

You can remove VOID without reinstalling Windows or resetting your personal files.

### Step A — Stop Windows from using VOID

1. Open **Settings → Personalization → Lock screen → Screen saver**.
2. Change the screensaver selection to **None** or another screensaver.
3. Apply the change.

This prevents Windows from trying to launch VOID after you remove its program file.

### Step B — Remove the installed program

1. Open File Explorer.
2. Navigate to `C:\Windows\System32`.
3. Find `Void.scr`.
4. Delete it. Windows may request administrator permission.

Only remove that file if it belongs to your VOID installation.

If you installed other VOID-specific files separately, remove only those files that you know belong to VOID.

### Step C — Remove your settings and image (optional)

If you want to remove your personal VOID configuration as well, open:

`%USERPROFILE%\Documents\VOID`

If your Documents folder is redirected, open the actual Documents location instead.

Delete the `VOID` folder if you no longer need its settings, background image, or generated image files.

**This step is optional.** Keeping the folder preserves your image and settings if you decide to install VOID again later.

### Step D — Remove the extracted source folder (optional)

Finally, you can delete the folder where you extracted the release ZIP. It isn't needed to run the installed screensaver.

## Troubleshooting

### The installer closes or fails

Check that `Void.scr` exists beside `Install.bat`. If it doesn't, you may have downloaded a source-only package or extracted the files incorrectly.

If the installer fails, don't assume it completed successfully. Record the error shown in the command window and check whether the program and Documents files were actually created.

### VOID isn't listed in the screensaver menu

Open Windows' Screen Saver Settings again and check whether VOID is available. Verify that `C:\Windows\System32\Void.scr` exists.

### My settings or image didn't change

Confirm that you edited the INI and image in the installed `Documents\VOID` folder, rather than the copies inside your extracted download. Restart the screensaver after making changes.

### Still having trouble?

Report the problem through the repository's GitHub Issues page, including your Windows version and the exact error message. Avoid posting personal information in issue reports.

Thanks for trying VOID!
