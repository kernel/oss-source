# Upstream pins

The files under `lgpl/source/` correspond to these revisions.

| Component | Upstream | Revision |
|---|---|---|
| Chromium | `chromium/src` | tag `155.0.8059.84` |
| Chromium FFmpeg | `chromium/third_party/ffmpeg` | `ba5e7eaea38b6a54157870e0085b2e8c75aa6bcb` (the `ffmpeg_revision` in Chromium's `DEPS` at the above tag) |

Everything under `third_party/ffmpeg/` is additionally subject to the FFmpeg
project's own license (LGPL-2.1-or-later), regardless of the license header on
an individual file.

Both upstreams are publicly readable:

- https://chromium.googlesource.com/chromium/src/+/refs/tags/155.0.8059.84
- https://chromium.googlesource.com/chromium/third_party/ffmpeg/+/ba5e7eaea38b6a54157870e0085b2e8c75aa6bcb
