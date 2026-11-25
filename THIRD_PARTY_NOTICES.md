# Third-party distribution notice — UpScalImg

The root MIT LICENSE applies to the independently written Python glue,
documentation, and orchestration only. It does not relicense native binaries,
pretrained weights, models, libraries, or upstream code.

## Upscayl NCNN
- Backend source: https://github.com/upscayl/upscayl-ncnn
- License: GNU Affero General Public License 3.0 (AGPL-3.0).
- Bundled upstream license text: LICENSE_UPSCAYL.txt.
- Users must comply with upstream copyleft/attribution/source obligations.

## Upscayl image models
- Original authors and distribution: https://github.com/upscayl/upscayl
- Models ultramix-balanced-4x and ultrasharp-4x: Kim2091;
  attribution and noncommercial conditions apply; see
  https://github.com/upscayl/upscayl/issues/198 and
  https://creativecommons.org/licenses/by-nc-sa/4.0/
- Remacri model attribution and applicable noncommercial conditions also apply.
- Other included models are not automatically MIT licensed.
- Downstream users must review each model's license, particularly for
  commercial use and redistribution. A license from the Python project
  conveys no separate rights in model weights.

## FFmpeg (separate release)
- Project: https://ffmpeg.org
- Windows build origin: gyan.dev 2025-02-13, commit identifier 19a2d26177.
- Binary configured with --enable-gpl --enable-version3 and is GPLv3.
- https://www.gyan.dev/ffmpeg/builds/
- https://ffmpeg.org/legal.html
- https://github.com/FFmpeg/FFmpeg/tree/19a2d26177
- The corresponding complete GPL source and build scripts must remain
  available in accordance with their licenses; a build's license cannot be
  replaced with MIT. Do not assume an unmodified upstream reference alone
  satisfies every redistribution obligation.

## Runtime / platform
- Windows x64 assets, not Linux containers and not Mac binaries.
- GPU/Vulkan may not be available in ChatGPT Code Interpreter.
