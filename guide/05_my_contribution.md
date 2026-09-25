# 05. My Contribution — Subin Joo

## Main TCAD Responsibility

팀 최종 역할 분담 기준으로 본 5×5 DoE에서 Ge 30%, 40% 두 열을 담당했다.

| Ge | FR |
|---:|---|
| 30% | 0 / 10 / 20 / 30 / 35 nm |
| 40% | 0 / 10 / 20 / 30 / 35 nm |

총 10개 핵심 조건을 직접 실행하고 결과 CSV를 정리했다.

원본 subset은 [results/subin_doe.csv](../results/subin_doe.csv)에 보존했다.

## Example Trends From My Runs

Ge=30%:

- stress magnitude: 1.346 GPa at FR=0 → approximately 1.52–1.54 GPa at FR=20–35
- STE: 0.593 at FR=0 → 0.672 at FR=20 → near saturation afterward
- SSlin: 80.4 mV/dec at FR=0 → 123.8 mV/dec at FR=35
- Ioff_norm: 1.07e-10 → 1.23e-7

Ge=40%:

- stress magnitude: 1.801 GPa at FR=0 → approximately 2.02–2.03 GPa at deep FR
- STE: 0.596 at FR=0 → 0.667 at FR=20 → near saturation afterward
- SSlin: 79.4 mV/dec at FR=0 → 117.6 mV/dec at FR=35
- Ioff_norm: 1.30e-10 → 1.05e-7

이 저-Ge 데이터만으로도 FR 약 20 nm 이후 응력 전달 이득이 작아지는 반면 전기적 손실은 계속 커지는 경향을 확인할 수 있다.

## Other Recorded Work

- low-Ge Ge-only sweep
- SVisual StressZZ field comparison using a common display scale
- team baseline and result-review participation
- final presentation storyline integration was assigned during the project; this repository only claims completed work that is supported by stored data

## Team Credit

25점 전체 데이터, STE 정의 확정, 추가 검증, 회귀 분석 및 최종 결론은 팀 공동 결과다. 본 저장소는 그 팀 결과와 개인 실행 범위를 구분해서 표시한다.
