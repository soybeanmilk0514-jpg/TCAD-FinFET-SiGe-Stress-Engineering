# FinFET pMOS Embedded SiGe S/D Stress Engineering

## Overview

25 nm pMOS FinFET의 Embedded SiGe Source/Drain에서 Ge composition과 fin recess depth(FR)가 channel stress, Stress Transfer Efficiency, drive performance, electrostatics, and leakage에 미치는 영향을 2-D design space로 분석한 프로젝트입니다.

![Project flow](./figures/project-flow.svg)

## Main DoE

| Axis | Levels |
|---|---|
| Ge | 30 / 40 / 50 / 60 / 70% |
| FR | 0 / 10 / 20 / 30 / 35 nm |
| Total | 25 points |

My assigned core runs were the Ge=30% and 40% columns, totaling 10 conditions.

## Final Result

The team proposed FR 15–20 nm as a practical design window for this TCAD structure.

At Ge=50%, FR=20 nm:

- STE = 0.667
- gmSat = 1.149e-4 S/µm
- SSlin = 84.7 mV/dec
- DIBL = 97.3 mV/V
- Ioff_norm = 9.68e-10

Increasing FR to 22 nm changed STE only from 0.667 to 0.668 while gmSat decreased and Ioff_norm increased to 1.93e-9.

## Documentation

See [Project Navigation](./guide/00_navigation.md) for the full documentation path and [My Contribution](./guide/05_my_contribution.md) for individual work boundaries.
