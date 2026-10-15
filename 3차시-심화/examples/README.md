# 3차시 완성 예시 파일

| 파일 | 설명 | 쓰는 곳 |
|---|---|---|
| [.claude/agents/code-bug-analyzer.md](.claude/agents/code-bug-analyzer.md) | 읽기 전용 코드 리뷰 에이전트 | 3차시 ① |
| [.claude/agents/product-manager-prd.md](.claude/agents/product-manager-prd.md) | 기획: PRD 작성 | 3차시 ② |
| [.claude/agents/backend-architect.md](.claude/agents/backend-architect.md) | 백엔드 개발 | 3차시 ② |
| [.claude/agents/frontend-developer.md](.claude/agents/frontend-developer.md) | 화면 개발 | 3차시 ② |
| [.claude/agents/qa-engineer.md](.claude/agents/qa-engineer.md) | 테스트와 품질 보증 | 3차시 ② |
| [.claude/agents/ai-integration-specialist.md](.claude/agents/ai-integration-specialist.md) | 오픈라우터 AI 연동 | 3차시 ② |
| [graph/refund_graph.py](graph/refund_graph.py) | 그래프 엔지니어링 환불 처리 예제 | 3차시 ⑥ |

**에이전트 파일 쓰는 방법**: 실습 폴더의 `.claude/agents/` 안에 복사하면 그 프로젝트에서 바로 쓸 수 있습니다. 모든 프로젝트에서 쓰려면 내 홈 폴더의 `.claude/agents/`(Windows: `C:\Users\내이름\.claude\agents\`)에 복사합니다.

에이전트 파일의 구조는 다음과 같습니다.

```markdown
---
name: 에이전트 이름 (필수)
description: 언제 쓰는지 (필수, 클로드가 이걸 보고 어떤 에이전트를 부를지 판단)
tools: 쓸 수 있는 도구 (선택, 빼면 모든 도구 사용)
model: 사용할 모델 (선택, 빼면 메인 대화와 같은 모델)
---
에이전트에게 주는 지시문
```

강의에서처럼 말로 설명해서 만들면 클로드 코드가 이 파일을 대신 써 줍니다. 여기 있는 파일은 결과를 비교해 볼 수 있는 예시입니다.
