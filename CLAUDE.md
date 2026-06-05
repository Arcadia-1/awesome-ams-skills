# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

A curated "awesome list" of agent skills, simulators, infrastructure, benchmarks, and knowledge bases for Analog & Mixed-Signal (AMS) IC design. The repo contains language-specific Markdown files:

- `README.md` — English version (path `/`)

Banner titles and subtitles can be customized via front matter `banner_title` and `banner_subtitle` fields.

## Content Structure

Each skill entry follows this pattern:

```markdown
### [skill-repo-name](https://github.com/Arcadia-1/skill-repo-name)

One-line description of the skill collection.

- **skill-name** — Short description: key capabilities, technology, and specs.
```

Keep descriptions parallel in structure and concise. Bullet points describe individual skills within a repo, not the repo itself.

## Tracked Skill Repositories

| Repo | Skills |
|------|--------|
| [virtuoso-bridge-lite](https://github.com/Arcadia-1/virtuoso-bridge-lite) | SpectreSimulator, VirtuosoClient, SKILL execution, Maestro/ADE helpers, PSF parsers |
| [adctoolbox](https://github.com/Arcadia-1/ADCToolbox) | ADC characterization, calibration, diagnosis toolbox, 59 examples, Codex skill installer |
| [gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill) | ngspice, gmoverid, transistor-models |
| [AMS-IO-Agent](https://github.com/Arcadia-1/AMS-IO-Agent) | IO ring generation and Virtuoso verification agent |
| [analog-agents](https://github.com/Arcadia-1/analog-agents) | 12 analog design skills, librarian/architect/designer/verifier agents, knowledge graph, cross-model review |
| [veriloga-skills](https://github.com/Arcadia-1/veriloga-skills) | veriloga, evas-sim, openvaf |
| [sar-adc-skills](https://github.com/Arcadia-1/sar-adc-skills) | SAR ADC architecture, CDAC, comparator, bootstrap switch, LDO, SAR logic, integration, Spectre verification, 4-bit VA assets, 11-bit reference design |
| [Analog-Circuit-Knowledge-Base](https://github.com/Arcadia-1/Analog-Circuit-Knowledge-Base) | analog theory, amplifier references, noise/sampling techniques, calculation guides |
| [analog-circuit-skills](https://github.com/Arcadia-1/analog-circuit-skills) | comparator, bootstrap-switch, five-transistor-ota, two-stage-opamp, ldo |
| [EVAS](https://github.com/Arcadia-1/EVAS) | evas-sim — pure-Python event-driven VA simulator, 5 bundled smoke-test groups |
| [AMS-IO-Bench](https://github.com/Arcadia-1/AMS-IO-Bench) | 60-case IO ring generation benchmark |
| [Verilog-A-Sculptor](https://github.com/Arcadia-1/Verilog-A-Sculptor) | React/Vite Verilog-A generation app for ADC/DAC/TDC/DTC models |
| [behavioral-veriloga-eval](https://github.com/Arcadia-1/behavioral-veriloga-eval) | vaBench / vaEVAS benchmark, EVAS/Spectre validation assets |
| [adc-claw](https://github.com/Arcadia-1/adc-claw) | ADC Spectre simulation workspace: sampling, comparator, switch, SAR experiments |
