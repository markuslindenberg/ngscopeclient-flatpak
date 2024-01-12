# Proof of concept flatpak manifest for ngscopeclient

## Prerequisites

Flatpak, see https://flatpak.org/setup/

## Building

```
flatpak --user install flathub org.flatpak.Builder
flatpak run org.flatpak.Builder --user --install --force-clean build-dir org.ngscopeclient.ngscopeclient.yml

```

## Running

```
flatpak run org.ngscopeclient.Ngscopeclient
```
