---
title: Classic Music Maker support
permalink: /classic-music-maker/
---
# Classic Music Maker support

_Last updated: November 25, 2026_

Classic Music Maker is published by Deck-Of-Jacks.

**Found a problem?** [Report an issue](https://github.com/IanD-Bot/support/issues/new?template=classic-music-maker.yml)

## About this app

Classic Music Maker is a beginner-friendly Windows music studio built around a multi-track timeline, built-in synth instruments, a piano roll, a drum grid, and multi-layer audio recording. Sound controls include **(i)** hover help in plain words with concrete examples, named presets, and built-in sample songs with a written step-by-step walkthrough.

## Requirements

Windows 10 version 2004 (build 19041) or later, 64-bit. A microphone or USB audio interface is optional and only needed if you want to record vocals or real instruments.

## Install and launch

Install the app from the Microsoft Store, then open **Classic Music Maker** from the Start menu.

## Making a song

- **Timeline and tracks.** New projects start with Drums, Bass, Keys, and Melody tracks so you can place notes right away. Click a track to open its drum grid or piano roll.
- **Sound controls and presets.** Adjust per-track or per-clip Volume, Pan, Pitch, Tone, and Frequency, or pick a named preset. Hover or click any **(i)** mark for an everyday explanation and example.
- **Walkthrough.** Open **View > Walkthrough** or **File > Sample songs** to listen to built-in examples or start a new song and follow the written steps.

## Recording layers

- Click **+ Audio** to add and arm an audio track (or click **R** on a track header).
- Pick your microphone or USB audio interface in the **Input** list, optionally turn on **Count-in**, and press **Record** to capture a layer while your song plays.
- Microphone access starts only when you press **Record**. Recordings stay on your PC inside your `.classicmusic` project file.

## Export

Use **File > Export** to save:

- **Project file (`.classicmusic`)** — keeps tracks, notes, mix controls, and recorded audio layers together.
- **WAV (`.wav`)** — uncompressed 44.1 kHz 16-bit stereo mix.
- **MP3 or M4A (`.mp3` / `.m4a`)** — compressed stereo mix through Windows Media Foundation (falls back to M4A/AAC if your PC does not have an MP3 encoder).
- **MIDI (`.mid`)** — Standard MIDI file of your note tracks (recorded audio layers are not included in MIDI).

## Appearance

Open **View > Theme** to choose **Match Windows** (default), **Light**, or **Dark**. Windows High Contrast themes always take priority.

## Common questions

- **Does Classic Music Maker send my recordings or projects anywhere?** No. All projects, recordings, and exports stay on your PC.
- **Why did compressed export save `.m4a` instead of `.mp3`?** Some Windows setups do not include an MP3 Media Foundation encoder, so Classic Music Maker uses M4A (AAC) instead and tells you in the dialog.
- **Why aren't my vocal takes in the MIDI file?** Standard MIDI only stores notes, tempo, and instrument programs, not recorded audio waveforms. Export WAV, MP3, or M4A to include recorded layers.

## Uninstall

To remove the app, uninstall **Classic Music Maker** from **Settings > Apps**. Your saved `.classicmusic` project files and exported songs stay in the folders where you saved them.

## Report a problem

[Report an issue](https://github.com/IanD-Bot/support/issues/new?template=classic-music-maker.yml) on GitHub. Issues are public. Please don't include personal information in the issue.

## Privacy

See the [Classic Music Maker privacy policy](https://privacy.deckofjacks.com/classic-music-maker).
