Gitter Desktop Client
===============================

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/gitterHQ/desktop?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The Gitter Desktop client is written using [NW.js](http://nwjs.io/) and is planned to be open sourced ([#2](https://github.com/gitterHQ/desktop/issues/2)). 

Downloads
---------

For the official downloads, please visit [https://gitter.im/apps](https://gitter.im/apps).

**Beta downloads**

* [Linux 32-bit deb package](https://update.gitter.im/linux32/latest)
* [Linux 64-bit deb package](https://update.gitter.im/linux64/latest)
* ~~OSX~~ Official version availabe on apps page, NWJS version coming soon

More Linux distributions will be made available soon.

Tray icon on Ubuntu
-------------------

To see the Gitter tray icon run:

```
sudo apt-add-repository ppa:gurqn/systray-trusty
sudo apt-get update
sudo apt-get upgrade
```

More info [here](http://ubuntuforums.org/showthread.php?t=2217458).

Enabling Logging on Windows
---------------------------
To enable logging on Windows, please [follow this guide](https://gist.github.com/trevorah/bfeb4ad69e4633dc76c5).

Changelog
---------
* 2015-02-12 `2.2.4`
  * Uses a more reliable version of the `gitter-realtime-client` fixing issues with tray and badge disconnecting.
* 2015-02-09 `2.2.3` — Fix Ubuntu libudev symlinking
* 2015-02-04 `2.2.2` — oauth fixes
* 2015-02-04 `2.2.1` — oauth fixes
* 2015-02-04 `2.2.0` — fixed autoupdater trashing the uninstaller
* 2015-02-03 `2.1.3` — autoupdate caching fixes
* 2015-02-03 `2.1.2` — autoupdate tweaks
* 2015-02-03 `2.1.1` — file menu tweaks
* 2015-02-02 `2.1.0` — added auto update
* 2015-01-22 `2.0.4` — alpha release for windows

