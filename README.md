# 🎹 Simple Web Piano App

This is a lightweight piano app built with HTML, CSS, and JavaScript that features both **white** and **black keys**. Users can play musical notes using their mouse or touchscreen. Each key plays a sine wave generated in real time via the Web Audio API.

---

## 🧠 How It Works

- **White and black keys** are laid out and styled to visually represent a keyboard.
- Each key is assigned a musical note frequency via the `data-note` attribute.
- When a key is clicked, the browser generates and plays a tone using the Web Audio API oscillator.

---

## 🚀 Features

- Responsive layout using Flexbox
- Accurate note frequencies for white and black keys (C–B, with sharps)
- Clean and minimal UI
- Pure front-end: no libraries or dependencies required

---

## 💻 Usage

1. Open `index.html` in your browser.
2. Click any key to hear the corresponding note.
3. No installation or compilation needed.

---

## 📁 File Structure

. ├── index.html       # Main app file ├── README.md 

---

## 🎯 Customization Ideas

- Add keyboard key bindings (e.g. A–L keys to play notes)
- Switch between wave types (`sine`, `square`, `triangle`, `sawtooth`)
- Add sustain toggle or volume control
- Enable soundfonts or MIDI support for richer tones

---

## 📜 License

Open-source and free to modify for educational or personal use.

Enjoy making music in the browser!
