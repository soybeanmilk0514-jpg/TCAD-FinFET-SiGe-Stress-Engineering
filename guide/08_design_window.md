# 08. Practical FR Design Window

Ge=50%에서 FR=15 nm와 22 nm를 추가 계산해 20 nm 주변을 세분화했다.

| FR | STE | gmSat | SSlin | DIBL | Ioff_norm |
|---:|---:|---:|---:|---:|---:|
| 15 nm | 0.660 | 1.143e-4 | 82.2 | 90.7 | 5.26e-10 |
| 20 nm | 0.667 | 1.149e-4 | 84.7 | 97.3 | 9.68e-10 |
| 22 nm | 0.668 | 1.131e-4 | 87.5 | 100.0 | 1.93e-9 |

## Boundary Logic

FR 15 nm:
- STE가 Ge=50% 관측 최대값의 약 98.5%에 도달

FR 20 nm:
- STE가 관측 최대값의 약 99.6%
- gmSat 최대

FR 22 nm:
- STE 증가 거의 없음
- gmSat 감소
- Ioff 약 2배 증가

FR 30–35 nm:
- STE는 거의 변하지 않음
- SSlin, DIBL, Ioff가 빠르게 악화

## Final Proposal

본 구조의 실용 FR design window는 **15–20 nm**로 제안했다.

이것은 응력을 가장 크게 만드는 조건이 아니라, 대부분의 stress-transfer benefit을 얻으면서 전기적 penalty가 급증하기 전의 공정 구간이다.
