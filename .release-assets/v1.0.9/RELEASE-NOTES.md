Download **SpectralPaint-1.0.9-Windows-App-and-VST3-x64.zip** under Assets for the Windows application and ARA-enabled VST3. The illustrated PDF manual is included in that ZIP and is also available separately below.

### Playback synchronization

- Playback Offset sits above Follow playhead and adjusts visual timing from −5000 to +5000 ms.
- New VST3 instances default to −500 ms; standalone defaults to 0 ms.
- Saved offsets are preserved. Set existing instances manually if needed; double-click resets the slider to zero.
- The display refreshes at 60 Hz. The offset changes the visual playheads and follow view; audio, selection coordinates, transport timing and exports remain unchanged.

### Selection and manual updates

- Invert Selection toggles between selected content and its complement.
- Frequency tolerance starts at Full spectrum for new sessions.
- Alt-left-drag in either visualizer adds/removes areas in the linked group while retaining Hand mode for panning.
- The illustrated manual covers calibration, shortcuts, drum-hit/cymbal-bleed color picking, and using Invert Selection to select outside the current selection.

### Install

Extract the entire Windows ZIP. Close the DAW before replacing the complete Spectral Paint.vst3 bundle in its VST3 scan folder. Reopen and verify 1.0.9 in the header. Existing VST3/ARA identifiers are preserved.

Both Windows test suites passed. Compare the ZIP, manual and What's new file against SHA256SUMS.txt. GitHub's Source code archives contain repository files; use the Windows ZIP above to install the software.
