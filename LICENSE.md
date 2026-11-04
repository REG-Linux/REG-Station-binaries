# REG-Station licence

<!-- SPDX-License-Identifier: LicenseRef-REG-Station -->

**Licence identifier:** `LicenseRef-REG-Station` (proprietary, with open-source parts listed in section 2). There is no SPDX licence for it, so GitHub lists this file as "Other".

Copyright (c) 2026 the REG-Linux authors (Romain Tisserand, Carlos
Martins), except the parts listed in section 2.

This file covers REG-Station as REG-Linux ships it, in REG-Linux images
(as `/usr/share/regstation/LICENSE`) and in the release archives published
at https://github.com/REG-Linux/REG-Station-binaries. It contains parts
under different licences. They are listed below.

## 1. Proprietary components

- `/usr/bin/regstation` (REG-Station, the REG-Linux frontend)
- its translations, `/usr/share/locale/*/LC_MESSAGES/regstation.mo`
- its data files under `/usr/share/regstation/`, except those listed in
  section 2

REG-Station is proprietary. Its source code is not published.

You may:

- install and use it on a device running REG-Linux;
- redistribute it unmodified, either as part of an official or unmodified
  REG-Linux image or inside the archive it shipped in, provided this file
  goes with it.

You may not:

- distribute modified copies;
- sell it on its own;
- use it outside REG-Linux.

This licence does not take away any right you have by law. That includes
the right to observe, study and test how a program works, and to
decompile it for interoperability, under EU Directive 2009/24/EC
(Articles 5(3), 6) and the UK CDPA 1988 (ss. 50B, 50BA). It also includes
the right to modify and reverse engineer it in order to debug changes you
make to the LGPL libraries it links to (FFmpeg, glibc, libudev), as
LGPL-2.1 section 6 requires.

## 2. Open-source components

REG-Station includes open-source code compiled into the binary
(EmulationStation and batocera-emulationstation, rcheevos, GLM, libspng,
stb, RapidJSON, glslang, SPIRV-Cross, libyuv, FlatBuffers, libra and
others), and installs fonts under their own licences (Apache-2.0,
SIL OFL 1.1, Ubuntu Font Licence).

Their copyright notices and licence texts are in
`/usr/share/regstation/THIRD_PARTY_LICENSES`, which ships with every
copy. Each of these components is under its own licence. Nothing in
section 1 restricts them.

The start-up scripts and compositor configuration installed with it
(`/etc/init.d/S31regstation`, `/usr/bin/regstation-standalone`,
`/etc/profile.d/04-sway.sh`, `/etc/sway/`, `/etc/xdg/weston/`,
`/usr/bin/weston-launch`) come from REG-Linux, under REG-Linux's licence.

The libraries REG-Station links to dynamically (SDL3, FFmpeg, FreeType,
libcurl and others) are not part of REG-Station. They are part of
REG-Linux, whose source and licence information are published at
https://github.com/REG-Linux/REG-Linux.

## 3. No warranty

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
