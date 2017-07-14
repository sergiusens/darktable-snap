<h1 align="center">
  <img src="https://avatars1.githubusercontent.com/u/29598503?v=3&s=256" alt="Darktable">
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

    sudo snap install darktable-kyrofa

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->

<p align="center">Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with :gift_heart: by Snapcrafters</p>

## Run

Simply search for Darktable in the dash. If you prefer the command-line, use:

    darktable-kyrofa.darktable

Note that the interface providing access to removable media (e.g. external
hard drives, SD cards, etc.) is not automatically connected upon install. If
you'd like to access removable media, you need to give the snap permission to
do so by connecting that interface:

    sudo snap connect darktable-kyrofa:removable-media

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/join-snapcrafters/1325)) 
are working to land snap install documentation and
the [snapcraft.yaml](https://github.com/kyrofa/darktable-snap/blob/master/snap/snapcraft.yaml)
upstream so Darktable can authoritatively publish future releases.

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [ ] Register the snap in the store, **using the preferred upstream name**
  - [ ] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [ ] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [x] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link](https://forum.snapcraft.io/t/call-for-testing-darktable-v2-2-5snap1)
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, transfer the snap name from you to snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [x] Publish the snap in the Snap store stable channel
  - [x] Update the install instructions in this `README.md`
  - [x] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link](https://forum.snapcraft.io/t/call-for-testing-darktable-v2-2-5snap1/872/2?u=kyrofa)
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [ ] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![Kyle Fazzari](https://gravatar.com/avatar/e6ce51da1c672916ee1f56f55a6bf397?s=128)](https://github.com/kyrofa/) |
| :---: |
| [Kyle Fazzari](https://github.com/kyrofa/) |

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](http://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
