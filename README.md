# OpenTracker PKGBUILD

This repository includes the PKGBUILD files to install OpenTracker on Linux distributions based on the pacman package manager.

Main project repository: [https://github.com/trippsc2/OpenTracker](https://github.com/trippsc2/OpenTracker)

## Packages

| Name                   | Description                    |
|------------------------|--------------------------------|
| alttpr-opentracker     | Installs latest stable release |
| alttpr-opentracker-git | Installs bleeding edge release |

## Requirements

- base-devel
- git

## Installation

Most users should prefer to install latest stable release for general usage.

**Stable release**

```
git clone https://github.com/trippsc2/OpenTracker-pacman.git
cd OpenTracker-pacman/alttpr-opentracker
makepkg -si
```

**Bleeding edge**

```
git clone https://github.com/trippsc2/OpenTracker-pacman.git
cd OpenTracker-pacman/alttpr-opentracker-git
makepkg -si
```

> Note: Please refer to the Arch wiki for more specific instructions regarding installing PKGBUILD files.

## Issues

Please create a github issue with any problems related to the PKGBUILD files.
