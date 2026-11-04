# REG-Station binaries

Prebuilt releases of **REG-Station**, the REG-Linux frontend.

REG-Station is **not open source**. Only the binaries are published here.
They are built for specific REG-Linux versions and will not work anywhere
else.

## What is open and what is not

| Component | Licence |
|-----------|---------|
| `regstation`, its translations and its own data files | Proprietary (`LicenseRef-REG-Station`). See [LICENSE.md](LICENSE.md) |
| Open-source code compiled in (EmulationStation, rcheevos, glslang, SPIRV-Cross and others) | Their own licences. See `/usr/share/regstation/THIRD_PARTY_LICENSES` in each archive |
| Bundled fonts | Apache-2.0, SIL OFL 1.1, Ubuntu Font Licence. See `THIRD_PARTY_LICENSES` |
| Start-up scripts and sway/weston configuration | REG-Linux's licence |

Each archive carries the licence (`/usr/share/regstation/LICENSE`) and the
notices of every open-source part (`/usr/share/regstation/THIRD_PARTY_LICENSES`).

The rest of REG-Linux (kernel, Buildroot tree, board support, patches,
the libraries REG-Station links to) is GPL-2.0 or another open-source
licence. Its source is published at https://github.com/REG-Linux/REG-Linux.
