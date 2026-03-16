---
layout: default
permalink: /
banner_title: Awesome AMS Skills
banner_subtitle: 模拟与混合信号 (AMS) 集成电路设计自动化技能集。为智能体打造的工程实战指南。
---

[![en](https://img.shields.io/badge/lang-English-blue.svg)](https://ams.tokenzhang.com/en/)
[![GitHub stars](https://img.shields.io/github/stars/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Arcadia-1/awesome-ams-skills?style=flat)](https://github.com/Arcadia-1/awesome-ams-skills/network)
[![GitHub last commit](https://img.shields.io/github/last-commit/Arcadia-1/awesome-ams-skills)](https://github.com/Arcadia-1/awesome-ams-skills/commits/main)

模拟与混合信号 (AMS) 集成电路设计自动化技能集。为智能体打造的工程实战指南。

---

## 技能列表

### [gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill)

模拟集成电路基础技能包：模型、仿真、表征与系统化尺寸设计。

- **ngspice** — 开源仿真器仿真教程。涵盖 DC、AC、瞬态、噪声分析的 9 个参考场景，内置 PTM 180/45/22nm 模型。
- **gmoverid** — gm/ID 设计方法：晶体管参数表征（电压-电流特性曲线、gm/Id 关系、栅电容）及自动尺寸设计查表 API。
- **transistor-models** — 完整 PTM MOSFET 模型库：Bulk CMOS（180nm–22nm）及 FinFET（20nm–7nm），支持 BSIM3v3/BSIM4/BSIM-CMG。

### [analog-circuit-skills](https://github.com/Arcadia-1/analog-circuit-skills)

模块级电路设计技能包：理论分析与仿真实践。

- **comparator** — 动态比较器：拓扑与工作相位原理、波形/噪声/斜坡仿真、速度–功耗–噪声尺寸扫描及 FOM 提取。包含 StrongArm 与 Miyahara 两种示例。
- **bootstrap-switch** — Bootstrap NMOS 采样开关：电路拓扑与工作相位、栅极电压自举验证（Vgs 恒等于 VDD）、输入范围内 Ron 对比（NMOS/CMOS/bootstrap）及晶体管尺寸指导。
- **ldo** — 低压差线性稳压器（LDO）设计与仿真。【开发中】
- **reference-buffer** - 参考电压缓冲器。【开发中】
- **source-buffer** - 源极跟随器、FVF（Flipped-Voltage-Follower）、SSF（Super-Source-Follower）分析、表征与设计。【开发中】
- **push-pull-buffer** - 推挽类输入缓冲器。【开发中】
- **ringamp** - 环形放大器分析、表征与设计。【开发中】
- **floating-inverter-amplifier** - 浮空反相放大器分析、表征与设计。【开发中】
- **floating-charge-transferrer** - 浮空电荷转移器分析、表征与设计。【开发中】
- **phase-noise** - 相位噪声分析与计算。【开发中】

### [veriloga-skills](https://github.com/Arcadia-1/veriloga-skills)

写出可直接用于 Cadence Virtuoso 编译并适配 Spectre 仿真的 Verilog-A 代码。

- **veriloga** — 编码规范与参考示例。经过 Virtuoso/Spectre 编译校对。12 类电路。
- **openvaf** — 指导如何使用 OpenVAF 将 Verilog-A 写的器件模型编译成插件（.osdi），并让开源仿真器 ngspice 能够成功调用它进行电路仿真。

### [EVAS](https://github.com/Arcadia-1/EVAS) [![PyPI](https://img.shields.io/pypi/v/evas-sim.svg)](https://pypi.org/project/evas-sim/) [![PyPI Downloads](https://img.shields.io/pypi/dm/evas-sim)](https://pypi.org/project/evas-sim/)

零依赖、秒级响应的 Verilog-A 行为级仿真沙箱，时钟、控制、校准等模块的验证利器。

- 打破传统 EDA 软件的沉重枷锁，通过纯 Python 事件驱动引擎实现 Verilog-A 模块的瞬时验证。
- 格式完全兼容 Virtuoso/Spectre 现有语法，实现代码无修正（Drop-in）运行。
- 内置涵盖 ADC-DAC、DWA 算法、基于 dither 的增益提取、比较器失调搜索等 14 类复杂系统模型，提供从源码到波形可视化的全流程参考。
- **evas-sim** — 指导智能体在无 License 环境下自主构建、运行并调试 Verilog-A 行为模型。

### [sar-adc-skills](https://github.com/Arcadia-1/sar-adc-skills)

SAR ADC 系统设计技能包。

- **sar-adc** - SAR ADC 系统建模、指标拆解、设计要点。【开发中】
- **sar-cdac** - 电容阵列控制原理、建模与实现。【开发中】
- **sar-logic** - SAR 逻辑控制原理、建模与实现。【开发中】

### [adctoolbox](https://github.com/Arcadia-1/ADCToolbox) [![PyPI](https://img.shields.io/pypi/v/adctoolbox.svg)](https://pypi.org/project/adctoolbox/) [![PyPI Downloads](https://img.shields.io/pypi/dm/adctoolbox)](https://pypi.org/project/adctoolbox/)

多维度 ADC 表征与诊断工具箱，深度洞察 ADC 结果背后的非理想性。

- 指标一键提取：计算 ENOB、SNDR、SFDR、SNR、HD3 等核心指标，并智能标注谐波与噪底。
- 权重一键校准：基于正弦波的比特权重提取算法。多种稳定性增强技术。支持多频率/多组数据联合校准。多种手段降低过拟合风险。
- 可视化故障诊断：超越传统 FFT 绘图，提供极坐标频谱、jitter 提取、误差分解、误差分布等工具进行深度表征与调试。
- 闭环设计验证：内置 15 种非理想信号模型（如抖动、热噪声、建立误差）和 45 个现成案例，涵盖从基础仿真到数字校准算法的完整链路。
- 久经流片验证：核心算法源自 50+ 次流片项目的经验沉淀。
- 专业化分发与部署：Python 支持 pip 安装；MATLAB 提供标准工具箱分发，支持在 Add-On Explorer 中搜索同名 Toolbox 安装。

---

## 如何贡献与扩展？

我们欢迎开发者针对以下方向提交 PR，丰富智能体的武器库：

- 更多自动化脚本。
- 新拓扑支持：如基于反相器的增益级、各种架构的增量型 ADC。
- LLM Prompting Templates：分享你如何引导 Claude 使用这些技能完成设计的 Prompt。
