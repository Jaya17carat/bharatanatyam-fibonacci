# नाट्यम् × फिबोनाची — Natyam × Fibonacci

> *Where the sacred geometry of the golden spiral meets the ancient grammar of Bharatanatyam*

[![License: MIT](https://img.shields.io/badge/License-MIT-gold.svg)](LICENSE)
[![HTML](https://img.shields.io/badge/Built%20with-HTML%2FJS-orange.svg)]()
[![Data](https://img.shields.io/badge/Data-JSON-brown.svg)](data/poses.json)

---

## 🌀 Concept

**Bharatanatyam** is one of the oldest classical dance forms of India, codified in the *Natya Shastra* (~200 BCE–200 CE). Its geometry is precise — the Aramandi (half-sit) creates a perfect diamond, mudras fold fingers into sacred angles, and adavu sequences build rhythmic patterns that echo mathematical progressions.

The **Fibonacci sequence** (1, 1, 2, 3, 5, 8, 13, 21, 34, 55…) converges toward **φ (phi) ≈ 1.618**, the golden ratio. This ratio appears throughout nature — in sunflower spirals, nautilus shells, galaxy arms, and crucially, in the proportions of the **human body itself**.

This project maps each category of Bharatanatyam movement to a Fibonacci number, revealing how classical dance geometry aligns with the golden spiral.

---

## ✨ Key Mappings

| Fib n | Value | Dance Element | Sanskrit | Why it Matches |
|-------|-------|--------------|----------|----------------|
| 1 | 1 | Samapadam | समपादम् | Origin point — unity before movement |
| 2 | 1 | Ekapadam | एकपादम् | Single axis — one leg, one line |
| 3 | **2** | Aramandi | अर्धमण्डली | Diamond shape — 2 legs, 90° diamond |
| 4 | **3** | Muzhumandi | मुझुमण्डली | 3 joint angles at Fibonacci intervals |
| 5 | **5** | Mudras (Asamyukta) | असंयुक्त हस्त | 5 fingers with φ-ratio phalanx lengths |
| 6 | **8** | Adi Tala | आदि ताल | 8 beats = Fib(6) exactly |
| 7 | **13** | Adavus | अदावु | 13 foundational adavu groups |
| 8 | **21** | Navarasas | नवरस | ~21 expressive states in full Margam |
| 9 | **34** | Varnam | वर्णम् | ~34 sequences in a complete Varnam |
| 10 | **55** | Margam | मार्गम् | Full recital arc = complete golden spiral |

---

## 🔬 The Golden Ratio in Bharatanatyam Geometry

### Aramandi — The Diamond
The Aramandi (half-sit) requires the knees to be bent outward at ~90° with heels together. The body's key points — crown, left knee, right knee, and heels — form a **rhombus**. The ratio of the vertical diagonal to the horizontal diagonal of this rhombus approaches **φ** in ideal form.

```
        HEAD (crown)
           |
      _____|_____
     /           \
LEFT KNEE     RIGHT KNEE     ← horizontal span
     \           /
      \_________/
           |
         HEELS
```

### Human Body & φ
The golden ratio is encoded in the human body — which is the instrument of Bharatanatyam:
- Navel-to-floor ÷ total height ≈ **1.618**
- Forearm ÷ hand length ≈ **1.618**
- Finger phalanx ratios ≈ **1.618**

This means a dancer in Aramandi is literally embodying the golden spiral.

### Adi Tala — Rhythm as Fibonacci
Adi Tala: **8 beats** (4 + 2 + 2) = **Fib(6)**
- Subdivision ratio: 4:2 = **2.0** (approaching φ)
- 8 / 5 (next lower Fib) = **1.600** (≈ φ)

### Adavus — 13 is Fib(7)
The Tanjavur school of Bharatanatyam codifies **13 adavu groups** — a count that is not arbitrary. It corresponds to Fib(7), sitting between 8 and 21 in the spiral of complexity.

---

## 📁 Project Structure

```
bharatanatyam-fibonacci/
├── index.html              # Interactive web demo
├── README.md               # This file
├── data/
│   └── poses.json          # Full pose-to-Fibonacci dataset
└── assets/                 # (optional) images, diagrams
```

---

## 🚀 Running the Project

No build step needed — this is a pure HTML/CSS/JS project.

```bash
git clone https://github.com/YOUR_USERNAME/bharatanatyam-fibonacci
cd bharatanatyam-fibonacci
open index.html
# or: python3 -m http.server 8080
```

---

## 🎯 Features

- **Interactive Fibonacci spiral** — animated canvas drawing the golden spiral arc by arc
- **Pose cards** — click any pose to highlight its corresponding spiral arc
- **Three visualization modes**: Spiral, Rectangles, Pose Overlay
- **Full data table** — all 10 mappings with geometric descriptions
- **JSON dataset** — machine-readable `poses.json` with rich metadata including joint angles, Sanskrit references, and φ relationships

---

## 📖 Sources & References

- **Natya Shastra** — Bharata Muni (approx. 200 BCE–200 CE) — *the foundational text of Indian performing arts*
- **Abhinaya Darpana** — Nandikesvara — *mirror of gesture, the mudra compendium*
- **Sangita Ratnakara** — Sarngadeva (13th century) — *music and tala theory*
- **The Mirror of Gesture** — Coomaraswamy & Duggirala (1917)
- **Fibonacci Numbers and the Golden Section** — Ron Knott, University of Surrey

---

## 🌱 Contributing

Contributions welcome! Ideas for extension:

- [ ] Add more dance styles (Kuchipudi, Odissi, Manipuri) with their own Fibonacci mappings
- [ ] Computer vision pose detection that overlays the Fibonacci spiral in real time
- [ ] Interactive mudra builder showing φ proportions in finger segments
- [ ] Audio: play the Fibonacci sequence as a tala rhythm
- [ ] 3D visualization of the spiral wrapped around a dancing figure

---

## 📄 License

MIT License — open for dance scholars, mathematicians, and artists alike.

---

<p align="center">
  <em>"The body is the temple. The dance is the prayer. The mathematics is the universe."</em>
</p>
