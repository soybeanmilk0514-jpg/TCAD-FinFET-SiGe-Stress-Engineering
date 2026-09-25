# 10. Limitations, Competition Outcome & Lessons

## Competition Outcome

이 프로젝트는 3단계 심사 과정 중 1차 심사를 통과해 2차 심사까지 진출했지만, 2차 심사에서 탈락하여 수상하지 못했다.

포트폴리오에서는 이를 수상 프로젝트처럼 표현하지 않는다.

## Technical Limits

- Ge range: 30–70%
- FR range: 0–35 nm
- 범위 밖 수치 외삽 금지
- STE 절대값은 M = 180 GPa 가정에 의존
- coherent SiGe epitaxy 가정
- 실제 고-Ge SiGe의 strain relaxation과 crystal defect는 직접 포함하지 않음
- FR 15–20 nm는 이 TCAD 구조와 입력 조건에 대한 design window
- spatial leakage path를 직접 특정한 것은 아님
- fin-width sensitivity는 Wfin 15 / 7.5 nm, Ge 60 / 70%의 보조 분석
- FinFET 결과를 GAA 수치에 직접 적용하지 않음

## Process Lessons

### 1. Maximum stress is not the same as best device design

응력을 가장 크게 만드는 조합보다, 추가 이득의 포화와 electrical penalty의 시작점을 함께 보는 것이 더 공정 설계에 가깝다.

### 2. Verification changed the research question

초기 defect-boundary 프레이밍은 실제 baseline에서 판별력이 부족해 폐기했다. 결과에 맞춰 결론만 바꾸는 것이 아니라 연구 질문 자체를 다시 정의했다.

### 3. Literature verification mattered

프로젝트 과정에서 AI 검색 요약이 서로 다른 소자·논문·특허 메커니즘을 혼합한 사례를 직접 찾아 정정했다. 최종 보고서에는 원문 검증이 끝난 문헌만 사용했다.

### 4. Collaboration requires a shared data standard

세 명이 같은 TCAD 조건을 병렬 실행했기 때문에, common baseline, naming rule, automated merge, and cross-validation이 결과 신뢰성에 중요했다.
