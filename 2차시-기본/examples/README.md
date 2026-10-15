# 2차시 완성 예시 파일

강의에서 만드는 파일의 완성 예시입니다. 직접 만든 결과와 비교하거나, 막혔을 때 복사해 쓰세요.

| 파일 | 설명 | 쓰는 곳 |
|---|---|---|
| [CLAUDE.md](CLAUDE.md) | 퀴즈 게임 프로젝트 설명과 "퀴즈 문제 교차 검증 가이드라인" | 2차시 ①② |
| [.claude/commands/quiz-validate.md](.claude/commands/quiz-validate.md) | 커스텀 명령어 `/quiz-validate` (카테고리 인자 지원) | 2차시 ③ |
| [.claude/skills/quiz-validate/SKILL.md](.claude/skills/quiz-validate/SKILL.md) | 같은 명령어를 스킬 형식으로 만든 것 | 2차시 ③ 참고 |
| [.env.example](.env.example) | API 키 저장 형식 예시 | 2차시 ⑤ |
| [.gitignore](.gitignore) | `.env`가 깃에 올라가지 않게 하는 설정 | 2차시 ⑤ |

**쓰는 방법**: 퀴즈 게임 폴더 안에 같은 경로로 복사합니다. 예를 들어 `quiz-validate.md`는 `퀴즈게임폴더/.claude/commands/quiz-validate.md`에 둡니다. commands 방식과 skills 방식 중 하나만 두세요. 둘 다 두면 같은 이름이 겹칩니다.

`.claude`처럼 점(.)으로 시작하는 폴더는 숨김 폴더라 탐색기에서 안 보일 수 있습니다. Windows 탐색기 [보기] → [표시] → [숨긴 항목]을 켜세요.
