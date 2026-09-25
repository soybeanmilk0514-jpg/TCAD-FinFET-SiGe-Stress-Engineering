# 06. Team Analysis & Data Pipeline

팀은 세 명이 각자 TCAD 결과를 만들더라도 분석 기준이 달라지지 않도록 공통 파이프라인을 사용했다.

## Workflow

1. Sentaurus Workbench에서 각 DoE point 실행
2. SVisual / exported variables로 응력 및 전기 지표 확보
3. 팀원별 CSV를 runs 폴더에 누적
4. analysis/build.py가 데이터 형식과 단위를 통일
5. Ge mole fraction을 percent로 변환
6. FR을 nm로 통일
7. SlFin을 GPa로 환산
8. 공통 공식으로 STE 계산
9. DIBL 계산
10. 팀 결과 병합 및 교차검증
11. analysis/contour.py로 2-D maps와 2-factor interaction analysis 생성

## Data Integrity Principles

- STE를 팀원이 각자 손계산하지 않음
- raw output과 processed grid를 분리
- 추가 검증점은 본 5×5 회귀 격자에 섞지 않음
- 동일 조건 독립 재실행으로 환경 차이를 확인
- 생성된 grid/figure는 분석 파이프라인으로 재생성

본 개인 포트폴리오에는 팀 Python 코드를 개인 코드처럼 복사하지 않는다. 대신 실행 방식과 데이터 provenance를 문서화한다.
