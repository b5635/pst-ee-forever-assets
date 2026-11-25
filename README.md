# PST Forever: lighting data

Per-area lighting data (height, normals, ambient occlusion, baked lights) and sprite depth for the dynamic
lighting of [PST Forever](https://github.com/b5635/pst-ee-forever), a mod for _Planescape: Torment:
Enhanced Edition_ (GOG 3.2.2.0). The lighting data comes from the [GemRB](https://gemrb.org)-based pipeline.

## Install

1. Install [PST Forever](https://github.com/b5635/pst-ee-forever/releases).
2. Download `pst_forever-lighting.zip` from this repository's Releases page (not "Source code").
3. Unzip it into the game folder, next to `Torment.exe`.
4. Run `pst_forever_config.exe` and switch lighting on.

## Releasing

Push a tag such as `v1.0.0`; GitHub Actions builds the zip and publishes the release.
