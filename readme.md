# peermaps-data

This repo tracks p2p addresses and http mirrors for the most recent versions of
the peermaps datasets.

You can help out by seeding and mirroring them!

These addresses will be updated occasionally, so if you are seeding check this
document every so often to keep your seeds up to date until there's a more
automated tool.

## planet-osm eyros georender

This dataset imports [planet-osm][] into an [eyros][] database in the
[georender][] format.

Generated from September 2021 planet-osm snapshot.

Recommended zoom range: ??-21

* /ipfs/QmVCYUK51Miz4jEjJxCq3bA6dfq5FXD6s2EYp6LjHQhGmh
* hyper://3dd1656d6408a718fae1117b5283fb18cb1f9139b892ce0f8cacbb6737ec1d67
* https://peermaps.linkping.org/data

[planet-osm]: https://planet.openstreetmap.org/
[eyros]: https://github.com/peermaps/eyros
[georender]: https://github.com/peermaps/docs/blob/master/georender.md

## natural earth vector eyros georender

This dataset imports [natural earth][] vector data into an [eyros][] database in
the [georender][] format.

Generated from May 2022 snapshot.

There are 3 directories: 110m, 50m, and 10m.

Recommended zoom ranges: 110m: ??-??, 50m: ??-??, 10m: ??-??

* /ipfs/QmTes6hYgCZzcP4oXjyvT48UwmzfqvWApXHs77sTnJV7fq
* hyper://44763daa1dd8a6e804927c22de95752fa821a7a1bf06ca59a47c1fc27cb28150

[natural earth]: https://www.naturalearthdata.com/

## sparse geonames cities500

This dataset provides the cities500 dataset from [geonames][] in a
[sparse format](https://github.com/peermaps/sparse-geonames-ingest) suitable for
[queries without downloading the entire archive](https://github.com/peermaps/sparse-geonames-search).

* /ipfs/QmVsqp3ct4WXDzSPRBqgHW6fKkkbLjfpjrGp8k45wXHH6w
* hyper://cff2454cb4c21bd9c8f36d6f2ac45b32dbe3abbb5cb5996e8f06e249c5693437

[geonames]: https://download.geonames.org/export/dump/
