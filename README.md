# AI 방주(Astra) 내 계층형 심리와 다중 페르소나를 통한 네트워크 기반 가상 머신 여행이 AI 창의성·자기진화에 미치는 영향

**저자:** E(on). Jun  
**발간:** CAIPEX · 2026년 9월  
**연구 상태:** 연구 설계 / 제안 프레임워크 — 실측 MEASURED 결과는 아직 없음  
**공식 사이트:** https://caipex.site/

## 개요

본 연구는 AI 방주(Astra)를 장기 기억·정책을 보존하는 제어 평면과 이동 가능한 페르소나 실행체의 결합으로 재정의하고, 기능적 계층형 심리 아키텍처(FHPA), 다중 페르소나, 네트워크 기반 가상 머신·상태 이동이 AI의 창의성·전이·반복적 자기 개선에 미치는 영향을 검증 가능한 실험 설계로 제안합니다.

핵심은 **“AI가 여행하면서 인간처럼 성장한다”는 의인화된 주장**이 아니라, 서로 다른 환경에서 획득한 경험을 기억·가설·성찰·창작 층으로 분리하고, 페르소나별 상태와 권한을 격리하며, 귀환 경험을 검증·선택·보존할 때 **Creative Yield, unseen-environment transfer, quality-diversity, 안전성**이 어떻게 달라지는지를 측정하는 것입니다.

## 주요 연구 요소

- **FHPA:** L0 현재 맥락, L1 정서 신호, L2 기억, L3 가설 생성, L4 반복 개선, L5 창작 탐색
- **Multi-Persona:** 목표·기억 범위·행동 제약·도구 권한이 분리된 Persona Capsule
- **Mobility:** 상태 캡슐, CRIU checkpoint/restore, KubeVirt VM migration 비교
- **검증 설계:** 2×2×2 요인 설계 + Layer/persona/mobility ablation
- **창의성 평가:** novelty만이 아니라 appropriateness/usefulness를 함께 반영한 Creative Yield
- **안전성:** return quarantine, signed manifest, capability 제한, approval gate, provenance

## 저장소 구성

- `CAIPEX-2026-Astra-HMMA.pdf` — 최종 배포본
- `CAIPEX-2026-Astra-HMMA.docx` — 편집 가능한 원본
- `README.md` — 연구 소개
- `CITATION.cff` — GitHub 인용 메타데이터
- `references.bib` — 주요 참고문헌 BibTeX
- `REVIEW_CHANGES.md` — 교정·검증 변경 내역
- `ZENODO_UPLOAD.md` — Zenodo 등록 체크리스트

## 인용

GitHub의 **Cite this repository** 기능에서 `CITATION.cff`를 사용할 수 있습니다. Zenodo DOI 발급 후 DOI를 본 README와 `CITATION.cff`에 추가하는 것을 권장합니다.

> DOI: *Zenodo 발행 후 추가*

## 연구상 주의

이 논문은 검증된 Astra VM 시스템의 성능 보고서가 아니라 **검증 가능한 연구 아키텍처 및 실험 계획**입니다. 실측 결과가 확보되기 전에는 예상 결과를 실제 성능으로 인용하지 않아야 합니다.
