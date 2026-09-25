# 03. Baseline Device & Design of Experiments

## Baseline

| Item | Value |
|---|---:|
| Device | pMOS FinFET |
| Gate length | 25 nm |
| Fin height | 35 nm |
| Fin width | 15 nm |
| S/D–channel lateral distance, Esd | 7.5 nm |
| S/D dopant | Boron |
| S/D concentration | 2e20 cm^-3 |
| Channel concentration | 2e18 cm^-3 |
| VDD | 0.8 V |
| Gate workfunction | 4.623 eV |
| Channel direction | <110> |
| Substrate orientation | (100) |

Ge 조성과 FR을 제외한 조건은 본 25점 격자에서 고정했다.

## Main DoE

Ge:
30 / 40 / 50 / 60 / 70 %

FR:
0 / 10 / 20 / 30 / 35 nm

총 5 × 5 = 25 조건이다.

## Additional Verification

본 격자와 별도로 다음 조건을 계산했다.

- Ge=50%, FR=15 nm
- Ge=50%, FR=22 nm
- Ge=50%, Strain_Impact ON/OFF FR sweep
- Fin width 15 nm → 7.5 nm sensitivity at Ge=60/70%

추가 검증점은 본 25점 회귀 격자와 분리해 해석했다.
