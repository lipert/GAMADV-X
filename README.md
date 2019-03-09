- [Introduction](#introduction)
- [Requirements](#requirements)
- [Downloads](#downloads)
- [Installation - First time GAM installation](#installation---first-time-GAM-installation)
- [Installation - Upgrading from a GAM version other than a prior version of GAMADV-X or GAMADV-XTD](#installation---upgrading-from-a-gam-version-other-than-a-prior-version-of-gamadv-x-or-gamadv-xtd)
- [Installation - Upgrading from a prior version of GAMADV-X or GAMADV-XTD](#installation---upgrading-from-a-prior-version-of-gamadv-x-or-gamadv-xtd)

# Introduction
GAMADV-X is a free, open source command line tool for Google G Suite Administrators to manage domain and user settings quickly and easily.

This page provides simple instructions for downloading, installing and starting to use GAMADV-X.

GAMADV-X requires G Suite for Business, Education, Non Profit, Partner or Government Edition. Google Apps Free Edition has limited API support and not all GAM commands work.

GAMADV-X is a rewrite/extension of Jay Lee's [GAM](https://github.com/jay0lee/GAM), without his efforts, this version wouldn't exist.

GAMADV-X is backwards compatible with [GAM](https://github.com/jay0lee/GAM), meaning that if your command works with regular GAM, it will also work with GAMADV-X. There may be differences in output, but the syntax is compatible.

# Documentation
General GAM documentation is hosted in the [GitHub Wiki]. Documentation specifically for GAMADV-X is hosted in the [GitHub GAMADV-X Wiki] and in Gam*.txt files.

# Mailing List / Discussion group
The GAM mailing list / discussion group is hosted on [Google Groups].  You can join the list and interact via email, or just post from the web itself.

# Source Repository
The official GAMADV-X source repository is on [GitHub] in the master branch.

# Author
GAMADV-X is maintained by <a href="mailto:ross.scroggs@gmail.com">Ross Scroggs</a>.

# Requirements
To run all commands properly, GAMADV-X requires three things:
* An API project which identifies your install of GAMADV-X to Google and keeps track of API quotas.
* Authorization to act as your G Suite Administrator in order to perform management functions like add users, modify group settings and membership and pull domain reports.
* A special service account that is authorized to act on behalf of your users in order to modify user-specific settings and data such as Drive files, Calendars and Gmail messages and settings like signatures.

# Downloads
You can download the current GAMADV-X release from the [GitHub Releases](https://github.com/taers232c/GAMADV-X/releases) page.

* Download: https://github.com/taers232c/GAMADV-X/wiki#downloads

# Installation - First time GAM installation
* Configuration: https://github.com/taers232c/GAMADV-X/wiki/gam.cfg
* Download: https://github.com/taers232c/GAMADV-X/wiki#downloads
* Install: https://github.com/taers232c/GAMADV-X/wiki/How-to-Install-Advanced-GAM

# Installation - Upgrading from a GAM version other than a prior version of GAMADV-X or GAMADV-XTD
* Configuration: https://github.com/taers232c/GAMADV-X/wiki/gam.cfg
* Download: https://github.com/taers232c/GAMADV-X/wiki#downloads
# Install: https://github.com/taers232c/GAMADV-X/wiki/How-to-Upgrade-from-Standard-GAM

# Installation - Upgrading from a prior version of GAMADV-X or GAMADV-XTD
* Updates: https://github.com/taers232c/GAMADV-X/wiki/GAM-Updates
* Download: https://github.com/taers232c/GAMADV-X/wiki#downloads

You can install multiple versions in different parallel directories.

[GitHub Releases]: https://github.com/taers232c/GAMADV-X/releases
[GitHub]: https://github.com/taers232c/GAMADV-X/tree/master
[GitHub Wiki]: https://github.com/jay0lee/GAM/wiki/
[GitHub GAMADV-X Wiki]: https://github.com/taers232c/GAMADV-X/wiki/
[Google Groups]: http://groups.google.com/group/google-apps-manager
