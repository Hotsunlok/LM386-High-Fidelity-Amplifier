## ⚡ PCB Layout — LM386 High-Fidelity Amplifier

This is the **two-layer PCB design** of the LM386 high-fidelity amplifier, created in **KiCad 8.0**.
The layout is optimized for **short signal paths** and **minimal noise**, using a **large ground plane** for stability.

---

### 🖼 PCB Overview

![PCB Layout](/images/pcb_amplifier.jpg)

---

### 🔍 Layout Description

* 🔵 **Ground Plane:** The blue area represents the **bottom copper layer**, serving as a **full ground plane** to reduce electrical noise and wiring complexity.
* 🎧 **Audio Input (Left Side):** Terminal block labeled `Audio_In` for signal input. Connected through a **volume potentiometer** for input level control.
* 🎛 **Gain Control:** Adjustable **gain potentiometer** (10 µF capacitor and resistor pair) allows fine-tuning of amplification strength.
* 🔋 **Power Input (Top-Right):** `PWR_IN` terminal for external DC supply (typically **9 V battery**).
* 🔊 **Speaker Output (Right Side):** Screw terminal labeled `SPK_OUT` for connecting the output speaker.
* 🪴 **Ground Plane Design:** Implemented on the **bottom layer** (blue copper fill) to minimize hum and interference in audio output.

---

🧠 *This PCB layout focuses on clarity, grounding efficiency, and compactness — ideal for DIY audio amplifier demonstrations.*

---
