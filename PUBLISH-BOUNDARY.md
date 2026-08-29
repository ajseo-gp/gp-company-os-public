# Public Knowledge Boundary

## 목적

회사 내부 운영지식과 외부 교육·마케팅 자료의 경계를 분리한다.

공개 자료는 내부 원본의 복사본이 아니라 **검토된 파생물(public derivative)** 이어야 한다.

## 분류

### 공개 가능

- AI Native Company의 일반 원칙
- Context / Decision / Knowledge / SOP의 개념적 차이
- BOOT → THINK → DECIDE → EXECUTE → VERIFY → LEARN 루프
- 사람과 AI의 역할 분담 원칙
- 가상의 예제 데이터와 일반화된 사례
- 공개해도 회사의 현재 운영상태나 경쟁우위를 직접 노출하지 않는 구조도

### 일반화 후 공개 가능

- 내부에서 검증한 운영 사례
- 실패와 개선의 패턴
- Agent 운영 경험
- 업무 자동화 전후의 구조적 변화

이 경우 실제 회사명·고객명·수치·처방·경로·인프라 상세를 제거하고 원리를 중심으로 다시 작성한다.

### 내부 전용

- 현재 회사 전략과 우선순위의 구체적 세부
- 실제 고객·문의·계약 정보
- 실제 처방·함량·원가·마진·단가
- 장비 IP, 계정, 인증, 네트워크와 Runtime 접속 정보
- 미공개 R&D 결과와 지원과제의 민감한 원본 데이터
- 실제 장애 복구 경로, credential, 비밀 운영 로그
- 외부에 공개되지 않은 Decision 및 현재 Handoff

## Publish Flow

```text
Private Company Authority
        ↓
Public Candidate
        ↓
Generalize / De-identify
        ↓
Security & Business Review
        ↓
Public Derivative
        ↓
Education / Content / Consulting
```

## 금지

- private repository를 단순 mirror해서 public으로 공개하지 않는다.
- 내부 파일 경로와 제목만 바꿔 공개하지 않는다.
- 미검증 Working Context를 회사의 확정 방법론으로 표현하지 않는다.
- 공개 목적 때문에 내부 권위 원본의 구조를 왜곡하지 않는다.
