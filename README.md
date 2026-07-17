# 🎵 AI Music Generator using Genetic Algorithm

## 📌 Overview

This project implements an Artificial Intelligence-based Music Generator using a Genetic Algorithm (GA). The system evolves musical melodies over multiple generations by applying evolutionary operations such as selection, crossover, and mutation. It supports multiple music styles and generates MIDI and MP3 outputs automatically.

The project demonstrates how Genetic Algorithms can be applied to creative tasks such as music composition while maintaining musical structure through scale constraints.

---

## ✨ Features

- Genetic Algorithm based melody generation
- Multiple music styles
  - Soft
  - Classical
  - Rap
- Supports Major and Minor scales
- Configurable tempo
- Multi-run GA evaluation
- Automatic MIDI generation
- Automatic MP3 conversion
- PDF report generation
- Fitness score visualization

---

## 🛠 Technologies Used

- Python
- Genetic Algorithm
- NumPy
- Matplotlib
- Mido
- MIDIUtil
- Pydub
- FluidSynth
- Google Colab

---

## 📂 Repository Structure

```
AI-Music-Generator-Using-Genetic-Algorithm/
│
├── AI_Music_Generator_Using_Genetic_Algorithm.ipynb
├── README.md
├── requirements.txt
├── LICENSE
│
├── outputs/
│   ├── Soft_generated.mp3
│   ├── Classical_generated.mp3
│   ├── Rap_generated.mp3
│   ├── Soft_generated.mid
│   ├── Classical_generated.mid
│   ├── Rap_generated.mid
│   └── report.pdf
```

---

## ⚙️ Algorithm Workflow

1. Initialize a random melody population.
2. Evaluate each melody using a fitness function.
3. Select the fittest melodies.
4. Apply crossover to generate offspring.
5. Apply mutation to introduce diversity.
6. Repeat for multiple generations.
7. Generate the best melody.
8. Export MIDI, MP3, and PDF report.

---

## 📊 Sample Outputs

The repository includes sample generated music for:

- 🎵 Soft Style
- 🎼 Classical Style
- 🎤 Rap Style

Both MIDI and MP3 versions are included.

---

## 🚀 Future Improvements

- Real-time music generation
- Deep Learning assisted melody generation
- User preference learning
- Additional music genres
- Interactive web interface

---

## 👩‍💻 Author

**Keerthi G**

B.Tech Computer Science Engineering

---

