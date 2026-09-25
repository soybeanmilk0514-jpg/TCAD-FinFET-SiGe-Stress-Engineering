# 01. Project Overview

## Final Research Question

FinFET pMOS의 Embedded SiGe Source/Drain에서 투입되는 응력 중 실제 Fin 채널까지 전달되는 정도는 얼마이며, Ge 조성과 S/D fin recess depth(FR) 중 어떤 변수가 그 전달 효율과 전기적 trade-off를 지배하는가?

## Why Two Variables?

Ge 조성은 SiGe stressor가 만들어내는 절대 응력의 크기를 바꾸고, FR은 stressor가 채널에 접근하는 구조적 위치를 바꾼다.

따라서 하나의 파라미터만 최적화하는 대신 Ge × FR 2차원 설계공간을 만들고, 각 점에서 다음을 함께 비교했다.

- channel longitudinal stress
- Stress Transfer Efficiency
- gmSat
- IdSat_norm
- SSlin
- DIBL
- Ioff_norm

## Core Outcome

본 구조에서는 절대 채널 응력은 Ge 증가에 크게 반응했고, 같은 Ge에서 정규화한 STE는 FR 약 20 nm까지 빠르게 증가한 뒤 포화했다. 반면 깊은 FR에서는 SSlin, DIBL, Ioff 손실이 계속 커졌다.

최종 팀 결론은 FR 약 15–20 nm를 실용 설계창으로 제시하는 것이다.
