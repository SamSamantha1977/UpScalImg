# UpScalImg

Independent Python 3.11+ OpenAI Skill, by Sam.

The lightweight Skill ZIP is upscayl-image.zip.
Its unpacked source lives in upscayl-image/ (see SKILL.md and references/RUNTIME.md).
These are source distributions, not a promise of cloud GPU/installation access.

## Native dependencies (NOT YET PUBLISHED)
Native binaries and model weights are NOT in Git history or the light ZIP.
They must be published separately as release assets after complete licence review.
Each downloader refuses missing releases and checks SHA256 before extraction.

- ffmpeg-windows-x64-2025-02-13.zip; bytes=130661781; sha256=684fc9adee65ff4d0adaf5c269d00be490403e0e68938c6e0974fe31ae51a945
- upscayl-ncnn-windows-x64-1.1.0.zip; bytes=233905761; sha256=805274df20ef1855133df60431fe73eb3da70ee1e37bee12b4c69f763a56c748

Redistribution of upstream FFmpeg, Upscayl, Video2X, bundled DLLs, models and weight files
requires third-party licence verification and relevant notices/source obligations.
The project source licence is not assigned yet; no implied third-party licence granted.

## Validation
Tested on MINIPC Python 3.11.9; remote ChatGPT Skill runtime not yet validated.
No credential, Cassandre file, private user media, or Windows executable is tracked.

## GitHub release distribution

The heavy native dependencies are attached to the versioned GitHub Release in this repository only. Every download URL and SHA-256 in upscayl-image/references/dependencies.json must point to this repository. See the actual Release assets and documented supported platform matrix; Windows binaries do not run on Linux or macOS.
