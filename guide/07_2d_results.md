# 07. 2-D Results

## Absolute Channel Stress

25점 회귀 결과에서 절대 응력은 Ge 조성의 영향이 가장 컸다.

- Ge coefficient t = -61.78
- FR coefficient t = -7.97
- Ge×FR interaction t = -1.57
- R² = 0.9947

FR=0에서 Ge 30→70%:

- |channel stress|: 1.346 → 3.210 GPa
- IdSat_norm: about +34%
- gmSat: about +19%
- SSlin: 80.4 → 76.6 mV/dec
- DIBL: 89.3 → 69.3 mV/V
- Ioff_norm: about 5.6× increase

## Stress Transfer Efficiency

STE regression:

- Ge main effect t = 0.32
- FR main effect t = 8.41
- Ge×FR interaction t = -0.82

따라서 정규화된 전달 효율의 주된 변화축은 FR이었다.

25점 STE 지도에서는 모든 Ge 조건에서 FR=0→20 nm 구간의 증가가 뚜렷했고, 20 nm 이후에는 0.67 부근에서 거의 포화했다.

## Interpretation

Ge는 주로 stressor의 입력 강도를 바꾸는 재료 변수로, FR은 그 응력이 채널에 얼마나 전달되는지를 바꾸는 구조 변수로 해석했다.

다만 전기적 최적화에서는 두 변수를 독립적으로 볼 수 없으며, 특히 깊은 FR에서 누설 및 정전제어 손실을 함께 확인해야 한다.
