# Mic to Piano Note & Piano Roll Visualizer

A real-time browser-based tool that captures microphone input, detects musical notes, and displays them in both a terminal-style log and a visual piano roll. Built entirely with HTML, CSS, and JavaScript—no frameworks or external dependencies required.

---

## Features

- **Live Microphone Input** – Captures audio in real time using the Web Audio API.
- **Pitch Detection** – Analyzes incoming sound and converts frequencies to MIDI notes.
- **Note Stability Filtering** – Uses repeat-count logic to stabilize pitch detection.
- **Terminal-Style Logging** – Displays detected notes with timing and frequency of appearance.
- **Piano Roll Visualization** – Renders note blocks on a scrollable grid aligned to time and pitch.
- **Calibration Control** – Shift detected notes up or down in semitones for pitch correction.
- **Tempo Adjustment** – Configure beats per minute to control piano roll timing.
- **Client-Side Only** – No servers or installations; works entirely in the browser.

---

## How to Use

1. Navigate to `mic-midi.xyz` through your browser (not available as of upload)
2. Click the **Start** button to enable microphone access.
3. Hum, sing, or play a single note on an instrument.
4. Notes will appear in the log view and on the piano roll in real time.
5. Use the calibration slider to adjust tuning.
6. Set your preferred BPM to control the timing scale of the piano roll.

---

## Technical Details

- **Languages**: HTML, CSS, JavaScript
- **APIs Used**: Web Audio API (with time-domain analysis and autocorrelation)
- **Pitch to MIDI Mapping**: `freqToMidi(frequency) => MIDI`, followed by note labeling
- **Note Filtering**: Simple majority filter over recent history (mode selection)
- **Visual Components**:
  - Terminal-style console with color-coded feedback
  - Scrollable, beat-aligned piano roll visualization
  - MIDI note range: C1 (24) to C7 (96)

---

## Development Setup

No build tools or installations are required. Simply:

```bash
git clone https://github.com/robotur/mic-midi.git
cd mic-midi
open index.html
