


LogoSoft‑Projects

A  collection of Siemens LOGO! PLC automation projects built with LOGO!Soft Comfort (v8.x). Each folder contains source files (.lsc), documentation, and simulation assets for educational or hobbyist use.

---

## 🚧 Projects Overview

⚡ 3-time lamp switching.lld
Sequentially switches three lamps ON and OFF at preset intervals. Demonstrates the usage of multiple timers in series to control independent outputs.

🔄 counter basic.lld
Implements a simple counter that increments with each input pulse and triggers an output when a preset value is reached—excellent for part counting or production batch detection.


🔒 latching.lld
Classic PLC “seal-in” logic: press a Start button to latch power ON, and press Stop to release. Teaches relay-like memory using self‑holding circuits. 


🔁 Star-delta starter.lld
Automates a three-phase motor’s Star-to-Delta transition using a timer to reduce inrush current on startup. Includes timing sequence and interlocks for safe switching.

⏱ timer ladder.lld
Demonstrates a simple ON-delay timer circuit: activate input, wait preset delay, then turn output ON. Great intro to TON instructions in ladder logic. 


💡 Circuit Diagram1.lsc
Circuit diagram for a basic control application (e.g., lamp or motor). Visualizes inputs, outputs, interlocks, and device connections—useful for understanding how ladder logic translates to real hardware.



## 📁 Repository Structure

```

/
├── StairCaseSwitch/
│   └── StairCaseSwitch.lsc
├── StairCaseSwitchWithPot/
│   └── StairCaseSwitchWithPot.lsc
├── SodaFillingConveyor/
│   ├── LOGO\_Soda\_Filling\_Conveyor.lsc
│   ├── Electrical Diagrams/
│   ├── My\_UDF\_Blocks/
│   └── README.md
└── README.md

````



---
 ⚙️ Getting Started

1. Clone the repository:
   ```bash git clone https://github.com/VedantJadhav258/LogoSoft-Projects.git
2. Open `.lsc` files in **LOGO!Soft Comfort v8.x**.
3. Optionally, use any provided circuit diagrams or documentation to understand logic flow.
 

 🤝 Contributing

Contributions welcome! To add your own project:

1. Fork this repo and add a new project folder.
2. Include `.lsc` source, diagrams, and a mini-README explaining inputs, outputs, and behavior.
3. Submit a pull request — I’d love to review and merge it!
---

