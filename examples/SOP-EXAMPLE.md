# SOP Example — AI 작업 시작 전 Context 확인

## 목적

AI가 과거 대화 기억이나 추측으로 작업을 시작하지 않도록 한다.

## Trigger

중요한 신규 작업 또는 기존 작업 재개 시.

## Inputs

- 사용자 요청
- 관련 Context
- 승인된 Decision
- 최근 Handoff

## Procedure

1. 요청의 Domain과 Intent를 분류한다.
2. 필요한 최소 Context만 조회한다.
3. 확정 사실과 가설을 분리한다.
4. 현재 실행 가능한 다음 한 단계를 정한다.
5. 승인 필요 여부를 확인한다.
6. 실행 후 결과와 Evidence를 기록한다.
7. 새로운 학습 또는 다음 Handoff를 남긴다.

## Output

- 현재 목표
- 현재 상태
- 다음 한 단계
- 판단이 필요한 예외

## Failure Handling

- Context가 충돌하면 임의로 선택하지 않는다.
- 최신 상태를 확인할 수 없으면 확정된 것처럼 보고하지 않는다.
- 실행 범위 밖의 새 아이디어는 별도 후보로 분리한다.
