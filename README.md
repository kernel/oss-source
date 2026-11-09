# oss-source

Source for the LGPL-licensed components that Kernel's browser images modify.

Kernel's browser images ship a Chromium build. A small number of files in that
build are LGPL-licensed, and some of them carry Kernel changes:

| Path | License |
|---|---|
| `third_party/blink/renderer/core/frame/navigator.cc` | LGPL-2.0-or-later |
| `third_party/blink/renderer/core/page/page.cc` | LGPL-2.0-or-later |
| `third_party/ffmpeg/**` | LGPL-2.1-or-later |

This repository publishes those files as they appear in the shipping build, so
that recipients of the images can obtain the corresponding source of the
modified library files.

## Contents

- `lgpl/source/` — complete text of each modified file, at its path within the
  Chromium tree.
- `lgpl/patches/` — the changes applied to those files.
- `pins.md` — the upstream revisions these files are based on.
- `LICENSES/` — full license texts.

## Using these files

Every path under `lgpl/source/` matches the same path in Chromium at the
revisions in `pins.md`. The files are complete, and the patches are included so
the change can be reviewed against upstream.

## Not covered here

Files in the images that are not LGPL — BSD-licensed Chromium code and
third-party components under their own licenses — are not reproduced here.
Their source is public at the pins in `pins.md`, and their licenses are
recorded in the third-party notices file shipped in the image at
`/usr/share/doc/kernel/THIRD-PARTY-NOTICES.txt`.

## Contact

legal@kernel.sh
