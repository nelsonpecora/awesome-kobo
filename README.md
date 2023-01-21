# awesome-kobo [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

This is a curated list of awesome resources for Kobo users, based on similar lists for [Kindle](https://github.com/inchei/awesome-kindle) and [Boox](https://github.com/emory/awesome-boox).

Suggestions and contributions are welcome!

## Built-in Kobo Functionality

* Reading ebooks from the Kobo store
* Sideloading ebooks via USB or (on fancier devices) Dropbox
* Integration with Pocket, for web articles
* Integration with Overdrive, for library books
* Listening to audiobooks from the Kobo store (on certain devices)
* Integration with Readwise, to sync highlights and annotations

## Kobo Apps

Software that runs on your Kobo itself. These are usually installed by:

1. Pluggin your Kobo in via USB
2. Adding the relevant `KoboRoot.tgz` file to the `/.kobo` directory of your device
3. Ejecting and disconnecting your device, which will trigger the app installation

> **Note:** Many apps have required config files that you need to fill out after they've installed. You'll need to reconnect your device to edit the config file afterwards, so don't forget about this step!

* [NickelDBus](https://github.com/shermp/NickelDBus) - A library that allows app developers to hook into Kobo's native application. Required by many apps
* [NickelMenu](https://github.com/pgaskin/NickelMenu) - Adds a new menu to Kobo's native app. Used by many apps to provide UI controls
* [KFMon](https://github.com/NiLuJe/kfmon) - Kute File Monitor, a library that allows app developers to hook into `inotify` to watch for file changes
* [KoboMail](https://github.com/clisboa/KoboMail) - Allows emailing ebooks to your Kobo, like Send to Kindle
* [KoboCloud](https://github.com/fsantini/KoboCloud) - Allows synching ebooks with multiple cloud services
* [NickelSeries](https://www.mobileread.com/forums/showthread.php?p=4013888) - Adds support for series and subtitle metadata on sideloaded ebooks
* [Kobo Weather App](https://bitbucket.org/david_weese/kobo-weather-app/src/master/) - Weather forecast app
* [Wallabako](https://gitlab.com/anarcat/wallabako) - Kobo reader for [Wallabag](https://www.wallabag.it/en) articles
* [NickelClock](https://www.mobileread.com/forums/showthread.php?t=347608) - A small app that shows the Kobo time widget while reading

## Useful Utils

* [Dictutil](https://pgaskin.net/dictutil/) - Custom dictionaries and tools to create them
* [Kepubify](https://pgaskin.net/kepubify/) - Converts EPUB files into Kobo's enhanced KEPUB format

## Alternate Reading Apps

These are full replacements for the native Kobo app.

* [Koreader](https://github.com/koreader/koreader) - Fully featured replacement for native Kobo (and more) functionality
* [Plato](https://github.com/baskerville/plato) - Kobo-specific full replacement
* [Ultimate Manga Reader](https://www.mobileread.com/forums/showthread.php?t=331635) - An online manga reader
* [InkBox](https://github.com/Kobo-InkBox/inkbox) - A whole new OS

## Tips and Tricks

* [MobileRead list of Tweaks/Hacks/Mods](https://www.mobileread.com/forums/showthread.php?t=217160) - Massive list of things not covered here, including some incredibly useful tips for app developers
* [Kobo Development Tutorial: 0 to Hero](https://www.mobileread.com/forums/showthread.php?t=297335) - For aspiring devs

## Contribution Guidelines

* Add items as `* [Project name](url of GitHub reposity page / homepage) - Description`
