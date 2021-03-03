<h1 align="center">
  <img src="snap/gui/steamlink.png" alt="Steam Link">
  <br />
  Steam Link
</h1>

<p align="center"><b>This is the snap for Steam Link</b> to <i>"stream games from another computer with Steam"</i>. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.</p>

<p align="center">
  <a href="https://snapcraft.io/steamlink">
    <img alt="steamlink" src="https://snapcraft.io/steamlink/badge.svg" />
  </a>
  <a href="https://snapcraft.io/steamlink">
    <img alt="steamlink" src="https://snapcraft.io/steamlink/trending.svg?name=0" />
  </a>
</p>

![steamlink](.github/screenshot.png?raw=true "SteamLink")


## Install

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/steamlink)

    snap install steamlink
    snap connect steamlink:audio-record
    snap connect steamlink:joystick
    snap connect steamlink:hardware-observe
    snap connect steamlink:network-manager-observe

## About

The Steam Link app allows you to stream games from your other computers. Just
plug in a controller, connect to a computer running Steam on the same local
network, and start playing your existing Steam games.

An unofficial snap built with ❤︎ by Martin Wimpress using configuration at
<https://github.com/Wimpressive-Snaps/steamlink-snap> and the upstream
project <https://repo.steampowered.com/steamlink/>.
