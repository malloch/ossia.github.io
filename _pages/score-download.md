---
layout: score-page
title:  "Download"

permalink: /score/download.html
category: site-score
score_dl: https://github.com/ossia/score/releases/download/v3.0.0-a19
score_version: 3.0.0-a19
---

Download the latest alpha release __ossia score v{{page.score_version}}__:
<p style="display: flex; justify-content: center;align-content:space-evenly;" align="center">
<a href="{{page.score_dl}}/ossia.score-{{page.score_version}}-win64.exe" target="_blank" class="page-button download-page"><img src="../assets/windows_logo_2012-Black.svg" height="80px"/>Windows 10</a>
<a href="{{page.score_dl}}/ossia.score-{{page.score_version}}-macOS.dmg"  target="_blank" class="page-button download-page" ><img src="../assets/apple_logo_black.svg" height="80px"/>Mac OS<br/>10.14, 10.15</a>
<a href="{{page.score_dl}}/ossia.score-{{page.score_version}}-linux-amd64.AppImage" target="_blank" class="page-button download-page"><img src="../assets/Linux_Platform.svg" height="80px"/>Linux</a>
</p>
See the <a href="https://github.com/OSSIA/score/releases/latest" target="_blank">change log</a> for the latest release.

## Supported platforms

The releases are 64-bit on all operating systems.

* Windows: must be at least Windows 10.
* macOS: must be at least Mojave (10.14).
* All Linux distributions from at least 2015-era should be supported. 
  * The packages are built on CentOS 7
  * Your system must have at least glibc-2.17, as well as X11, ALSA, libGL, librt, libdbus.
  * libavahi is required at runtime for Zeroconf support.
  * libbluez is necessary to use Wiimotes (which go through Bluetooth).

## Source code

The source code for the latest release can be downloaded from here: 
* Latest release's <a href="{{page.score_dl}}/ossia.score-{{page.score_version}}-src.tar.xz">source code</a>
* Latest release's <a href="{{page.score_dl}}/ossia.score-{{page.score_version}}-src.tar.xz.asc">source code signature</a>
* Alternatively, you can fetch the latest source code <a href="https://github.com/OSSIA/score">directly from Github</a>

## Stable version

The latest stable version is <a href="https://github.com/ossia/score/releases/tag/v2.5.2" target="_blank">2.5.2</a> - it won't be updated anymore however.
Due to substantial changes to the software the save files are not importable yet in the 3.0 branch.
