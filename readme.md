# peermaps-data

This repo tracks p2p addresses and http mirrors for the most recent versions of
the peermaps datasets.

You can help out by seeding and mirroring them!

These addresses will be updated occasionally, so if you are seeding check this
document every so often to keep your seeds up to date until there's a more
automated tool.

## planet-osm eyros georender

This dataset imports [planet-osm][] into an [eyros][] database in the
[georender][] format. Size `100GiB`.

Generated from September 2021 planet-osm snapshot.

Recommended zoom range: ??-21

* `/ipfs/QmVCYUK51Miz4jEjJxCq3bA6dfq5FXD6s2EYp6LjHQhGmh` (CIDv0)
* `/ipfs/bafybeidf5yn56cxk6zkyjmay4wigu2o7ynqh7q62z3kppag5v7jpqavy5q` (CIDv1)
* `hyper://3dd1656d6408a718fae1117b5283fb18cb1f9139b892ce0f8cacbb6737ec1d67`
* `https://peermaps.linkping.org/data`

[planet-osm]: https://planet.openstreetmap.org/
[eyros]: https://github.com/peermaps/eyros
[georender]: https://github.com/peermaps/docs/blob/master/georender.md

## natural earth vector eyros georender

This dataset imports [natural earth][] vector data into an [eyros][] database in
the [georender][] format.

Generated from May 2022 snapshot.

There are 3 directories: 110m, 50m, and 10m.

Recommended zoom ranges: 110m: ??-??, 50m: ??-??, 10m: ??-??

* `/ipfs/QmTes6hYgCZzcP4oXjyvT48UwmzfqvWApXHs77sTnJV7fq` (CIDv0)
* `/ipfs/bafybeico6ts6stvi2qsdxyd4e7cyyohwz77hzrzizjqnylof54ujb2pywq` (CIDv1)
* `hyper://44763daa1dd8a6e804927c22de95752fa821a7a1bf06ca59a47c1fc27cb28150`

[natural earth]: https://www.naturalearthdata.com/

## sparse geonames cities500

This dataset provides the cities500 dataset from [geonames][] in a
[sparse format](https://github.com/peermaps/sparse-geonames-ingest) suitable for
[queries without downloading the entire archive](https://github.com/peermaps/sparse-geonames-search).

* `/ipfs/QmcWEeF9UGuo1VUw8N97uEH5rjcXvoay2fJusDvajHfmNN` (CIDv0)
* `/ipfs/bafybeigspa3h7jz7tqeepgm37njmfo2nwkard6tklojimlcu4i4zltay64` (CIDv1)
* `hyper://c1fed4a7be3d36e437fec0fba04d40fee7565ccf756c4801ffcea2f0ae1eecc9`

[geonames]: https://download.geonames.org/export/dump/

## qbzf fonts

noto, liberation, and dejavu fonts imported into [qbzf][] format

* `/ipfs/QmNQCPGV3XZrtNdQyMbZhSJcGisg4xCFyxeHs1tacrdETm` (CIDv0)
* `/ipfs/bafybeiaa5chmilnm2zy46xptvnl3jikyz234bd2yabj4ztkvqwnretefgq` (CIDv1)
* `hyper://126065f6b93924f976034b84ce74d9d570a44903ce9d110069a7aa65ddccd507`

[qbzf]: https://github.com/peermaps/qbzf
