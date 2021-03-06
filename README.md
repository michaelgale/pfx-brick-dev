# pfx-brick-dev

This repository contains resources shared by Fx Bricks with the public developer community for the PFx Brick. These resources include language asset files for localization, documentation, APIs, and more. This repository also serves as a focal point for capturing bugs, issues, and feature requests by the user community.

## Localization

The localization folder contains strings and other assets used for building different localized versions of both the desktop and mobile PFx App. The folder is organized by language code (EN, DE, etc.) and each folder contains product/platform specific sub-folders for iOS, Android, etc.

For iOS Apps, the key assets are:
* **localizable.strings** - a text file organized as token/quoted string pairs. Both the token and string are enclosed in double quotations marks (""), separated by an equals sign (=), and terminated by a semi-colon (;), e.g.
```
"disconnected_title" = "Disconnected";
```
* **AppStoreDesc-XX.txt** - a text file containing the public description of the iOS app in the Apple App Store, where XX represents the language code, e.g. EN, DE, etc.

## Documentation

The doc folder stores documentation, templates, etc. for publicly issued documentation.

## Issues

The Issues facility of GitHub should be used to submit bug reports and feature requests for the PFx Brick firmware, the desktop and mobile PFx App and the PFx Brick API.  Issues should be clearly tagged to identify which software component it applies (PFx App, iOS, firmware, Windows, etc.), as well as the type of issue, i.e. bug, feature-request, todo, etc. 
