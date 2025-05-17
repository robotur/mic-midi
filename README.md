# 🎹 Mic-to-Piano Note & Piano Roll Visualizer

A sleek real-time web app that listens to your microphone 🎤, detects musical notes 🎶, logs them in a terminal-like display 💻, and visualizes them on a piano roll 🟩 — all in your browser.

---

## ✨ Features

- **🎤 Live Microphone Input** – Captures your pitch in real time.
- **📡 Pitch Detection** – Converts audio frequencies to MIDI notes.
- **🧠 Note Stabilization** – Uses median filtering for consistent output.
- **🎨 Terminal Log** – Color-coded terminal logs with repeat counts and durations.
- **🎹 Piano Roll Visualization** – Scrollable, time-aligned piano roll.
- **⚙️ Calibration Slider** – Adjust detected pitch by ±4 octaves.
- **⏱️ Adjustable BPM** – Control the tempo of the piano roll display.
- **🧼 Clear Button** – Reset the logs and visuals with a click.
- **🖤 Dark Mode Design** – Stylish and easy on the eyes.
- **🚀 100% Client-side** – No server, no dependencies, just open and go!

---

## 🔧 How It Works

1. **Start Mic**: Click the **Start** button to allow microphone access.
2. **Detect Notes**: The app listens for a pitch, detects the closest MIDI note, and displays it.
3. **Log Notes**: When the same note is heard multiple times, it's logged in a terminal view.
4. **Visualize**: Sustained notes are added to a scrolling piano roll with timing based on your BPM.
5. **Adjust**:
   - Use the **Calibration Slider** to fix pitch shifts.
   - Set your **desired BPM** to match your tempo.

---

## 🖼️ Screenshots

> _[Insert animated GIF or screenshot here if desired]_

---

## 🛠️ Tech Stack

- **HTML5**
- **Vanilla JavaScript**
- **Web Audio API**
- **CSS3**

---

## 🧪 Local Usage

1. Clone or download this repository.
2. Open `index.html` in your favorite browser.
3. Allow microphone access.
4. Start singing, humming, or playing an instrument.

> 💡 Works best with clean, monophonic audio (single note at a time).

---

## 🧰 Optional Improvements

- MIDI export
- Note velocity/intensity mapping
- Instrument selector
- Save/load sessions
- Mobile optimization

---

## 🧑‍💻 Author

**Your Name**  
> Frontend experimenter, audio geek, and web wizard.

---

## 📄 License

MIT License – Feel free to use, remix, and share.

---

## 📣 Acknowledgments

- Inspired by [Chris Wilson's PitchDetect](https://webaudiodemos.appspot.com/pitchdetect/)
- Thanks to MDN & Stack Overflow for docs and support

---

## 🚀 Live Demo (Optional)

If you deploy it online (e.g., GitHub Pages, Netlify), link it here:

[🔗 Click here to try it live](https://your-demo-link.com)

---
