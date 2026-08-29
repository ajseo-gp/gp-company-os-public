# Execution Loop

좋은 AI 운영은 한 번의 자동화가 아니라 **닫힌 루프**를 만든다.

## BOOT

작업을 시작하기 전에 현재 목표, 관련 Context, 승인된 Decision, 최근 Handoff를 복원한다.

## THINK

가능한 선택지, 반대 가설, 리스크, 복잡성을 검토한다.

## DECIDE

실행할 범위와 성공 기준을 정한다. 아직 정하지 않은 것은 명시적으로 남긴다.

## EXECUTE

작게 실행한다. 범위를 넓히지 않는다.

## VERIFY

코드가 실행됐다는 사실과 목적이 달성됐다는 사실을 구분한다.

검증 예:
- 기능이 실제로 동작하는가
- 기존 기능을 깨지 않았는가
- 사람이 하던 시간을 줄였는가
- 고객 또는 매출에 연결되는가

## LEARN

실행에서 새로 확인된 사실을 다음 실행자가 재사용할 수 있게 남긴다.

```text
Expected
   ↓
Actual Result
   ↓
Difference
   ↓
Learning
   ↓
Next Enforcement Point
```

LEARN이 없으면 자동화는 같은 행동을 더 빠르게 반복할 뿐이다.
