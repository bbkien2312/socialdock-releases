# Third-party components

SOCIALdock invokes the following independent runtime components. Their original licenses remain applicable; the SOCIALdock source repository is private.

- Electron: MIT and Chromium/third-party notices bundled by electron-builder (LICENSE.electron.txt, LICENSES.chromium.html).
- CPython standalone: Python Software Foundation license and bundled dependency licenses. Distribution: https://github.com/astral-sh/python-build-standalone, pinned release/checksums in scripts/runtime-lock.json.
- yt-dlp: https://github.com/yt-dlp/yt-dlp (Unlicense for project code; dependencies have their own licenses).
- ijson: https://github.com/ICRAR/ijson (BSD-3-Clause).
- Beautiful Soup: https://www.crummy.com/software/BeautifulSoup/ (MIT).
- openpyxl: https://openpyxl.readthedocs.io/ (MIT).
- FFmpeg/ffprobe: separate executables distributed by ffmpeg-static / ffprobe-static. See runtime/licenses and binary build notices for exact versions, licenses and upstream source/build references. No FFmpeg library is linked into SOCIALdock code.

Public binary distribution must retain all applicable notices and provide corresponding upstream source/build materials where required. A checksum verifies file integrity; it is not a code signature or malware assessment.
