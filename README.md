# scrcpy (v2.0)

_pronounced "**scr**een **c**o**py**"_

This application mirrors Android devices (video and audio) connected via
USB or [over TCP/IP](doc/device.md#tcpip-wireless), and allows to control the
device with the keyboard and the mouse of the computer. It does not require any
_root_ access. It works on _Linux_, _Windows_ and _macOS_.

Its features include:
 - [audio forwarding](doc/audio.md) (Android >= 11)
 - [recording](doc/recording.md)
 - mirroring with [Android device screen off](doc/device.md#turn-screen-off)
 - [copy-paste](doc/control.md#copy-paste) in both directions
 - [configurable quality](doc/video.md)
 - Android device [as a webcam (V4L2)](doc/v4l2.md) (Linux-only)
 - [physical keyboard/mouse simulation (HID)](doc/hid-otg.md)
 - [OTG mode](doc/hid-otg.md#otg)
 - and more…

## Prerequisites

The Android device should be on Andriod 5.0 or later.

Andriod 11 or later is required for audio forwaarding.

Make sure you enabled USB debugging on your Andriod device. This can be done by going to Settings> About Phone, Scroll down to "build number", and tap it 7 times. If done correctly, the message "You are now a develpoer!" will appear.

On some devices, you also need to enable an additional option, `USB
debugging (Security Settings)` (this is an item different from `USB debugging`)
to control your device using a keyboard and mouse.


## Get the app

 - [Linux](doc/linux.md)
 - [Windows](doc/windows.md)
 - [macOS](doc/macos.md)


## User documentation

The application provides a lot of features and configuration options. They are
documented in the following pages:

 - [Device](doc/device.md)
 - [Video](doc/video.md)
 - [Audio](doc/audio.md)
 - [Control](doc/control.md)
 - [Window](doc/window.md)
 - [Recording](doc/recording.md)
 - [Tunnels](doc/tunnels.md)
 - [HID/OTG](doc/hid-otg.md)
 - [Video4Linux](doc/v4l2.md)
 - [Shortcuts](doc/shortcuts.md)


## Resources

 - [FAQ](FAQ.md)
 - [Translations][wiki] (not necessarily up to date)
 - [Build instructions](doc/build.md)
 - [Developers](doc/develop.md)

[wiki]: https://github.com/Genymobile/scrcpy/wiki

## Contact

If you encounter a bug, please read the [FAQ](FAQ.md) first, then open an [issue].

[issue]: https://github.com/Genymobile/scrcpy/issues

For general questions or discussions, you can also use:

 - Reddit: [`r/scrcpy`](https://www.reddit.com/r/scrcpy)
 - Twitter: [`@scrcpy_app`](https://twitter.com/scrcpy_app)


## Donate

I'm [@rom1v](https://github.com/rom1v), the author and maintainer of _scrcpy_.

If you appreciate this application, you can [support my open source
work][donate].

[donate]: https://blog.rom1v.com/about/#support-my-open-source-work

## Licence

    Copyright (C) 2018 Genymobile
    Copyright (C) 2018-2023 Romain Vimont

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
