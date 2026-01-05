# 🎚️ Multi-Band Audio Equalizer

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![GUI](https://img.shields.io/badge/GUI-PyQt5-green)
![Topic](https://img.shields.io/badge/Topic-Digital%20Signal%20Processing-purple)
![Library](https://img.shields.io/badge/Audio-SciPy%20%7C%20NumPy-orange)

## 📌 Project Overview
**Sound Equalizer** is a desktop application for real-time audio equalization and signal analysis. It allows users to manipulate audio frequencies across **10 different bands**, visualize changes via dynamic graphs, and compare the original signal with the equalized output.

The tool demonstrates practical applications of **Digital Signal Processing (DSP)** concepts such as Fourier Transform (FFT), Spectrograms, and Signal Reconstruction using Python.

## ⚙️ Key Features
* **10-Band Equalizer:** Precise control over frequency bands (Bass, Mid, Treble) using sliders.
* **Visual Analysis:**
    * **Waveform View:** Time-domain representation of the signal.
    * **Spectrogram:** Frequency-domain intensity map.
    * **Cinegram:** Visualizing signal differences.
* **Signal Comparison:** Toggle between original and modified audio to hear/see the difference instantly.
* **File Support:** Load and process standard WAV files.

## 🛠️ Tech Stack
* **Language:** Python.
* **GUI Framework:** PyQt5 (Qt Designer).
* **Signal Processing:** SciPy, NumPy.
* **Visualization:** Matplotlib / PyQtGraph.

## 🚀 How to Run
1.  **Clone the repository**

2.  **Install Dependencies**

3.  **Run the Application:**
    ```bash
    python src/main.py
    ```