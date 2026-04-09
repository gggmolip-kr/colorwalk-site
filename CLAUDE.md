# 이김푸딩게임즈 작업 규칙

## 작업 기록 (필수)
작업 완료 시, 아래 명령어로 LEEKEEMPUDDING 일지에 기록:

```bash
gh workflow run "오늘 기록 추가" -R gggmolip-kr/LEEKEEMPUDDING -f message="[프로젝트명] 작업 내용" -f status="완료"
```

- 상태값: 완료 / 진행중 / 보류
- 예시: `gh workflow run "오늘 기록 추가" -R gggmolip-kr/LEEKEEMPUDDING -f message="[색감채집] 랜딩페이지 3개국어 수정 완료" -f status="완료"`

## 주의
- LEEKEEMPUDDING 저장소 파일을 직접 수정하지 말 것 (충돌 방지)
- 반드시 GitHub Actions 워크플로우를 통해 기록할 것
- `gh auth status`에서 gggmolip-kr 계정이 활성화되어 있는지 확인. 아니면 `gh auth switch --user gggmolip-kr` 실행

## 판단 기준
- 완성도보다 출시 속도 우선 (MVP 마인드)
- 마케팅 없는 개발은 절반짜리
- "이게 장기 목표에 가까워지는 작업인가?"
