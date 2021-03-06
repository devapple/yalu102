# yalu102

## I am using Luca’s yalu code for my own use and will not release 10.2.x jailbreak of my own.

![Yalu logo](https://github.com/kpwn/yalu102/blob/master/yalu102/Assets.xcassets/AppIcon.appiconset/AppIcon60x60@3x.png?raw=true)

A "work in progress" iOS jailbreak for 64-bit devices created by [qwertyoruiopz](https://twitter.com/qwertyoruiopz) and [marcograssi](marcograss).

Please use the "Issues" tab for **code related** issues only. If you need support please search on [/r/jailbreak](https://reddit.com/r/jailbreak) before posting a question there.

## Supported Devices and iOS versions

| Device | Version | Other |
|---------|----------|---------|
| iPad Pro  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPhone 6S  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPhone SE  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPhone 5S  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPad Air| iOS 10.0.0 -> iOS 10.2 | n/a |
| iPad Mini 2| iOS 10.0.0 -> iOS 10.2 | n/a |
| iPhone 6  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPad Mini 3| iOS 10.0.0 -> iOS 10.2 | n/a |
| iPad Air 2| iOS 10.0.0 -> iOS 10.2 | n/a |
| iPad Mini 4 | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPod touch (6G)  | iOS 10.0.0 -> iOS 10.2 | n/a |
| iPhone 7 | iOS 10.0.0 -> 10.2.1 | mobile substrate disabled |
| iPhone 7 Plus | iOS 10.0.0 -> 10.2.1 | mobile substrate disabled |
| iPhone 5 | iOS 10.0.0 -> 10.1.1 | KPP bypass patched memory leak |

### Planned Support:

In the near future, the jailbreak will support the following devices:

| Device | Version | Additions | 
|---------|----------|----------|
| iPhone 7 | iOS 10.0.0 -> 10.2.1 | enable sub |
| iPhone 7 Plus | iOS 10.0.0 -> 10.2.1 | enable sub |
| iPhone 5 | iOS 10.0.0 -> iOS 10.2.1 | bypass |

**Note, the iPhone 7 is only supported till iOS 10.1.1**
If you are already on iOS 10.2 with an iPhone 7, **stay there**. The actual exploit behind this still works, but the KPP bypass does not.

## Compiling:

1. `git clone` the repo.
2. Open the repo in Xcode
3. Change the bundle ID, as shown [here](https://www.reddit.com/r/sideloaded/wiki/how-to-sideload#wiki_changing_the_bundle_identifier_and_team)
4. Include the IOKit headers, and add them to your search path.
5. Run the project.

## Warnings

This jailbreak is a work in progress. Some things do not work, but most things do.

Do not install things that are untested.

**AppSync and other unsupported and untested software will probably throw your device into a bootloop or do other bad things.** Do not open an issue complaining that your device has been bootlooped because you installed other software. You have been warned.

## Installing

> DO NOT DOWNLOAD THIS SOFTWARE FROM OTHER SOURCES OTHER THAN THESE LINKS UNDER ANY CIRCUMSTANCE. IT IS VERY EASY TO BACKDOOR THIS SORT OF SOFTWARE TO CONTAIN MALWARE. PLEASE BE EXTREMELY CAREFUL. THESE MIRRORS ARE TRUSTED, BUT STILL CHECK THE SHA1.

* Download the pre-compiled version from the table below.
* [Check the SHA1 hash](http://onlinemd5.com) of the downloaded file (optional but recommended).
* Install using [Cydia Impactor](http://www.cydiaimpactor.com/).
* Open the application and follow instructions.


| Version | Download |
|---------|----------|
| Beta 1 | Coming Soon |

## Contributing

Create a fork of the repository, make your changes and then create a pull request.
Please be sure to check if the pull request has been made before, before creating a new one. Note, any pull requests adding IOKit headers will be closed. Please respect copyright laws, and do not distribute / download IOKit headers from unofficial sources: they are bundled legally with macOS SDK

## Substrate

On the iPhone 7 & Plus models the mobile substrate has been disabled due to a KPP misuse of function in the code, please respect this and do NOT get any repos that re-enable this, doing so may cause malfunction to your device. 