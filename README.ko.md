# 사업계획서 작성 가이드

> 🇺🇸 [English README](./README.md)

**VC 등급 사업계획서 작성 가이드 — YC, Sequoia, a16z 프레임워크를 단일 11절 표준으로 통합.**

## 사전 요구사항

- **Obsidian Vault** — 문서 저장 위치로 참조되는 Vault 경로
- **Claude Cowork 또는 Claude Code** 환경

## 목적

서로 다른 VC는 사업계획서를 다르게 읽습니다. BP-Guide는 세 가지 읽기 패턴을 통합한 11절 통합 프레임워크로, 전체 생태계 투자자 기대를 다룹니다. 단일의 잘 쓴 계획서는 모든 곳에서 작동합니다.

## 사용 시점 및 방법

투자자 대상 사업계획서, 피치덱, 전략 개요 작성 시 이 스킬을 사용하세요. 구조: 30초 스캔 계층 → 3분 체크 계층 → 10분 심화 읽기 계층. 각 절은 명확한 성공 기준과 작성 패턴을 가집니다.

## 사용 예시

| 상황 | 프롬프트 | 결과 |
|---|---|---|
| Seed 투자 피치 | `"bp-guide: Y Combinator용 사업계획서 작성"` | YC 최적화 11절 프레임워크; 제목→성과 강조 |
| Series A 투자 | `"Sequoia 피치용 SaaS 사업계획서"` | Sequoia 서사 깊이 맞춤; GTM·단위경제 심화 절 |
| 인수 포지셔닝 | `"bp-guide: 전략 인수 협상 위치"` | 11절 전략 적합성·기술 차별성·매출 지표 강조 |

## 핵심 기능

- YC, Sequoia, a16z 최고의 사례 통합 11절 통합 프레임워크
- 3계층 읽기 구조: 30초 스캔, 3분 체크, 10분 심화 읽기
- 투자자 읽기 패턴 내장: 초기 절에 제목과 성과 강조
- 각 절 성공 기준과 실제 사례

## 연관 스킬

- **[financial-model](https://github.com/jasonnamii/financial-model)** — bp-guide 절은 financial-model 산출물 통합
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill은 사업 강점 진단; bp-guide는 투자자 대상 구조화
- **[deliverable-engine](https://github.com/jasonnamii/deliverable-engine)** — deliverable-engine은 계획서를 폴리시된 PDF 또는 피치덱으로 포맷

## 설치

```bash
git clone https://github.com/jasonnamii/bp-guide.git ~/.claude/skills/bp-guide
```

## 업데이트

```bash
cd ~/.claude/skills/bp-guide && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용할 수 있습니다.

## Cowork 스킬 생태계

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT 라이선스 — 자유롭게 사용, 수정, 공유하세요.