# Running the game on Linux with WINE

## What is WINE

**Official website: <https://www.winehq.org/>**

**WINE** is the abbreviation of "**W**ine **i**s **N**ot an **E**mulator". It is a _compatibility layer_ that allows you to run Windows applications on various POSIX-compliant platforms such as Linux, macOS, BSD, etc.

## Download and install WINE

Go to <https://wiki.winehq.org/Download> to pick the WINE version that matches your OS.

## Fullscreen gameplay & 3D acceleration

The game may run into issues with fullscreen gameplay and 3D acceleration.

You may need to install the following **32-bit** packages:

- `libgl1:i386`
- `libvulkan1:i386`