# Darktable Snap

Darktable packaged as a snap. Install with:

    $ sudo snap install darktable-kyrofa


To run, simply search for Darktable in the dash. If you prefer the command-line,
use:

    $ darktable-kyrofa.darktable

Note that the interface providing access to removable media (e.g. external
hard drives, SD cards, etc.) is not automatically connected upon install. If
you'd like to access removable media, you need to give the snap permission to
do so by connecting that interface:

    $ sudo snap connect darktable-kyrofa:removable-media ubuntu-core:removable-media
