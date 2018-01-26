<h1 align="center">
  <img src="https://raw.githubusercontent.com/kyrofa/darktable-snap/master/snap/gui/logo.png" alt="Darktable">
  <br />
  Darktable
</h1>

<p align="center"><b>This is the snap for Darktable</b>, <i>"Virtual lighttable and darkroom for photographers"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

## Install

    sudo snap install darktable

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

## Run

Simply search for Darktable in the dash. If you prefer the command-line, just run `darktable`.

Note that the interface providing access to removable media (e.g. external
hard drives, SD cards, etc.) is not automatically connected upon install. If
you'd like to access removable media, you need to give the snap permission to
do so by connecting that interface:

    sudo snap connect darktable:removable-media
