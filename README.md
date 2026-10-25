# Spectral Paint — Kisatchie Audio

Windows x64 standalone audio editor and ARA-enabled VST3.

## Download

Open [Releases](https://github.com/Quiescent18/spectral-paint-downloads/releases) and download **SpectralPaint-1.0.3-Windows-x64.zip** from the release's **Assets** section. The ZIP includes the EXE, complete VST3 bundle, approved illustrated user manual, demo audio, installation notes and license notices. A separate PDF manual, the updated **WHATS-NEW-1.0.3.txt** shortcut guide and SHA-256 checksums are also attached to the release.

Extract the whole ZIP before use. Close your DAW before replacing the complete VST3 bundle. For standalone use, launch **Spectral Paint.exe** and select your audio device. For plug-in use, install the bundle in a scanned VST3 folder and enable ARA source access in an ARA-capable DAW. Follow the manual for details and supported limits.

## New in 1.0.3

Hold **Alt and left-drag** in either visualizer to toggle existing areas in the linked group. Each box adds ungrouped areas, removes already-grouped areas, and preserves untouched members. The waveform uses time overlap; the spectrum uses time/frequency overlap. Empty boxes preserve the group, and Hand mode stays active so you can continue panning.

Switch to Eyedropper to resize grouped edges. Escape or Unlink exits group mode; Delete discards grouped highlight rectangles. Remove, Reduce, Crop and Solo continue to use all highlighted spectral content. Read the shortcut guide for details.

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

This repository hosts public downloads and documentation.
