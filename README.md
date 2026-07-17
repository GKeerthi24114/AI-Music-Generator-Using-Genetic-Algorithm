# 🎵 Automatic Melody Improvisation Using Genetic Algorithms

An AI-powered melody generation system that uses **Genetic Algorithms (GA)** to automatically compose melodies in multiple musical styles while following a user-defined target melody. The system evolves melodies through selection, crossover, and mutation, producing high-quality MIDI compositions along with detailed analytical PDF reports.

---

## 📌 Project Overview

This project applies **Evolutionary Computation** to music generation by representing melodies as chromosomes and improving them over successive generations using Genetic Algorithms.

Unlike deep learning approaches, this system:

- Does not require large datasets
- Does not require GPU training
- Supports user-defined melodies
- Allows multiple musical styles
- Produces both musical and analytical outputs

---

## ✨ Features

- 🎼 Automatic melody generation using Genetic Algorithms
- 🎵 Supports target melody as user input
- 🎹 Major and Minor scale support
- 🎶 Multiple musical styles
  - Soft
  - Rap
  - Classical
- 🔄 Adaptive crossover and mutation
- 📈 Fitness-based melody evolution
- 📊 Fitness evolution graphs
- 🎼 Pitch contour visualization
- 📄 Automatic PDF report generation
- 🎧 MIDI file generation
- ⚙️ Adjustable GA parameters
- 📋 Multi-run performance comparison

---

## 🧬 Genetic Algorithm Workflow

1. User enters target melody
2. Initial melody population is randomly generated
3. Fitness of each melody is evaluated
4. Best melodies are selected
5. Crossover creates offspring
6. Mutation introduces diversity
7. New generation replaces weaker melodies
8. Process repeats for multiple generations
9. Best melody is exported as MIDI
10. Performance report is generated as PDF

---

## 🎵 Musical Styles

### 🎼 Soft Style
- Smooth note transitions
- Minimal pitch jumps
- Pleasant melodic flow

### 🎤 Rap Style
- Greater rhythmic variation
- Higher note diversity
- Dynamic melodic movement

### 🎻 Classical Style
- Preserves contour of target melody
- Balanced musical progression
- Traditional melodic characteristics

---

## 📊 Evaluation Metrics

The generated melodies are evaluated using:

- Fitness Score
- Smoothness
- Pitch Transition Quality
- Contour Similarity
- Musical Diversity
- Listener Feedback
- Style Consistency

---

## 📈 Outputs

The project automatically generates:

### 🎵 MIDI Files

Playable melodies for every generated style.

### 📄 PDF Report

Contains

- Fitness evolution graphs
- Pitch contour plots
- Style comparison
- Parameter summary
- Generation statistics
- Best fitness score
- Performance analysis

---

## ⚙️ User Configurable Parameters

Users can customize

- Melody Length
- Musical Scale
- Tempo (BPM)
- Population Size
- Number of Generations
- Mutation Rate
- Crossover Type
- Musical Style
- Target Melody

---

## 🛠️ Technologies Used

- Python
- Genetic Algorithms
- NumPy
- Mido
- MIDIUtil
- Matplotlib
- FPDF
- Evolutionary Computation

---

## 📂 Repository Structure

```
Automatic-Melody-Improvisation/
│
├── README.md
├── requirements.txt
├── Automatic_Melody_Improvisation.ipynb
│
├── outputs/
│   ├── midi_files/
│   ├── reports/
│   ├── fitness_graphs/
│   └── pitch_contours/
│
└── images/
```

---

## 🚀 Results

The system successfully

- Generates melodically coherent music
- Evolves melodies over multiple generations
- Produces distinct outputs for Soft, Rap, and Classical styles
- Creates MIDI files for playback
- Generates detailed PDF reports with visual analysis
- Balances creativity and musical structure using evolutionary optimization

---

## 🔮 Future Improvements

- Multi-instrument music generation
- Chord progression generation
- Real-time melody improvisation
- Hybrid GA + Deep Learning models
- Emotion-aware music generation
- Longer musical compositions
- Interactive web interface

---

## 👩‍💻 Author

**Keerthi G**

B.Tech Computer Science and Engineering

Amrita Vishwa Vidyapeetham

---

