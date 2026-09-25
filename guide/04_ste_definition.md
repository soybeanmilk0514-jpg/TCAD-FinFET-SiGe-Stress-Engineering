# 04. Stress Transfer Efficiency

## Final Definition

STE = |stress_GPa| / (180 × 0.042 × x)

where:

- x = Ge mole fraction
- stress_GPa = SlFin_MPa / 1000
- SlFin = ChFin 영역의 채널 길이 방향 체적평균 응력
- 180 GPa = 프로젝트에서 고정해 사용한 기준 이축탄성계수
- 0.042 = Ge 조성에 대한 격자 mismatch 선형 계수

## Why Volume-Averaged Stress?

초기에는 두 응력 추출법을 함께 수집했다.

1. ChFin 체적평균 SlFin
2. gate-interface 인접 단일점 SlFin_pt

최종 데이터에서 체적평균 SlFin은 다섯 Ge 조건 각각에서 gmSat과 +0.95 이상의 상관을 보였지만, 단일점 방식은 평균적으로 음의 상관을 보였다.

따라서 최종 STE 분자는 체적평균 SlFin으로 확정했다.

## Important Limitation

이 STE는 실제 SiGe stressor 내부의 물리적 응력 대비 절대 전달률이 아니다.

Ge 조성에 비례하는 명목 응력으로 정규화한 비교 지표이며, 특히 같은 Ge 조건에서 FR 변화에 따른 전달 경향을 비교하는 데 사용했다.
