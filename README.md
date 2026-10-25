# Spectral Paint — Kisatchie Audio

Windows x64 standalone audio editor and ARA-enabled VST3.

## Download Windows Application + VST3

Open [the latest release](https://github.com/Quiescent18/spectral-paint-downloads/releases/latest) and download **SpectralPaint-1.0.3-Windows-App-and-VST3-x64.zip** under **Assets**.

This ZIP contains **Spectral Paint.exe** (the Windows standalone application), the complete **Spectral Paint.vst3** plug-in bundle, the illustrated user manual, shortcut guide, demo audio, installation notes and license notices. Use this Windows package to install the software. GitHub's separate **Source code** archives contain repository files.

Extract the whole ZIP before use. Close your DAW before replacing the complete VST3 bundle. For standalone use, launch **Spectral Paint.exe** and select your audio device. For plug-in editing, install the bundle in a scanned VST3 folder and enable ARA source access in an ARA-capable DAW.

## Manual and checksums

The release also includes **SpectralPaint-1.0.3-Users-Manual.pdf**, **WHATS-NEW-1.0.3.txt** and **SHA256SUMS.txt**. Manual page 7 explains selection grouping; page 12 lists keyboard and mouse shortcuts.

## New in 1.0.3

Hold **Alt and left-drag** in either visualizer to toggle existing areas in the linked group. Each box adds ungrouped areas, removes already-grouped areas, and preserves untouched members. The waveform uses time overlap; the spectrum uses time/frequency overlap. Empty boxes preserve the group, and Hand mode stays active for continued panning.

Switch to Eyedropper to resize grouped edges. Escape or Unlink exits group mode; Delete discards grouped highlight rectangles. Remove, Reduce, Crop and Solo use all highlighted spectral content.

## Features

- Color and Frequency matching across the source audio.
- Colored waveform and frequency spectrum with editable time/frequency selections.
- Custom areas and linked selection editing.
- Remove, Reduce and Crop spectral audio edits.
- Solo audition, original comparison, Undo/Redo, transport and looping.
- Timeline zoom, pan and playhead following.
- Save edit decisions and export processed WAV audio.

Audio timing and duration are preserved. Color matching is not instrument recognition or guaranteed source separation. The release targets Windows x64 and existing source audio; a host must support ARA source access for plug-in editing.

## Download verification

Compare downloads against **SHA256SUMS.txt**. The binaries are unsigned; Kisatchie Audio file metadata is not a digital signing certificate. Retain all supplied license notices. Third-party components retain their own license terms.
