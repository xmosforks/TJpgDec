# TJpgDec

This repository is an XMOS-maintained import of ChaN's Tiny JPEG Decompressor
(TJpgDec). It exists because the upstream project is distributed from the
author's website as ZIP archives rather than from a canonical Git repository.

Upstream project: <https://elm-chan.org/fsw/tjpgd/>

Archives: <https://elm-chan.org/fsw/tjpgd/archives.html>

Official patches: <https://elm-chan.org/fsw/tjpgd/patches.html>

## Repository Layout

The `src/` and `doc/` directories are imported from upstream release archives.
The first eight commits reconstruct the upstream release snapshots in order and
are tagged using the upstream revision names.

## Upstream Releases

| Revision | Date | Archive | SHA-256 |
| --- | --- | --- | --- |
| R0.01 | 2011-10-04 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd1.zip> | `5eac760de32ee171c23482c26825eb8fdde6e35a76cbe9b2ae7fb39120218f0c` |
| R0.01a | 2012-02-19 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd1a.zip> | `5e9bac39fd7483a5a24f58d5dc80c29527b445cb9c416a0c54b06d20b6ddb737` |
| R0.01b | 2012-09-03 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd1b.zip> | `452b43a804a638a303191095253d82d4e38d73358ca0f8d5557f75adab064afc` |
| R0.01c | 2019-03-16 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd1c.zip> | `825358319794193ea7453810a4ecb9514d7ccf4c23e3ec5fbf84a3f97e6247e4` |
| R0.01d | 2020-07-01 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd1d.zip> | `a37868de15364e76978f250e9d3d23344f8ffeaf7b92c2ef0bc35b0c95530106` |
| R0.02 | 2021-05-08 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd2.zip> | `d3d4609c616317e34e75b07d48a6819f4e163098c9dabcc299ed260a12ddf904` |
| R0.02a | 2021-06-11 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd2a.zip> | `528895fe6f1daa2ea6596d7b60072101d3f41d62092b3b9837990e10e24cf0de` |
| R0.03 | 2021-07-01 | <https://elm-chan.org/fsw/tjpgd/arc/tjpgd3.zip> | `052fe3efbc9a8be29f31597ad009c5b51a4f6905878eb28569e0ab3d46d0c013` |

## Tags

The upstream archive imports are tagged `R0.01`, `R0.01a`, `R0.01b`, `R0.01c`,
`R0.01d`, `R0.02`, `R0.02a`, and `R0.03`.

The official May 17, 2023 upstream patch for R0.03 is applied separately and
tagged `R0.03-p1`.

XMOS-specific changes are kept in separate commits after upstream imports and
patches.

## License

TJpgDec is distributed under a custom permissive license. See `LICENSE.txt` and
the copyright/license notice preserved in `src/tjpgd.c`.
