# GHLtar Utility

Use a Guitar Hero Live PS3/Wii U dongle, or iOS Bluetooth Guitar, on your Windows PC by emulating an Xbox 360 controller.

Compiled releases are available [from the releases page](https://github.com/ghlre/GHLtarUtility/releases).

## GHLtar Utility Lite

The lite version removes the ability to use iOS guitars as the Bluetooth LE APIs are only available in Windows 10.

## Requirements

- GHLtar Utility requires Windows 10 (build 10240) or higher
- GHLtar Utility Lite requires Windows 7 or higher
- .NET Framework: 4.6 for non-lite, 4.5.2 for lite.
- WinUSB driver installed for the Guitar Hero PS3/Wii U dongles
- Bluetooth dongle for iOS guitars
- ViGEm Bus Driver

[Tutorial] Use PS3/Wii U/iOS Guitar Hero Live guitars on Clone Hero

I wrote a program to use Wii U/PS3 GHL guitars as well as iOS ones with Clone Hero. (Windows only for now)

    If you're using Windows 7, install .NET Framework 4.5.2

    Install the ViGEm Bus Driver (follow the instructions on the release page) - if you have Parsec installed, you'll already have this and you can skip this step.

    If you're using a Wii U/PS3 guitar, use Zadig to install the WinUSB driver for your dongle (select the Guitar Hero option, enable Show All Devices if necessary)

    Download the latest GHLtar Utility and extract it somewhere on your computer

    Run GHLtar Utility

    GHLtarUtility.exe - for Windows 10

    GHLtarUtilityLite.exe - for Windows 7/8.1, doesn't have iOS support!

    Connect your dongle if using the Wii U/PS3 guitar, turn on your guitar if using the iOS guitar.

    Start Clone Hero and make sure all buttons are mapped correctly (by default they are mapped 1:1 to the 360 GHL guitar)

    enjoy(TM)
