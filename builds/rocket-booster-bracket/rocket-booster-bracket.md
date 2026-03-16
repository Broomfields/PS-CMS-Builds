---
title: "Rocket Booster Bracket"
description: "Custom two-part motor mount designed to hold locally available boosters in a rocket chassis built for larger ones."
date: "2021-07-31"
cover: "02-model-cap"
cover_alt: "Bracket cap model — top view showing the booster retaining geometry"
gallery:
  - name: "01-model-study"
    label: "Bracket — Cap Study, recreating original booster cap as a model"
  - name: "02-model-cap"
    label: "Bracket — Cap, this braces the top of the boosters, and has a cap to hold them in the bracket"
  - name: "03-model-brace"
    label: "Bracket — Brace, this braces the bottom of the boosters and acts as the rocket base"
  - name: "04-rig"
    label: "Launch rig"
  - name: "05-rocket-base"
    label: "Rocket body"
  - name: "06-rocket"
    label: "Rocket assembled and ready"
tags: ["openscad", "3d-printing", "rocketry"]
cad_tool: "OpenSCAD"
status: "complete"
license: "CC BY-SA 4.0"
featured: true
links:
  - label: "Printables"
    url: "https://www.printables.com"
  - label: "Thingiverse"
    url: "https://www.thingiverse.com"
subpages:
  - "print-settings"
files:
  - name: "01-rocket-cap"
    label: "Bracket Cap — OpenSCAD Source"
  - name: "02-rocket-brace"
    label: "Bracket Brace — OpenSCAD Source"
  - name: "03-rocket-cap-model"
    label: "Bracket Cap — STL"
  - name: "04-rocket-brace-model"
    label: "Bracket Brace — STL"
  - name: "05-rocket-study"
    label: "Bracket Study — OpenSCAD Source"
---

Here's the situation: the rocket was built for bigger motors than we could actually source locally. Not ideal when you're trying to, y'know, launch the thing. Rather than tear apart the whole chassis and start over, I figured the smarter move was a custom mount that could hold the smaller boosters we *could* get.

See [Print Settings](print-settings) for slicer configuration.

## Design

The mount is two parts. The cap braces the top of the boosters and holds them in the bracket. The brace handles the bottom and doubles as the rocket base, with a retaining lip at one end so the boosters can't travel through under thrust.

Both parts share a common variables file, so if the booster dimensions ever need changing you only have to update them in one place. Worth it.

