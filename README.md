# Subtitle Edit

*the subtitle editor :)*

[![GitHub version](https://img.shields.io/github/release/SubtitleEdit/subtitleedit.svg)](https://github.com/SubtitleEdit/subtitleedit)
[![Build status](https://img.shields.io/appveyor/ci/SubtitleEdit/subtitleedit/main.svg)](https://ci.appveyor.com/project/SubtitleEdit/subtitleedit/branch/main)
![SE number of downloads](https://img.shields.io/github/downloads/subtitleedit/subtitleedit/latest/total.svg)
[![SE](https://img.shields.io/badge/SUBTITLE%20EDIT-join%20chat-blue.svg)](https://gitter.im/SubtitleEdit/subtitleedit "Subtitle Edit Gitter Chatroom")
[![download latest release](https://img.shields.io/badge/SUBTITLE%20EDIT-download-000F39.svg)](https://github.com/SubtitleEdit/subtitleedit/releases/latest) 

<https://www.nikse.dk/SubtitleEdit/Help>

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?hosted_button_id=4XEHVLANCQBCU)

# Subtitle Edit

## Overview

Subtitle Edit is a free (open source) editor for video subtitles - a subtitle editor :)

With SE you can easily adjust a subtitle if it is out of sync with the video in several different ways. You can also use SE for making new subtitles from scratch (do use the time-line/waveform/spectrogram) or translating subtitles. For a list of features see below or check out the [Subtitle Edit Help page](#). On my blog you can download the latest beta version and read about/discuss new features. Also, you can watch a few videos about installing and using Subtitle Edit.

A Subtitle Edit dll (LibSe.dll) is available for programmers (BSD New/Simplified license). Compile it from source code or use the NuGet package.

## Download

- Download latest version of Subtitle Edit
- Note: SE requires Microsoft .NET Framework Version 4.8
- Get the full C# source code - GPL or LGPL license
- Blu-ray sup reading code is under the Apache License and Matroska subtitle parsing uses zlib code with a BSD style license.

## Features

- Create/adjust/sync/translate subtitle lines
- Convert between SubRib, MicroDVD, Advanced Sub Station Alpha, Sub Station Alpha, D-Cinema, SAMI, youtube sbv, and many more (300+ different formats!)
- Cool audio visualizer control - can display wave form and/or spectrogram
- Video player uses mpv, DirectShow, or VLC media player
- Visually sync/adjust a subtitle (start/end position and speed)
- Audio to text (speech recognition) via Whisper or Vosk/Kaldi
- Auto Translation via Google translate
- Rip subtitles from a (decrypted) dvd
- Import and OCR VobSub sub/idx binary subtitles
- Import and OCR Blu-ray .sup files - bd sup reading is based on Java code from BDSup2Sub by 0xdeadbeef)
- Can open subtitles embedded inside Matroska files
- Can open subtitles (text, closed captions, VobSub) embedded inside mp4/mv4 files
- Can open/OCR XSub subtitles embedded inside divx/avi files
- Can open/OCR DVB and teletext subtitles embedded inside .ts/.m2ts (Transport Stream) files
- Can open/OCR Blu-ray subtitles embedded inside .m2ts (Transport Stream) files
- Can read and write both UTF-8 and other unicode files and ANSI (support for all languages/encodings on the pc!)
- Sync: Show texts earlier/later + point synchronization + synchronization via other subtitle
- Merge/split subtitles
- Adjust display time
- Fix common errors wizard
- Spell checking via Libre Office dictionaries (many dictionaries available)
- Remove text for hear impaired (HI)
- Renumbering
- Effects: Typewriter and karaoke
- History/undo manager (Undo=Ctrl+z, Redo=Ctrl+y)
- Compare subtitles
- Multiple search and replace
- Change casing using names dictionary
- Merge short lines/split long lines
- Export to PNG images (+bdn xml), Adobe Encore FAB image script, VobSub, Blu-ray sup, EBU stl, PAC, and plain text

## Languages

Subtitle Edit is available in 32+ languages. Read more about how to translate Subtitle Edit.

## Supported Formats

Subtitle Edit can read, write, and convert between more than 300 subtitle formats, like:

- SubRip (*.srt)
- ABC iView
- Adobe Encore
- Advanced Sub Station Alpha
- AQTitle
- Avid
- CapMaker Plus (*.cap, binary)
- Captionate
- Cavena890 (*.890, binary)
- Cheetah Caption (*.cap, binary)
- D-Cinema (Cinecanvas, both interop and smpte)
- Dvd Studio Pro
- Dvd Subtitle
- EBU Subtitling data exchange format (*.stl, binary)
- F4 (several variations)
- Flash xml
- Json (two variations, for use with JavaScript)
- MicroDvd
- MPlayer2
- OpenDvt
- PAC (*.pac, binary)
- Pinnacle Impression
- QuickTime Text
- RealTime Text
- Scenarist
- Sony DVD Architect
- Sub Station Alpha
- SubViewer 1.0
- SubViewer 2.0
- Sami (*.smi)
- Son (*.son, import only)
- Subtitle Editor Project
- Timed Text 1.0 (*.xml), also know as TTML or DFXP
- Timed Text Draft (*.xml)
- TMPlayer
- TTXT
- TurboTitle
- Ulead Subtitle Format
- Ultech (*.cap, binary, only read)
- UTX
- WebVTT
- YouTube Annotations
- YouTube Sbv
- Zero G
- Xml
- Csv
- VobSub (*.sub/*.idx, binary - can also be read from Matroska/mp4 files)
- DVD Vob (*.vob, binary, read only)
- Blu-ray sup (*.sup, binary, can also be read from Matroska files)
- Bdn xml (*.xml + png images, read+write)
- Transport Stream subtitles (*.ts)
- + several formats of unknown name

## Batch Conversion

Subtitle Edit can also convert subtitles via command line or the batch-convert-ui.
