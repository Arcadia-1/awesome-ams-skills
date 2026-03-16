---
layout: default
permalink: /en/
banner_title: Awesome AMS Skills
banner_subtitle: AMS IC design automation skills for AI agents — engineering-first, hands-on guides.
---

[![zh](https://img.shields.io/badge/lang-中文-red.svg)](https://ams.tokenzhang.com/)
[![GitHub stars](https://img.shields.io/github/stars/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/network)
[![GitHub last commit](https://img.shields.io/github/last-commit/Arcadia-1/awesome-ams-skills)](https://github.com/Arcadia-1/awesome-ams-skills/commits/main)

---

## Skills

### [gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill)

Foundation skill pack for analog IC design: models, simulation, characterization, and systematic sizing.

- **ngspice** — Open-source simulator tutorials: 9 reference scenarios covering DC, AC, Transient, and Noise analyses with built-in PTM 180/45/22nm models.
- **gmoverid** — gm/ID design methodology: transistor characterization (I-V curves, gm/Id relationships, gate capacitance) and automated sizing via lookup-table API.
- **transistor-models** — Complete PTM MOSFET model library: Bulk CMOS (180nm–22nm) and FinFET (20nm–7nm), BSIM3v3/BSIM4/BSIM-CMG.

### [analog-circuit-skills](https://github.com/Arcadia-1/analog-circuit-skills)

Block-level circuit design skill pack: theory, simulation, and practical design insights.

- **comparator** — Dynamic comparator: topology and operating-phase theory, waveform/noise/ramp simulation, speed–power–noise sizing sweeps, and FOM extraction. Includes StrongArm and Miyahara examples.
- **bootstrap-switch** — Bootstrapped NMOS sampling switch: circuit topology and operating phases, gate-voltage bootstrap verification (Vgs = VDD constant), Ron comparison across input range (NMOS / CMOS / bootstrap), and transistor sizing guidance.
- **ldo** — Low-dropout regulator design and simulation. *(WIP)*
- **reference-buffer** — Reference voltage buffer. *(WIP)*
- **source-buffer** — Source follower, FVF (Flipped-Voltage-Follower), and SSF (Super-Source-Follower) analysis, characterization, and design. *(WIP)*
- **push-pull-buffer** — Push-pull input buffer. *(WIP)*
- **ringamp** — Ring amplifier analysis, characterization, and design. *(WIP)*
- **floating-inverter-amplifier** — Floating inverter amplifier analysis, characterization, and design. *(WIP)*
- **floating-charge-transferrer** — Floating charge transferrer analysis, characterization, and design. *(WIP)*
- **phase-noise** — Phase noise analysis and calculation. *(WIP)*

### [veriloga-skills](https://github.com/Arcadia-1/veriloga-skills)

Write Verilog-A code that compiles directly in Cadence Virtuoso and simulates in Spectre.

- **veriloga** — Coding rules and reference examples, validated against Virtuoso/Spectre compilation. 12-category circuit reference library with domain-aware simulation routing (voltage → EVAS, current → OpenVAF/ngspice).
- **openvaf** — Guide for compiling Verilog-A device models into plugins (.osdi) with OpenVAF and loading them into ngspice for circuit simulation.

### [EVAS](https://github.com/Arcadia-1/EVAS) [![PyPI](https://img.shields.io/pypi/v/evas-sim.svg)](https://pypi.org/project/evas-sim/) [![PyPI Downloads](https://img.shields.io/pypi/dm/evas-sim)](https://pypi.org/project/evas-sim/)

Zero-dependency, instant-response Verilog-A behavioral simulation sandbox — ideal for verifying clock, control, and calibration logic.

- Pure-Python event-driven engine: instant verification of Verilog-A modules with no EDA license required.
- Drop-in Virtuoso/Spectre syntax compatibility — run existing `.va` code without modification.
- 14 bundled example groups covering ADC-DAC, DWA algorithms, dither-based gain extraction, comparator offset search, and more — full reference from source to waveform visualization.
- **evas-sim** — Guides agents to autonomously build, run, and debug Verilog-A behavioral models in license-free environments.

### [sar-adc-skills](https://github.com/Arcadia-1/sar-adc-skills)

SAR ADC system design skill pack.

- **sar-adc** — SAR ADC system modeling, specification budgeting, and key design considerations. *(WIP)*
- **sar-cdac** — Capacitor array control principles, modeling, and implementation. *(WIP)*
- **sar-logic** — SAR logic control principles, modeling, and implementation. *(WIP)*

### [adctoolbox](https://github.com/Arcadia-1/ADCToolbox) [![PyPI](https://img.shields.io/pypi/v/adctoolbox.svg)](https://pypi.org/project/adctoolbox/) [![PyPI Downloads](https://img.shields.io/pypi/dm/adctoolbox)](https://pypi.org/project/adctoolbox/)

Multi-dimensional ADC characterization and diagnosis toolbox for deep insight into non-idealities.

- One-click metric extraction: ENOB, SNDR, SFDR, SNR, HD3 with automatic harmonic and noise-floor annotation.
- One-click weight calibration: sine-wave-based bit-weight extraction with stability enhancements, multi-frequency/multi-dataset joint calibration, and overfitting mitigation.
- Visual fault diagnosis: polar spectrum, jitter extraction, error decomposition, and error distribution — going beyond traditional FFT plots.
- Closed-loop design verification: 15 built-in non-ideality models (jitter, thermal noise, settling error, etc.) and 45 ready-to-run examples covering simulation to digital calibration.
- Battle-tested: core algorithms distilled from 50+ tape-out projects.
- Available as a pip package (Python) and Add-On Explorer toolbox (MATLAB).

---

## Contributing

PRs are welcome in the following directions:

- Additional automation scripts.
- New topology support: inverter-based gain stages, incremental ADC architectures, etc.
- LLM Prompting Templates: share how you prompt Claude to use these skills for your design tasks.
