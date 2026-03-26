# Agent-Driven Development Workflow

이 프로젝트는 AI 에이전트를 활용한 단계별 개발 워크플로우를 따릅니다.

## Workflow Stages

1. **Research** (`/project:research`) — 코드베이스를 분석하고 `docs/knowledge/`에 문서화
2. **Plan** (`/project:plan`) — 구현 계획을 수립하고 `docs/plan.md` 생성
3. **Code** (`/project:code`) — 승인된 계획에 따라 구현 (Teams: 서브에이전트 활용 가능)
4. **Close** (`/project:close`) — 작업 아카이빙, knowledge 갱신, 커밋 준비

## Core Principles

- 현재 단계에서 허용된 작업만 수행할 것
- 분석(사고)을 먼저 하고, 그 다음에 문서/코드를 작성할 것
- `docs/` 디렉토리를 포함하는 곳을 프로젝트 루트로 취급할 것
- 프로젝트 루트 바깥의 파일을 읽거나 수정하지 말 것

## Key Files

- `docs/task_goal.md` — 현재 작업 목표
- `docs/plan.md` — 구현 계획 (plan 단계에서 생성)
- `docs/exec_log.md` — 실행 로그 (code 단계에서 생성)
- `docs/knowledge/` — 코드베이스 분석 결과 (research 단계에서 생성)
- `docs/commits/` — 완료된 작업 아카이브

## Commands

- 각 단계별 슬래시 커맨드: `/project:research`, `/project:plan`, `/project:code`, `/project:close`
- Code 단계에서 Teams 서브에이전트 활용: `researcher`, `planner`, `coder` agents 사용 가능
