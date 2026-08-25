# KNC Printer — Installation & EXE Return Codes

**Product:** KNC Printer  
**Publisher:** KNC TECHNOLOGY / KNCTECH  
**Current package version:** 2.7.1  
**Platform:** Windows 10 / Windows 11 (64-bit)

## Installation

KNC Printer is distributed as a Windows EXE installer.

Package name:

`KNC-PRINTER-Setup.exe`

The installer should be downloaded only from the official KNC Printer release location.

## EXE Return Codes

The following return code is used to indicate a successful installation:

| Return code | Meaning |
|---|---|
| `0` | Installation completed successfully |

If the installer returns another non-zero value, the installation did not complete successfully or was interrupted by Windows, the user, or another system condition.

Possible causes may include:

- installation cancelled by the user;
- insufficient disk space;
- another installation already running;
- Windows security or policy restrictions;
- insufficient permissions;
- a required system restart;
- damaged or incomplete installer download.

For a non-zero return code, retry the installation after resolving the related Windows condition.

## Silent Installation

KNC Printer can be installed using the silent-installation parameters configured for the package submitted to Microsoft Partner Center.

## Support

For installation problems, please use the official KNCTECH support channels or the KNC Printer release repository:

https://github.com/knctech/KNC-Print-Releases

## Updates

Each KNC Printer release is published as a versioned package.  
A new application version should use a new versioned release/package URL.
