# MapBBCode Share Changelog

Versions are numbered `N.M-S`, where `N.M` is the MapBBCode library version, and `S` is the Share build, independent of the library version. There are no "stable" versions and releases: the latest version is always the one to install.

### 1.1-7, 2013-11.29

* Updated MapBBCode to 1.1.2-dev.
* Added attribution edit link
* Fixed cache purging.

### 1.1-6, 2013-11-26

* Updated MapBBCode to 1.1.2-dev.
* Added length measurement with a new plugin.

### 1.1-5, 2013-11-23

* Website now works in subfolders and without mod_rewrite. [#4](https://github.com/MapBBCode/share.mapbbcode.org/issues/4)
* Fixed edit id reset after importing a file. [#7](https://github.com/MapBBCode/share.mapbbcode.org/issues/7)
* OziExplorer formats now can have their own encoding (usually iso or cp1251). [#6](https://github.com/MapBBCode/share.mapbbcode.org/issues/6)

### 1.1-4, 2013-11-16

* Updated MapBBCode to version 1.1.1.

### 1.1-3, 2013-11-13

* Updated MapBBCode to version 1.1.0.
* Updated MapBBCode parsing functions, semicolons in titles are now processed correctly.
* Forgot to replace one bbcode specification link.

### 1.0-2, 2013-11-12

* Empty CSV now doesn't have a header to not confuse users; single path is saved as csv.
* BBCode tags can be omitted in `?bbcode=` parameter.
* Moved Bing key to a configuration file.
* Ability to work without a database. [#3](https://github.com/MapBBCode/share.mapbbcode.org/issues/3)
* Merge imported traces with existing data. [#2](https://github.com/MapBBCode/share.mapbbcode.org/issues/2)
* Highlight "Save" button on map change. [#1](https://github.com/MapBBCode/share.mapbbcode.org/issues/1)
* Rephrased the message with a link for sharing.
* New OpenMapSurfer tile URL.
* New configuration keys: `BING_KEY`, `IMPORT_SINGLE`.

### 1.0-1, 2013-11-01

* Added Cycle Map layer.
* Rephrased the message with a link for sharing.
* Restricted bots from editing pages.

### 1.0-0, 2013-10-31

Initial release.
