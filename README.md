# LaTeX DevContainer Template

A fully reproducible LaTeX development environment designed for VS Code Remote Containers. Includes a complete TeX Live installation, Biber/BibLaTeX support, minted, and automatic PDF builds via LaTeX Workshop.

## Features

- Zero LaTeX installation required on the host machine
- Works with Flatpak VS Code and immutable systems (e.g. Fedora Silverblue/Bazzite)
- Full TeX Live distribution including IEEE and thesis templates
- BibLaTeX+Biber support pre-configured
- latexmk with shell-escape enabled
- Fully isolated development dependencies

## Usage

1. Clone this repo
2. Open in VS Code
3. Choose "Reopen in Container"
4. Build your LaTeX project normally — the PDF viewer works automatically

## Requirements

- Docker or Podman
- VS Code + Remote Containers extension

## Why?

Local LaTeX installations are notoriously inconsistent between machines and very unfriendly to immutable Linux systems like Fedora Silverblue and Bazzite. Packaging LaTeX inside a development container guarantees identical results everywhere. I created this to use LaTeX across various atomic Fedora distros, macOS, and Windows.
