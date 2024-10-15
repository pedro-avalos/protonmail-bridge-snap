<h1 align="center">
  <img src="./snap/gui/protonmail-bridge.svg" alt="protonmail-bridge" width="256px">
  <br />
  Proton Mail Bridge
</h1>

<p align="center"><b>This is the snap for <a href="https://proton.me/mail/bridge">Proton Mail Bridge</a></b>,
<i>“Proton Mail Bridge is a desktop application that runs in the background,
encrypting and decrypting messages as they enter and leave your computer”</i>.
It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>

<p align="center">
<a href="https://snapcraft.io/protonmail-bridge">
  <img alt="enpass" src="https://snapcraft.io/protonmail-bridge/badge.svg" />
</a>
<a href="https://snapcraft.io/protonmail-bridge">
  <img alt="enpass" src="https://snapcraft.io/protonmail-bridge/trending.svg?name=0" />
</a>
</p>

![protonmail-bridge](screenshot.png?raw=true "protonmail-bridge")

<p align="center">Published for <img src="https://raw.githubusercontent.com/anythingcodes/slack-emoji-for-techies/gh-pages/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters</p>

## Install

```shell
sudo snap install protonmail-bridge
```

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/protonmail-bridge)

([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

## Snap configuration

You need to have a keychain in order to run the Proton Mail Bridge. To allow
access to the keychain, you have to manually connect the
[`password-manager-service`](https://snapcraft.io/docs/password-manager-service-interface)
plug.

```shell
sudo snap connect protonmail-bridge:password-manager-service
```

## Remaining tasks

Snapcrafters ([join us](https://forum.snapcraft.io/t/snapcrafters-reboot/24625)) are working to land snap install documentation and the [snapcraft.yaml](https://github.com/snapcrafters/fork-and-rename-me/blob/master/snap/snapcraft.yaml) upstream so [Project] can authoritatively publish future releases.

  - [x] Click the green "Use this template" button above to create a new repository based on this template
  - [X] Give the newly created repository a sensible name, like `godzilla` if you're snapping the Godzilla software (*Note: Do not use `snap` in this name.*)
  - [X] Update the description of the repository to `Unofficial snap for [Project]`
  - [X] Update logos and references to `[Project]` and `[my-snap-name]`
  - [X] Create a snap that runs in `devmode`
  - [X] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [X] Register the snap in the store, **using the preferred upstream name**
  - [X] Add a screenshot to this `README.md`
  - [X] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [X] Publish the confined snap in the Snap store beta channel
  - [X] Update the install instructions in this `README.md`
  - [X] Post a call for testing in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link](https://forum.snapcraft.io/t/call-for-testing-protonmail-bridge/43421?u=pedro-avalos)
  - [X] Add the Snapcraft store account (snap-advocacy@canonical.com) as a collaborator to your snap in the [Dashboard](https://dashboard.snapcraft.io) and ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to accept this request
  - [ ] Fix all important issues found during testing
  - [ ] Make a post in the Snapcraft Forum ["store-requests" category](https://forum.snapcraft.io/c/store-requests/19) asking for a transfer of the snap name from you to Snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the Snapcraft Forum ["Snapcrafters" category](https://forum.snapcraft.io/c/snapcrafters/23) - [link]()
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Ask upstream if they are interested in maintaining the Snap. If they are:
    - [ ] Fork the upstream project, add the snap build files and required assets/launchers to that repo and submit a pull request or patch - [link]()
    - [ ] Add upstream contact information to the `README.md`
    - If upstream accept the PR:
      - [ ] Request upstream create a Snap store account
      - [ ] Add upstream account as a collaborator on the snap
      - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream

If you have any questions, [post in the Snapcraft forum](https://forum.snapcraft.io).

## The Snapcrafters

| [![Pedro Avalos Jimenez](https://gravatar.com/avatar/99d80a655179643de6d2b8eccad0b12a16b21d778a5c2676ed9ab7dcaa0d889c/?s=128)](https://github.com/pedro-avalos/) |
| :---: |
| [Pedro Avalos Jimenez](https://github.com/pedro-avalos/) |

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
