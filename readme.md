# Gloomhaven (GH)

An easy-to-use collection of data and images from [Gloomhaven](http://www.cephalofair.com/gloomhaven) by [Cephalofair Games](http://www.cephalofair.com/) - Developer: **Isaac Childres**.

11/10/2021: Only used for Firefox Add-On. The new Chrome Extension is powered by [Worldhaven Asset Viewer](https://github.com/any2cards/worldhaven).

## What's included

This repository contains data and images for the following components:

- attack-modifiers
- battle-goals
- character-ability-cards
- character-mats
- character-perks
- deprecated-assets
- events
- items
- map-tiles
- milestone-ability-cards
- milestones
- monster-ability-cards
- monster-stat-cards
- personal-quests
- player-aid-cards
- random-dungeons
- random-scenarios
- tokens
- world-map

There are four top-level directories; `data` , `images` , `pbf` ,and `xwc`.

### data

The `data` folder contains all GH Card Viewer data in JSON format.

### images

The `images` folder contains all GH Card Viewer images for each of the above components.

### pbf

The `pbf` folder contains specific GH Card Viewer images for Play By Forum (PBF) use.

### xwc

The `xwc` folder contains all of the files that power the GH Card Viewer Chrome Extension/Firefox Add-On.

## Usage

You can use this data to build your own apps, etc.

The easiest way to do this is via [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules#Starting-with-Submodules):

* Git submodule: `git submodule add https://github.com/any2cards/gloomhaven.git`

## Bugs / Issues

Please [open a ticket](https://github.com/any2cards/gloomhaven/issues/new) on Github.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :tada:

When adding images please use [TinyPNG](https://tinypng.com/) to reduce their filesize as much as possible without affecting image quality.

## Projects

A list of projects that use this content:

- [GH Card Viewer](https://addons.mozilla.org/en-US/firefox/addon/gloomhaven-card-viewer/) (Firefox Add-On)

Want your project listed here? [Let us know!](https://github.com/any2cards/gloomhaven/issues/new?title=Add%20Project)

## Versioning

This project uses [SemVer](http://semver.org/). Given a `MAJOR.MINOR.PATCH` version number, we will increment the:
- `MAJOR` version when existing content is changed in such a way that it can break consumers of the data
- `MINOR` version when new content is added in a backwards-compatible manner, or existing content is changed in a backwards-compatible manner
- `PATCH` version when fixing mistakes in existing content

## History

See the [Releases tab](https://github.com/any2cards/gloomhaven/releases) in Github.

## Contributors

- William Habush (any2cards@yahoo.com)
- Guido Hansen (sadgit@penultimate.de)

This work would not have been possible without the invaluable help and guidance of Guido Kessels. You can find his excellent X-Wing data at: https://github.com/guidokessels/xwing-data.

---

Gloomhaven: Gloomhaven and all related properties, images and text are owned by Cephalofair Games.

