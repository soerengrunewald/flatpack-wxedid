# Flatpak Package of wxEDID

## Prepare

[Check](https://docs.flatpak.org/en/latest/first-build.html) to setup
flatpak-builder.

## Build

    $ flatpak-builder build-dir net.sourceforge.wxedid.yaml

## Install

    $ flatpak-builder --user --install --force-clean build-dir net.sourceforge.wxedid.yaml

