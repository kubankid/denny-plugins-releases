# Denny Plugins - downloads

Built plugins only (no source). Pick your platform:

- **Windows:** [Denny-Plugins-Windows.zip](https://github.com/kubankid/denny-plugins-releases/releases/latest/download/Denny-Plugins-Windows.zip)
  - unzip, double-click `install-windows.bat` (asks for admin, copies into `C:\Program Files\Common Files\VST3`)
  - FL Studio: Options > Manage plugins > tick "Rescan previously verified plugins" > Start scan
- **macOS:** [Denny-Plugins-macOS.zip](https://github.com/kubankid/denny-plugins-releases/releases/latest/download/Denny-Plugins-macOS.zip)
  - `.vst3` -> `~/Library/Audio/Plug-Ins/VST3/`, `.component` -> `~/Library/Audio/Plug-Ins/Components/`, then rescan in FL

| Plugin | Type in FL | What it does |
|---|---|---|
| **WXRST** | Generator | Lo-fi / PS2-era / OVO pads, keys, 808s + chord engine + sampler with chops |
| **WXRST XTRACT** | Effect | Split any sample into stems, turn stems into MIDI, send them into WXRST |
| **Denny Key Finder** | Effect | Key, Camelot code and BPM of whatever plays through it |

From these versions on, the plugins update themselves: an UPDATE banner shows up in the plugin when a newer build is here.
`version.json` in this repo is what they read.
