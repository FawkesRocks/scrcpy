# On Windows

## Install

Download the [latest release]:

 - [`scrcpy-win64-v2.0.zip`][direct-win64] (64-bit)  
   <sub>SHA-256: `ae4c8d37a496b43f8974ba8f07f708e22a9570ba0cddc3dc3a36edbccd4d2a20`</sub>
 - [`scrcpy-win32-v2.0.zip`][direct-win32] (32-bit)  
   <sub>SHA-256: `15d98c02cb0e0bbd84f8b5d54991e0f6925569b1286a86a40743944fcb1c2d8c`</sub>

[latest release]: https://github.com/Genymobile/scrcpy/releases/latest
[direct-win64]: https://github.com/Genymobile/scrcpy/releases/download/v2.0/scrcpy-win64-v2.0.zip
[direct-win32]: https://github.com/Genymobile/scrcpy/releases/download/v2.0/scrcpy-win32-v2.0.zip

and extract it.

## Run

_Make sure that your device is set up as outlined [HERE](/README.md#prerequisites)._

To start scrcpy directly without opening a terminal, double-click on one of
these files:
 - `scrcpy-console.bat`: start with a terminal open (it will close when scrcpy
   terminates, unless an error occurs). This is recommended for ease of use.
 - `scrcpy-noconsole.vbs`: start without a terminal (but you won't see any error
   message).

_DO NOT RUN `scrcpy.exe` directly: This is intended to be run from a terminal for those using the command line. for our purposes, this is not needed and so we will ignore the .exe. Use `scrcpy-console.bat`instead._

Upon first launch, you will see "unauthroized device" or a similar error in the terminal. There will be a popup on the andriod device requesting USB debugging access. Check the checkbox to Always Allow, and click "Allow".

Scrcpy will now launch. audio, such as TalkBack, will be piped into the selected PC audio output. 
