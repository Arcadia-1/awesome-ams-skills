---
layout: default
permalink: /
banner_title: Awesome AMS Skills
banner_subtitle: AMS IC design automation skills for AI agents — engineering-first, hands-on guides.
---

[![GitHub stars](https://img.shields.io/github/stars/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/network)
[![GitHub last commit](https://img.shields.io/github/last-commit/Arcadia-1/awesome-ams-skills)](https://github.com/Arcadia-1/awesome-ams-skills/commits/main)

---

## Projects

### [virtuoso-bridge-lite](https://github.com/Arcadia-1/virtuoso-bridge-lite) [![Stars](https://img.shields.io/github/stars/Arcadia-1/virtuoso-bridge-lite?style=flat-square&logo=github)](https://github.com/Arcadia-1/virtuoso-bridge-lite/stargazers)

Lightweight Python bridge for remote Cadence Virtuoso and Spectre workflows.

- **SpectreSimulator** — Run Spectre remotely through SSH, transfer netlists/results, choose Spectre modes, and parse PSF ASCII outputs for automated analysis.
- **VirtuosoClient** — Execute SKILL, inspect/edit schematics and layouts, drive Maestro/ADE workflows, and collect snapshots/results through a Python interface.
- **agent tooling** — Includes Spectre/Virtuoso skills, examples, profile-based environment resolution, and reusable parsers used by downstream AMS workflows.

### [ADCToolbox](https://github.com/Arcadia-1/ADCToolbox) [![Stars](https://img.shields.io/github/stars/Arcadia-1/ADCToolbox?style=flat-square&logo=github)](https://github.com/Arcadia-1/ADCToolbox/stargazers) [![PyPI](https://img.shields.io/pypi/v/adctoolbox.svg?style=flat-square)](https://pypi.org/project/adctoolbox/) [![PyPI Downloads](https://img.shields.io/pypi/dm/adctoolbox?style=flat-square)](https://pypi.org/project/adctoolbox/)

Multi-dimensional ADC characterization and diagnosis toolbox for deep insight into non-idealities.

- One-click metric extraction: ENOB, SNDR, SFDR, SNR, HD3 with automatic harmonic and noise-floor annotation.
- One-click weight calibration: sine-wave-based bit-weight extraction with stability enhancements, multi-frequency/multi-dataset joint calibration, and overfitting mitigation.
- Visual fault diagnosis: polar spectrum, jitter extraction, error decomposition, and error distribution — going beyond traditional FFT plots.
- Closed-loop design verification: synthetic ADC impairment models plus 59 ready-to-run examples covering simulation, analog diagnosis, digital calibration, and visualization workflows.
- Battle-tested: core algorithms distilled from 50+ tape-out projects.
- Available as a pip package (Python), MATLAB toolbox, and bundled Codex skill installer.

### [gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill) [![Stars](https://img.shields.io/github/stars/Arcadia-1/gmoverid-skill?style=flat-square&logo=github)](https://github.com/Arcadia-1/gmoverid-skill/stargazers)

Foundation skill pack for analog IC design: models, simulation, characterization, and systematic sizing.

- **ngspice** — Open-source simulator tutorials: 9 reference scenarios covering DC, AC, Transient, and Noise analyses with built-in PTM 180/45/22nm models.
- **gmoverid** — gm/ID design methodology: transistor characterization (I-V curves, gm/Id relationships, gate capacitance) and automated sizing via lookup-table API.
- **transistor-models** — PTM model library: traditional bulk 180/130/90/65nm, HP/LP 45/32/22nm, and multi-gate FinFET 20/16/14/10/7nm.

### [AMS-IO-Agent](https://github.com/Arcadia-1/AMS-IO-Agent) [![Stars](https://img.shields.io/github/stars/Arcadia-1/AMS-IO-Agent?style=flat-square&logo=github)](https://github.com/Arcadia-1/AMS-IO-Agent/stargazers)

LLM-driven Cadence Virtuoso agent for IO ring schematic/layout generation and verification.

- **IO automation** — Generates IO pad-ring schematics/layouts from structured requirements and design knowledge bases.
- **verification flow** — Integrates DRC, LVS, PEX, image-vision inspection, task history, and tool statistics.
- **interfaces** — CLI and optional Gradio web UI with multi-model API support.

### [analog-agents](https://github.com/Arcadia-1/analog-agents) [![Stars](https://img.shields.io/github/stars/Arcadia-1/analog-agents?style=flat-square&logo=github)](https://github.com/Arcadia-1/analog-agents/stargazers)

Federated agentic analog IC design framework: 12 skills, 4 agent roles, knowledge graph, cross-model review, and self-evolving checklists for design flows with or without EDA.

- **librarian / architect / designer / verifier** — Role-separated agents for library survey, architecture decomposition, transistor-level design, pre-simulation review, Spectre verification, and sign-off.
- **verification levels** — L1 functional, L2 performance, and L3 PVT robustness flow with explicit spec sheets, margin reports, and iteration logs.
- **knowledge graph + checklists** — Topology lessons, anti-patterns, review rules, and effort levels that scale from quick checks to exhaustive verification.

### [veriloga-skills](https://github.com/Arcadia-1/veriloga-skills) [![Stars](https://img.shields.io/github/stars/Arcadia-1/veriloga-skills?style=flat-square&logo=github)](https://github.com/Arcadia-1/veriloga-skills/stargazers)

Write Verilog-A code that compiles directly in Cadence Virtuoso and simulates in Spectre.

- **veriloga** — Coding rules and reference examples, validated against Virtuoso/Spectre compilation. 12-category circuit reference library with domain-aware simulation routing (voltage → EVAS, current → OpenVAF/ngspice).
- **evas-sim** — Optional voltage-domain verification path for behavioral Verilog-A modules using EVAS event-driven simulation.
- **openvaf** — Guide for compiling Verilog-A device models into plugins (.osdi) with OpenVAF and loading them into ngspice for circuit simulation.

### [sar-adc-skills](https://github.com/Arcadia-1/sar-adc-skills) [![Stars](https://img.shields.io/github/stars/Arcadia-1/sar-adc-skills?style=flat-square&logo=github)](https://github.com/Arcadia-1/sar-adc-skills/stargazers)

SAR ADC design knowledge base for agentic IC design — from system architecture to transistor-level implementation and verification.

- **sar-adc-skill** — Full SAR ADC design guide: specs-to-budgets, CDAC-centered architecture, sync/async SAR logic, comparator/bootstrap/LDO submodules, top-level integration, PVT/metastability/reference concerns, and Spectre verification flow.
- **behavioral Verilog-A assets** — 4-bit SAR building blocks for system verification: ideal CDAC, comparator, sync logic, async logic, DAC, and single-ended SAR ADC model.
- **11-bit reference design** — Taped-out SAR ADC reference notes covering module hierarchy, signal polarity, async control, CDAC unit sizing, bootstrap switch, StrongArm comparator, and verification checklist.

### [Analog-Circuit-Knowledge-Base](https://github.com/Arcadia-1/Analog-Circuit-Knowledge-Base) [![Stars](https://img.shields.io/github/stars/Arcadia-1/Analog-Circuit-Knowledge-Base?style=flat-square&logo=github)](https://github.com/Arcadia-1/Analog-Circuit-Knowledge-Base/stargazers)

Structured analog circuit reference library for amplifier theory, noise techniques, ADC architectures, pole-zero analysis, and design calculations.

- **amplifier references** — Single-transistor stages, 5T differential amplifier, Miller two-stage amplifier, ringamp, floating inverter amplifier, and floating charge-transfer amplifier.
- **noise and sampling notes** — kT/C cancellation, correlated double sampling, correlated level shifting, current-integration sampling, and source-degeneration noise analysis.
- **calculation guides** — Bandwidth, phase-noise conversion, comparator noise statistics, and capacitance extraction from AC simulation.

### [analog-circuit-skills](https://github.com/Arcadia-1/analog-circuit-skills) [![Stars](https://img.shields.io/github/stars/Arcadia-1/analog-circuit-skills?style=flat-square&logo=github)](https://github.com/Arcadia-1/analog-circuit-skills/stargazers)

Block-level circuit design skill pack: theory, simulation, and practical design insights.

- **comparator** — Dynamic comparator: topology and operating-phase theory, waveform/noise/ramp simulation, speed–power–noise sizing sweeps, and FOM extraction. Includes StrongArm and Miyahara examples.
- **bootstrap-switch** — Bootstrapped NMOS sampling switch: circuit topology and operating phases, gate-voltage bootstrap verification (Vgs = VDD constant), Ron comparison across input range (NMOS / CMOS / bootstrap), and transistor sizing guidance.
- **five-transistor-ota** — Classic 5T CMOS OTA with NMOS differential pair, PMOS current-mirror load, and NMOS tail source; includes ngspice DC transfer, AC gain/bandwidth/phase, and output-noise analysis.
- **two-stage-opamp** — Miller-compensated two-stage CMOS op amp with PMOS input pair, NMOS mirror load, second common-source gain stage, bias mirror, DC operating-point, AC gain/phase, pole-zero, and open-/closed-loop noise simulations.
- **ldo** — Low-dropout regulator with ngspice DC, AC loop/PSRR/Zout, transient load/line behavior, noise, compensation sweeps, and auto-design helper scripts.

### [EVAS](https://github.com/Arcadia-1/EVAS) [![Stars](https://img.shields.io/github/stars/Arcadia-1/EVAS?style=flat-square&logo=github)](https://github.com/Arcadia-1/EVAS/stargazers) [![PyPI](https://img.shields.io/pypi/v/evas-sim.svg?style=flat-square)](https://pypi.org/project/evas-sim/) [![PyPI Downloads](https://img.shields.io/pypi/dm/evas-sim?style=flat-square)](https://pypi.org/project/evas-sim/)

Zero-dependency, instant-response Verilog-A behavioral simulation sandbox — ideal for verifying clock, control, and calibration logic.

- Pure-Python event-driven engine: instant verification of Verilog-A modules with no EDA license required.
- Drop-in Virtuoso/Spectre syntax compatibility — run existing `.va` code without modification.
- 5 bundled smoke-test groups covering clock dividers, digital basics, noise generation, ideal ADC/DAC, and comparator examples; the larger workflow-oriented example set lives in `veriloga-skills/evas-sim`.
- **evas-sim** — Guides agents to autonomously build, run, and debug Verilog-A behavioral models in license-free environments.

### [AMS-IO-Bench](https://github.com/Arcadia-1/AMS-IO-Bench) [![Stars](https://img.shields.io/github/stars/Arcadia-1/AMS-IO-Bench?style=flat-square&logo=github)](https://github.com/Arcadia-1/AMS-IO-Bench/stargazers)

Benchmark dataset for automated IC IO ring generation in Cadence Virtuoso.

- **60 cases** — 28nm and 180nm wirebonding cases from 3×3 to 18×18 pad rings.
- **coverage** — Single/double rings, digital/analog/mixed signals, and multi-voltage-domain configurations.
- **metrics** — Correctness, completeness, DRC/LVS cleanliness, domain isolation, pad ordering, and efficiency.

### [Verilog-A-Sculptor](https://github.com/Arcadia-1/Verilog-A-Sculptor) [![Stars](https://img.shields.io/github/stars/Arcadia-1/Verilog-A-Sculptor?style=flat-square&logo=github)](https://github.com/Arcadia-1/Verilog-A-Sculptor/stargazers)

React + Vite application for AI-assisted Verilog-A model generation.

- **model recipes** — ADC, DAC, TDC, and DTC behavioral-model settings.
- **global constraints** — Module naming, hidden-state handling, transition strategy, supply style, reset, and enable behavior.
- **LLM generation** — Gemini-powered code generation with rationale and copyable Verilog-A output.

### [behavioral-veriloga-eval](https://github.com/Arcadia-1/behavioral-veriloga-eval) [![Stars](https://img.shields.io/github/stars/Arcadia-1/behavioral-veriloga-eval?style=flat-square&logo=github)](https://github.com/Arcadia-1/behavioral-veriloga-eval/stargazers)

vaBench / vaEVAS benchmark source for behavioral Verilog-A generation and validation.

- **task families** — `spec-to-va`, `tb-generation`, `end-to-end`, and `bugfix` benchmark cases.
- **validation route** — EVAS for fast local checking and Spectre for final gold promotion or paper-facing evidence.
- **benchmark assets** — Prompt, metadata, checks, gold assets, and compact evidence reports for release-quality tasks.

---

## Coming Soon

### [custom-cdac-layout] — *To be open-sourced*
### [skill-skill] — *To be open-sourced*

---

## Contributing

PRs are welcome in the following directions:

- Additional automation scripts.
- New topology support: inverter-based gain stages, incremental ADC architectures, etc.
- LLM Prompting Templates: share how you prompt Claude to use these skills for your design tasks.
