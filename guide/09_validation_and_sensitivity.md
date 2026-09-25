# 09. Validation & Sensitivity

## 1. Strain-Electrical Coupling

Ge=50%, FR=0에서 Strain_Impact ON/OFF를 비교해 응력의 전기적 효과가 실제 SDevice 계산에 반영되는지 확인했다.

팀 baseline 문서에는 IdSat_norm이 ON/OFF 사이에서 약 +227% 차이를 보였다고 기록되어 있다.

## 2. FR Geometry Validation

FR=15 nm test structure를 실제 실행하고 baseline과 cutline을 비교해 요청한 15 nm 추가 recess가 구조에 반영됐는지 좌표 기반으로 확인했다.

## 3. Independent Re-Run

동일 조건 4쌍을 독립 재실행했고 기록상 편차는 0.0%였다.

## 4. Strain_Impact ON/OFF FR Sweep

Ge=50%, FR 0→35 nm:

| Metric | Strain ON | Strain OFF |
|---|---:|---:|
| SSlin change | +44% | +31% |
| DIBL change | +64% | +21% |
| Ioff change | +43,497% | +4,136% |
| IdSat change | +17% | +14% |

strain coupling을 꺼도 deep-FR degradation이 크게 남았다.

따라서 팀은 깊은 recess로 인한 geometry/electrostatic change를 1차 원인으로 보고, strain/band-structure effect가 leakage를 추가 증폭하는 것으로 해석했다.

## 5. Fin-Width Sensitivity

Wfin 15 → 7.5 nm 보조 검증에서는 얕은 FR에서 SS/DIBL과 STE가 개선됐지만, 깊은 FR에서는 오히려 전기적 특성이 크게 악화됐다.

따라서 미세화될수록 FR upper limit가 더 엄격해질 수 있다는 보조 결론을 얻었다. 이 결과는 두 fin-width 조건에 한정하며 일반 scaling law로 확장하지 않는다.
