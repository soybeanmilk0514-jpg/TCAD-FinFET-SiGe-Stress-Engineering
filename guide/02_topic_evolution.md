# 02. Topic Evolution

이 프로젝트는 처음부터 FinFET SiGe 주제로 시작한 것이 아니다.

팀은 GAA-TFET, 도핑 기반 GAA, DRAM BCAT 등 여러 후보를 검토했고, 구현 가능성·최근 연구 중복·최근 실제 경진대회 수상작과의 겹침을 확인하면서 주제를 여러 차례 변경했다.

최종적으로 FinFET + Embedded SiGe Source/Drain 응력공학을 선택한 이유는 다음과 같다.

1. 기존 FinFET 구조에 실제 공정 변화인 Embedded SiGe S/D를 추가할 수 있었다.
2. Ge 조성과 recess depth라는 서로 다른 공정·구조 변수를 함께 분석할 수 있었다.
3. 단순히 최대 성능점을 찾기보다 응력 전달과 전기적 비용의 2차원 trade-off를 보여줄 수 있었다.
4. Synopsys FinFET 예제를 기반으로 제한된 기간 안에 TCAD 구현과 반복 계산이 가능했다.

초기에는 People–Bean / Luryi–Suhir 기반 defect boundary를 핵심으로 삼으려 했으나, baseline fin 치수에서 원하는 판별력이 나오지 않아 이 접근은 폐기했다.

이후 연구 질문을 Stress Transfer Efficiency와 전기적 trade-off로 다시 정의했다.

이 과정은 결과 자체보다도, 문헌 검색 요약을 그대로 믿지 않고 실제 논문·특허·최근 수상작과 대조해 연구 질문을 수정한 경험으로 정리할 수 있다.
