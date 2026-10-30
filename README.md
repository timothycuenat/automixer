<div align="center">

<img src="assets/icon.svg" alt="" width="72">

# TIM Automixer

### Drop it on every mic. Press play. Done.

Clean, natural dialogue from every lavalier — automatically.<br>
No gates to tune, no volume rides, no comb filtering.

<br>

<a href="https://github.com/timothycuenat/automixer/releases/latest/download/TIM-Automixer-macOS.pkg"><img src="https://img.shields.io/badge/Download_for_macOS-4fc3e8?style=for-the-badge&logo=apple&logoColor=121417&labelColor=4fc3e8" alt="Download for macOS" height="44"></a>
&nbsp;
<a href="https://github.com/timothycuenat/automixer/releases/latest/download/TIM-Automixer-Windows-Setup.exe"><img src="https://img.shields.io/badge/Download_for_Windows-4fc3e8?style=for-the-badge&logo=windows&logoColor=121417&labelColor=4fc3e8" alt="Download for Windows" height="44"></a>

<sub>AU &amp; VST3 on macOS 11+ (Apple Silicon &amp; Intel) · VST3 on Windows 10/11 (64-bit)</sub>

**[Website](https://timothycuenat.github.io/automixer/)** &nbsp;·&nbsp; **[All releases](https://github.com/timothycuenat/automixer/releases)**

<br>

<img src="assets/screenshot.png" alt="TIM Automixer plugin window: gain history, one strip per microphone and group settings" width="760">

</div>

<br>

## As simple as it gets

<img src="assets/three-steps.svg" alt="1. Drop TIM Automixer on every mic track. 2. Press play: the mics link automatically. 3. Clean dialogue: the right mic is always open." width="100%">

No routing and no sidechain: every instance finds the others on its own.

## Why it works

Every voice also reaches the other mics, later and quieter. That bleed makes dialogue hollow and phasey, and a gate can't fix it: a voice moves over about 30 dB, while bleed sits only 10–20 dB below it.

TIM Automixer compares the mics with each other, the way your eyes do on the waveforms.

<img src="assets/how-it-works.svg" alt="Each mic is compared with the others: the speaker stays open and the other mics are turned down by their level difference." width="100%">

## What you get

| | |
|---|---|
| **Gain sharing** | The speaker stays open. When two people talk at once, they share the gain and the overall level stays constant. |
| **Linked instances** | One instance per track, up to 8 mics per group and 16 groups per project. |
| **Voice-focused detection** | Listens to 150 Hz – 5 kHz and learns each mic's room noise. |
| **Lookahead** | Opens the mic just before the first word. Latency is reported to your host. |
| **Natural sound** | Smoothing keeps voices steady, and Hold last mic keeps the room tone during pauses. |
| **Depth & Contrast** | Stay gentle and airy, or push bleed further down in difficult rooms. |
| **Live view** | Gain history, meters and a *Speaking* light for each mic. |
| **Presets** | 7 factory presets, plus your own. |

## Install

1. **Download** the installer for your system with the buttons above.
2. **Run it**, then restart your audio or video software.
3. **Search for "TIM"** in the effects list and put the plugin first on every mic track.

Use the same format (AU or VST3) on every track of a conversation: AU and VST3 instances can't link with each other.

<details>
<summary><strong>macOS says the installer can't be opened</strong></summary>
<br>

Right-click the file, then choose **Open** and **Open** again.

If your software doesn't list the plugin after installing, paste this in the Terminal and restart the software:

```bash
sudo xattr -dr com.apple.quarantine "/Library/Audio/Plug-Ins/Components/TIM Automixer.component" "/Library/Audio/Plug-Ins/VST3/TIM Automixer.vst3"
```
</details>

<details>
<summary><strong>Windows shows "Windows protected your PC"</strong></summary>
<br>

Click **More info**, then **Run anyway**. To uninstall the plugin, go to *Settings → Apps*.
</details>

<details>
<summary><strong>I'd rather install it by hand</strong></summary>
<br>

Download the [macOS .zip](https://github.com/timothycuenat/automixer/releases/latest/download/TIM-Automixer-macOS.zip) or the [Windows .zip](https://github.com/timothycuenat/automixer/releases/latest/download/TIM-Automixer-Windows-VST3.zip). Each one includes an `INSTALL.txt` file with the steps.
</details>

<br>

<div align="center">
<sub>Designed by <strong>Timothy Cuenat</strong>, sound engineer, photographer and filmmaker.<br>
Inspired by Dan Dugan's gain-sharing automixer. Built with <a href="https://juce.com">JUCE</a>.</sub>
</div>
