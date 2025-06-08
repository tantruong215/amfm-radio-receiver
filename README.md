# AM/FM Radio Receiver

An analog front-end radio circuit with digital demodulation via software-defined radio (SDR), targeting 540–1600 kHz (AM) and 88–108 MHz (FM).

---

### ⚙️ Hardware Design
- RF tuner module (Si4703 or TEA5767)
- SDR dongle (RTL-SDR) for FM capture
- Arduino or ESP32 for I²C control

---

### 🧠 Control/Software Features
- Band selection + tuning via rotary encoder
- Basic DSP demodulation of FM signal
- Audio output via DAC and speaker amp

---

### 📊 Results (Expected)
- Tune FM/AM stations in real-time
- SNR > 25 dB in strong-signal area
- Frequency drift < 100 Hz/hr

---

### 🧰 Tools Used
- GNU Radio
- Python (SDR DSP)
- KiCad, Arduino IDE

---

### 🚧 Project Status
🛠️ Status: In Progress – Summer 2025
