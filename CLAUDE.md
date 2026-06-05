# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

A curated "awesome list" of Claude Code agent skills for Analog & Mixed-Signal (AMS) IC design. The repo contains language-specific Markdown files:

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
| [gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill) | ngspice, gmoverid, transistor-models |
| [analog-circuit-skills](https://github.com/Arcadia-1/analog-circuit-skills) | comparator, bootstrap-switch, five-transistor-ota, two-stage-opamp, ldo, reference-buffer, source-buffer, push-pull-buffer, ringamp, floating-inverter-amplifier, floating-charge-transferrer, phase-noise *(most WIP)* |
| [veriloga-skills](https://github.com/Arcadia-1/veriloga-skills) | veriloga, openvaf |
| [EVAS](https://github.com/Arcadia-1/EVAS) | evas-sim — pure-Python event-driven VA simulator |
| [sar-adc-skills](https://github.com/Arcadia-1/sar-adc-skills) | SAR ADC architecture, CDAC, comparator, bootstrap switch, LDO, SAR logic, integration, Spectre verification, 4-bit VA assets, 11-bit reference design |
| [virtuoso-bridge-lite](https://github.com/Arcadia-1/virtuoso-bridge-lite) | SpectreSimulator, VirtuosoClient, SKILL execution, Maestro/ADE helpers, PSF parsers |
| [adc-claw](https://github.com/Arcadia-1/adc-claw) | ADC Spectre simulation workspace: sampling, comparator, switch, SAR experiments |
| [adctoolbox](https://github.com/Arcadia-1/ADCToolbox) | ADC characterization, calibration, and diagnosis toolbox |
