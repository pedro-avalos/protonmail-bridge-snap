<h1 align="center">
  <img src="./snap/gui/protonmail-bridge.svg" alt="protonmail-bridge" width="256px">
  <br />
  Proton Mail Bridge
</h1>

<p align="center"><b>This is the snap for <a href="https://proton.me/mail/bridge">Proton Mail Bridge</a></b>,
<i>"Proton Mail Bridge is a desktop application that runs in the background,
encrypting and decrypting messages as they enter and leave your computer"</i>.
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
