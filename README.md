# Spectral Paint — Kisatchie Audio

Windows x64 standalone audio editor and ARA-enabled VST3.

![Spectral Paint cymbal bleed example from the user manual](assets/Cymbal-Bleed-Noise-Threshold.png)

## Download — Latest Windows x64 build (November 15, 2026)

**[Download Spectral Paint 1.0.9 — Linked Resize Update](https://github.com/Quiescent18/spectral-paint-downloads/releases/download/v1.0.9-linked-resize/SpectralPaint-1.0.9-Linked-Resize-Windows-x64.zip)**

This is the **latest published Windows build**, including the linked-selection resizing fix. The application and VST3 continue to identify as **version 1.0.9**; this is a maintenance update, not a new plug-in identity.

The ZIP contains **only four top-level items**:

- `Spectral Paint.exe` — Windows x64 standalone audio editor.
- `Spectral Paint.vst3/` — complete ARA-enabled VST3 plug-in folder.
- `SpectralPaint-1.0.9-Users-Manual.pdf` — illustrated user manual.
- `README.txt` — installation instructions and license notices.

### Install

Extract the ZIP completely. For the VST3, close REAPER or your DAW, then copy the **entire `Spectral Paint.vst3` folder** to `C:\\Program Files\\Common Files\\VST3` (administrator permission may be required). Restart the DAW, rescan plug-ins if needed, and enable ARA source access. For standalone use, open `Spectral Paint.exe` and select your audio device.

### Linked-selection resizing fix

- Shrinking larger linked time/frequency selections is no longer limited by the group's shortest or narrowest region.
- Regions that shrink to zero duration or frequency width are removed when the mouse is released.
- Remaining linked selections keep resizing, and the gesture remains a single Undo step.
- Moving linked regions still preserves their relative positions.

The [Windows build and tests](https://github.com/Quiescent18/spectral-paint/actions/runs/43737739650) completed successfully.

### Verify the updated download

**SHA-256 (latest ZIP):** `d0113e065b2196069032872a1b12d3e8e0c1cb10caacd56ffb0f5a4c7862e366`

On Windows, run `Get-FileHash -Algorithm SHA256 .\\SpectralPaint-1.0.9-Linked-Resize-Windows-x64.zip` in PowerShell to compare the downloaded file's hash against the value above. Binaries are unsigned; Kisatchie Audio file metadata is not a digital code-signing certificate.

## Manual and previous release

The current ZIP includes the illustrated manual. You can also [view the 1.0.9 manual separately](https://github.com/Quiescent18/spectral-paint-downloads/releases/download/v1.0.9/SpectralPaint-1.0.9-Users-Manual.pdf). Page 6 explains linked selections, page 7 Invert Selection, page 9 visual synchronization, page 12 the cymbal-bleed example, and page 14 shortcuts. The manual predates the linked-resize maintenance fix described above.

[Previous Spectral Paint 1.0.9 release (November 1, 2026)](https://github.com/Quiescent18/spectral-paint-downloads/releases/tag/v1.0.9) — retained for reference. Its ZIP predates the linked-selection resizing fix. Older release checksums and What's New documents apply **only** to that previous release.

## Features and playback synchronization

**Playback Offset** above Follow playhead lets you synchronize the visual playhead with the sound: new VST3 instances default to **−500 ms**, while standalone defaults to **0 ms**. Saved offsets are preserved; adjustment ranges from −5000 ms to +5000 ms, and double-click resets the slider to zero. This affects the visual display only, not audio timing or exports. Other 1.0.9 features include Invert Selection, Full Spectrum initial frequency tolerance, 60 Hz playhead display, and the illustrated manual.

## Features

- Color and Frequency matching across source audio.
- Colored waveform and frequency spectrum with editable time/frequency areas.
- Select All, Invert Selection, custom areas and linked selection editing.
- Alt-left-drag in either visualizer toggles touched areas in the linked group; Hand mode remains active for panning.
- Remove, Reduce and Crop spectral audio edits.
- Solo audition, original comparison, Undo/Redo, transport and looping.
- Timeline zoom, pan, playhead following and adjustable visual Playback Offset.
- Save edit decisions and export processed WAV audio.

Audio timing and duration are preserved. Color matching is not instrument recognition or guaranteed source separation. The software edits existing source audio; a host must support ARA source access for plug-in editing.

## Licensing and distribution

The ZIP's README includes installation instructions and licensing notices. Third-party components retain their own terms. Source-code archives on GitHub are not the Windows installer ZIP.
