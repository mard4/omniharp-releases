<div align="center">

<img src="art/banner.svg" width="100%" alt="OmniHarp: a cream instrument panel with rows of pastel chord buttons and a twelve-string harp. It plays C, A minor, F and G, strumming the strings on each chord.">

### Press a chord. Run a finger across the strings.
An Omnichord-inspired instrument for your DAW

<p align="center">
  <a href="https://omniharp.com"><img src="https://img.shields.io/badge/Website-Omniharp-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="🌐 Website" /></a> 
  <a href="https://martidan.gumroad.com/l/omniharp?wanted=true"><img src="https://img.shields.io/badge/Support-Gumroad-ff90e8?style=for-the-badge&logo=gumroad&logoColor=black" alt="Support on Gumroad" /></a>
</p>


<br>

<a href="https://martidan.gumroad.com/l/omniharp"><img src="art/download-macos.svg" width="400" alt="Download for macOS: VST3, AU and Standalone, macOS 12 or later"></a>
<a href="https://martidan.gumroad.com/l/omniharp"><img src="art/download-windows.svg" width="400" alt="Download for Windows: VST3 and Standalone, 64-bit"></a>

<img src="art/divider.svg" width="220" alt="">

</div>

## What's inside

<table>
<tr>
<td width="50%" valign="top">
  
**27 chords, and a few more**<br>
Major, minor and 7th in nine keys. Hold two buttons in a column for the OM-84's maj7, m7 and dim.

</td>
<td width="50%" valign="top">

**A harp that follows you**<br>
Twelve strings, always in the key of your chord. Click one, drag across them to strum, or play them over MIDI.

</td>
</tr>
<tr>
<td valign="top">

**Six rhythms**<br>
Rock, Waltz, Slow Rock, Latin, Fox Trot and Swing. Start them with your next chord, or lock them to your song's tempo with BPM.

</td>
<td valign="top">

**Layered chords**<br>
Hold up to four chords from different columns at once, and the strings play all of their notes.

</td>
</tr>
<tr>
<td valign="top">

**Chord Computer**<br>
Record a progression, then step through it one chord at a time with a single key. It's saved with your project.

</td>
<td valign="top">

**Wobbly tape, if you want it**<br>
Chorus and vibrato with Rate, Depth, Mix and Width, plus Sustain and a ±12 semitone Transpose.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**Drag your takes straight into the DAW**<br>
OmniHarp quietly records everything you play. Drag the MIDI TAKE tile onto a track for a MIDI clip, or DRUM TAKE for the rhythm as audio. Every take is also saved in `Music/OmniHarp Takes`.

</td>
</tr>
</table>

<img src="art/omniharp.png" width="100%" alt="The OmniHarp plugin window: power, sound and chorus controls, six rhythms, 27 chord buttons, a Chord Computer, take tiles and a twelve-string harp.">

<div align="center"><img src="art/divider.svg" width="220" alt=""></div>

## Install

<details open>
<summary><b>macOS</b> </summary>
<br>

1. Unzip the download.
2. Copy `OmniHarp.vst3` to `~/Library/Audio/Plug-Ins/VST3/`.
3. Copy `OmniHarp.component` to `~/Library/Audio/Plug-Ins/Components/` for Logic and GarageBand.
4. Rescan plugins in your DAW and find it under **Personal › OmniHarp**, on an instrument or MIDI track.

`OmniHarp.app` runs without a DAW. Drag it to Applications.

</details>

<details open>
<summary><b>Windows</b></summary>
<br>

1. Unzip the download.
2. Copy the `OmniHarp.vst3` folder to `C:\Program Files\Common Files\VST3\`.
3. Rescan plugins in your DAW and find it under **Personal › OmniHarp**, on an instrument or MIDI track.

`OmniHarp.exe` runs without a DAW. The Windows build isn't code-signed, so SmartScreen may warn you: choose **More info › Run anyway**.

</details>

<div align="center"><img src="art/divider.svg" width="220" alt=""></div>

## Play it

<div align="center">
<img src="art/keys.svg" width="100%" alt="Computer keyboard map. Major chords: Q W E R T Y U I O. Minor chords: A S D F G H J K L. 7th chords: Z X C V B N M comma period, for the keys E flat, B flat, F, C, G, D, A, E and B. Strumplate: 1 2 3 4 5 6 7 8 9 0 minus equals.">
</div>

In a DAW, your typing usually goes to the DAW instead of the plugin, so use the mouse or MIDI there. Click the **OH** crown on the harp for the full guide.

### MIDI

| Notes | Plays |
|:---|:---|
| 48–59 | Major chords, by root |
| 36–47 | Minor chords, by root |
| 24–35 | 7th chords, by root |
| 60–71 | Strumplate, string 1 to 12 |
| 72 | Chord Computer step |
| Channel 2, any note | Harp: the chord's closest note |
| Channel 10, 36–51 | 16 chord pads |
| CC 70–77 | Knobs |

Some DAWs, Ableton Live among them, send every note on channel 1, so the two channel-based rows won't work there.

<div align="center"><img src="art/divider.svg" width="220" alt=""></div>

## Good to know

- **Formats:** VST3 and Standalone on both systems, plus Audio Unit on macOS.
- **Local control port:** while running, OmniHarp listens on a port between 9890 and 9899, on your own computer only, for its optional MCP control.
- **Problems:** [open an issue](https://github.com/mard4/omniharp-releases/issues) with your system and DAW.
<sub>Runs on Apple Silicon and Intel Macs. <a href="https://github.com/mard4/omniharp-releases/releases">All releases</a></sub>

## Credits

OmniHarp is an independent fan project, not affiliated with or endorsed by Suzuki. Built with [JUCE](https://juce.com/).
