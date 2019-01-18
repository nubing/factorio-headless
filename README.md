Factorio Headless Snap
===============

Headless server for Factorio running as a system service.

Change configuration options
sudo snap get factorio-headless
sudo snap set factorio-headless admins='["kovarex"]'
sudo snap set factorio-headless game-password=1337
sudo snap restart factorio-headless

Control the service and check status
sudo snap start factorio-headless
sudo snap stop factorio-headless
sudo snap start --enable factorio-headless
sudo snap stop --disable factorio-headless
sudo snap services | grep factorio-headless

Server files location
ls /var/snap/factorio-headless/common

## Install

Get it from the Snap Store or install in terminal.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/factorio-headless)

	snap install factorio-headless

## Links

- [Factorio Website](https://factorio.com).