# qcdnum-feedstock

[![hep-forge](https://img.shields.io/badge/package-hep--forge%2Fqcdnum-orange.svg)](https://anaconda.org/hep-forge/qcdnum)
[![Build & Upload](https://github.com/hep-forge/qcdnum-feedstock/actions/workflows/autoupload.yml/badge.svg)](https://github.com/hep-forge/qcdnum-feedstock/actions/workflows/autoupload.yml)
[![Anaconda Version](https://anaconda.org/hep-forge/qcdnum/badges/version.svg)](https://anaconda.org/hep-forge/qcdnum)
[![Anaconda Platforms](https://anaconda.org/hep-forge/qcdnum/badges/platforms.svg)](https://anaconda.org/hep-forge/qcdnum)

Feedstock for [qcdnum](https://www.nikhef.nl/~h24/qcdnum/index.html) — part of [hep-forge](https://anaconda.org/hep-forge).
Builds linux-amd64 + linux-arm64 in one matrix workflow and uploads to the
[hep-forge](https://anaconda.org/hep-forge) Anaconda channel.

QCDNUM is a very fast QCD evolution program written in FORTRAN77.

## Architectures

| Architecture | Latest published |
|--------------|------------------|
| linux-amd64 (`linux-64`) | ✅ `18.00.00` |
| linux-arm64 (`linux-aarch64`) | ✅ `18.00.00` |

_As of the last feedstock render; the badges above are live._


## Install

```bash
conda install -c hep-forge -c conda-forge qcdnum
```

## Maintainers

* [@meiyasan](https://github.com/meiyasan/)

