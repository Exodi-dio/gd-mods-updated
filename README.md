# GD Mods Updated

Personal builds of open-source Geode mods recompiled for **Geometry Dash 2.2091**.

These exist because the mod index (and most mods) still target 2.2081, and I run GD 2.2091 on mobile with Geode nightly. Each mod is built from its upstream source by GitHub Actions — no local builds, no binaries of unknown origin. Full source and workflow runs are public in the linked repos.

> **Requires Geode nightly.** Stable Geode 5.11.2 ships an SDK that is 2.2081-only for Android and will refuse a 2.2091 build.

## Mods

| Mod | Version | Platform | Download | Source |
| --- | --- | --- | --- | --- |
| Jukebox | 3.8.1 | Android (arm64 + armv7) | [fleym.nongd.geode](https://github.com/Exodi-dio/jukebox/releases/download/v3.8.1-android-2.2091/fleym.nongd.geode) | [Fleeym/jukebox](https://github.com/Fleeym/jukebox) (MIT) |

## Installing on a phone

1. Tap the download link above (it downloads a `.geode` file to your phone).
2. Open GD with Geode installed.
3. Geode → **Mods** → the **+** / install button → pick the `.geode` file from your Downloads folder.
4. Restart the game.

If GD refuses it, check Geode's version — you need a nightly build, not a stable release.

## Not included

Mod menus and cheat clients (GDH, Eclipse Menu, Prism Menu) are deliberately not built here. They are closed to this kind of redistribution or carry cheat feature sets, and I'm not rebuilding them.

## Attribution

Every mod here is someone else's work, built unchanged except for the GD version bump. Licenses are those of the upstream projects — see each mod's source link.
