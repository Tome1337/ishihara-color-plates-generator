# Ishihara Color Plates Generator 🎨

This repository documents the research and methodology behind generating pseudoisochromatic color plates inspired by the original Ishihara test (1917).

It **does not contain the proprietary source code** of the generator.  
Instead, it outlines the visual and colorimetric principles used to create valid, ΔE-calibrated Ishihara-style plates for educational and research purposes.

---

## 🔬 Methodology Overview

- Color space: CIE LAB and LMS cone response simulation  
- Target contrast: ΔE\*ab ≈ 14 ± 3 (based on standard plate readability thresholds)  
- Dot layout: randomized circle field (1 200–1 800 dots per plate)  
- Figure generation: parametric mask with equal area ratio  
- Validation: simulated Protanopia and Deuteranopia perception

---

## 📊 Research Documentation

Detailed notes and references are available in  
[`/docs/research-overview.md`](docs/research-overview.md)

Live web reference:  
👉 [https://ishiharatest.com/en-us/](https://ishiharatest.com/en-us/)

---

## 🧠 Disclaimer

The full algorithm implementation is proprietary and protected under intellectual property rights.  
This repository is released for **educational and verification purposes only**.

---

## 📜 License

This work is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**  
➡️ [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

---

Developed by **Tomáš Pokrývka / Websy s.r.o. (Poprad, Slovakia)**  
Contact: [info@websy.sk](mailto:info@websy.sk)
