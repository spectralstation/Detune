# Detune

**A warm, vintage-styled wavetable synthesizer** by Spectral Station, for macOS and Windows.

Three wavetable oscillators with WAV import, two filters, four LFOs, a 16-slot mod matrix you patch with
real cables, and a full effects rack, all on a calm, Repro-inspired modular panel.

## Download

Get the latest installers from the **[Releases page](../../releases/latest)**:

| System | File | Formats |
|---|---|---|
| macOS 11+ (Apple Silicon & Intel) | `Detune-x.y.z-macOS.pkg` | VST3, Audio Unit |
| Windows 10/11 (64-bit) | `Detune-x.y.z-Windows-Setup.exe` | VST3 |

## Install

**macOS**
1. Open the `.pkg` and follow the steps (choose VST3 and/or Audio Unit).
2. Plug-ins go to `/Library/Audio/Plug-Ins/VST3` and `/Library/Audio/Plug-Ins/Components`.
3. If macOS says the installer "can't be opened", right-click it and choose **Open**, then **Open** again.

**Windows**
1. Run `Detune-x.y.z-Windows-Setup.exe`.
2. If Windows SmartScreen appears, click **More info**, then **Run anyway**.
3. Detune installs to `C:\Program Files\Common Files\VST3`.

Then rescan plug-ins in your DAW. In **FL Studio**: *Options > Manage plugins > Find plugins*, then find
**Detune** under *Generators*.

## Uninstall

- **macOS:** delete `Detune.vst3` and `Detune.component` from the folders above.
- **Windows:** *Settings > Apps > Detune > Uninstall*.

## Quick tips

- Drag knobs up/down; hold **Shift** for fine control; **double-click** to reset.
- Drag a cable from any **OUT** jack (LFO, ENV, macros, velocity...) onto a CV jack (WAVE, CUT, PITCH...)
  to modulate it. Scroll on a patched jack to change the amount, or drag the cable off to remove it.
- **import wav** on an oscillator loads your own wavetable (2048-sample frames).
- Presets: use the arrows at the top, or the **PRESETS** page in the SYSTEM section.

---
© Spectral Station. Detune is free to download; redistribution of the installers is not permitted.
