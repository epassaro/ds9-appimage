# ds9-appimage
Builds of SAOImage DS9 in the AppImage format

## Release cycle
This repository uses GitHub Actions to make weekly AppImage builds of [SAOImage DS9](https://github.com/SAOImageDS9/SAOImageDS9) in two variants:

- [Latest tag](https://github.com/epassaro/ds9-appimage/releases/latest)
- [Continuous build](https://github.com/epassaro/ds9-appimage/releases/tag/continuous)

> NOTE: This project does not build beta versions of DS9

## Installation
Download an AppImage from the [releases section](https://github.com/epassaro/ds9-appimage/releases), make it executable, and run.

Newer Ubuntu systems may require the _libfuse2_ library:

```bash
$ sudo apt install libfuse2
```

## Motivation
I began this project primarily for research purposes because I've been wanting to learn how to distribute software in the AppImage format for a while. 

I decided to start with DS9 because it's a piece of software I'm familiar with, and it's relatively easy to build.

## See also
- [ds9-flatpak](https://github.com/epassaro/ds9-flatpak) - My Flatpak recipe for DS9
