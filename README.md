<!--
  ⚠ 공개(public) 전 반드시 "공개 전 체크리스트"(문서 맨 아래) 한 번 훑고
     민감 정보 제거 후 레포를 public 으로 전환할 것. 현재는 private.
-->

# 이동섭 (Dongsub Lee) — Backend Engineer

> 5년차 백엔드 엔지니어. 헬스케어 SaaS 도메인에서 **EMR(전자의무기록)·회원/인증·보험청구·BI**를 아우르며,
> 서버리스 기반 멀티테넌트 백엔드를 설계·운영해 왔습니다.
> 백엔드를 중심으로 프론트·데스크탑까지 대응하고, 사이드로 라이브 서비스를 직접 만들어 운영합니다.

- 💻 GitHub: [@lds6210](https://github.com/lds6210)
- 🌏 Live Project: [sente.life](https://sente.life)
- ✉️ Email: <lds6210@naver.com>
- 📍 Korea

---

## About

- **2021.10 ~ 현재**, 의료 IT 기업에서 헬스케어 SaaS 백엔드를 담당
- 한의원 **EMR(전자의무기록)** 을 메인으로, 회원·인증·보험청구·BI 등 **다수 서비스의 백엔드를 횡단**하며 개발·운영
- **AWS Lambda(Serverless Framework) 기반 멀티테넌트 아키텍처** 설계·구현·장애 대응
- **신규 시스템을 0→1로 구축**(통합 인증·BI 백엔드)하고, **레거시 아키텍처 전환**(컨테이너→서버리스)도 수행
- 백엔드 주력 + 필요 시 **프론트(Vue/Next)·데스크탑(Electron/Rust)** 까지 풀스택 대응
- 의료 현장의 무중단·데이터 정합성을 최우선으로 하는 **신중한 배포 문화**에 익숙

---

## 기술 스택

**Languages** `TypeScript` · `JavaScript` · `Python` · `Rust` · `SQL`

**Backend** `Node.js` · `Fastify` · `Serverless Framework` · `AWS Lambda` · `API Gateway` · `REST`

**Database / ORM** `MySQL` · `DynamoDB` · `Drizzle ORM` · `Kysely` · 대규모 마이그레이션·정합성

**Infra / DevOps** `AWS (Lambda, S3, CloudFront, Cognito/SSO, Lambda Layers)` · `Cloudflare` · `Docker` · `Bitbucket Pipelines (CI/CD)`

**Frontend / Desktop** `Vue` · `Next.js / React` · `Electron` · `PWA`

**Observability** `Sentry` · `CloudWatch` · `Redash`

---

## 도메인 전문성

| 도메인 | 내용 |
|---|---|
| 🏥 **헬스케어 / EMR** | 한의원 전자의무기록 — 접수·진료·상병·처방·수납·청구 워크플로 |
| 🩺 **건강보험 / 청구** | 건강보험 자격조회, 보험청구(자동차보험 자보 포함), 외부 기관 규격 연동 |
| 🔐 **회원 / 인증** | 다중 서비스 통합 인증(SSO), 사용자 식별자 통합, 멀티테넌트 권한 |
| 📊 **BI / 운영 어드민** | 데이터 분석 백엔드, 멀티서비스 통합 운영 어드민 |
| 📨 **메시지 / 커머스** | 알림 발송, 마켓/커머스 백엔드 |

---

## 경력 타임라인

> 의료 IT 기업 · Backend Engineer · 2021.10 ~ 현재

| 시기 | 확장된 책임 범위 |
|---|---|
| **2021–2022** | 회원/인증 도메인 백엔드 — 회원 API 개발 및 **컨테이너→서버리스 전환** |
| **2023** | **보험청구 백엔드** 집중 개발(외부 기관 규격 대응) + EMR 백엔드 합류 |
| **2024** | **EMR 백엔드 본격화** + 멀티서비스 운영 어드민 |
| **2025** | EMR 핵심 개발 + **BI 백엔드·통합 인증 시스템 0→1 신규 구축** |
| **2026** | EMR 데스크탑 앱(Electron+Rust)·데이터 이관 도구·채팅 등 **다각화** |

---

## 주요 성과 (Highlights)

- **5년간 다수 서비스 백엔드를 횡단**하며 일관되게 핵심 기여 (백엔드 30+ 서비스 경험)
- **서버리스 멀티테넌트 SaaS 아키텍처** 설계·운영 — AWS Lambda + Lambda Layer 공유 런타임,
  cold start·의존성·배포 파이프라인 등 운영 함정 관리
- **0→1 구축**: 데이터 분석(BI) 백엔드와 통합 인증(SSO) 시스템을 신규로 설계·구현
  (데이터 모델링·마이그레이션·테스트·문서 동반)
- **아키텍처 전환**: 회원 도메인을 컨테이너(Docker)에서 서버리스(Lambda)로 이전
- **EMR 데스크탑 앱**: Electron + Rust 네이티브 런처, e2e 테스트, 자동 업데이트, 배포·권한(UAC) 이슈 대응
- **데이터 이관 도구**: Python 기반으로 레거시 → 자사 EMR 데이터 마이그레이션 도구 구축
- **운영 DB 마이그레이션**: 대규모 스키마·charset 전환을 검증 기반으로 무중단 수행

> ℹ️ 사내 코드·내부 스펙·고객/환자 데이터는 비공개입니다. 위 항목은 일반화된 책임·성과 범위입니다.

---

## 사이드 프로젝트

### 🌏 [sente.life](https://sente.life) — 한자 스토리로 외우는 중국어 단어 학습 (라이브 서비스)
> "글자 하나에 우주가 있다" — 한자의 유래·이야기로 중국어 단어를 외우는 학습 웹/PWA

- 한자 분해·획순 따라쓰기·병음·원어민 발음·예문·시험·하루 목표, "글자 우주" 인터랙션
- 가입 없이 5단어 맛보기 → 이메일 로그인, PWA 앱 설치 지원
- **Stack**: `Next.js (App Router)` · `React` · `Cloudflare` · `PWA` · SEO 최적화(OG/Twitter/동적 OG 이미지)
- 기획·개발·디자인·배포·운영을 **단독으로 0→1** 수행

### 🪟 [paneup](https://github.com/lds6210) — Windows Terminal 멀티 런처 (OSS, WIP)
- `wt` 멀티탭/스플릿 페인을 한 줄로 — "AI 시대의 tmex"(병렬 AI 세션 실행용)
- **Stack**: `Node.js` · Windows Terminal · MIT License
- 본인 워크플로(병렬 AI 세션) 문제를 직접 도구로 해결

---

## 연락처

- GitHub: [@lds6210](https://github.com/lds6210)
- Live: [sente.life](https://sente.life)
- Email: <lds6210@naver.com>

---

<!-- ===================== 공개 전 체크리스트 (public 전환 시 이 블록째로 검토/삭제) =====================

공개(public) 전 반드시 확인:
- [ ] 회사명/서비스명 노출 수준 최종 결정 (현재: 고용주명 미기재, 도메인 일반 서술)
- [ ] 사내 코드·내부 스펙·티켓 본문·고객/환자 데이터·시크릿이 단 한 줄도 없는지
- [ ] 내부 서비스명/저장소명 노출 여부 (현재 본문에 미포함 — 유지)
- [x] Email 채움 (lds6210@naver.com)
- [ ] NDA·근로계약상 공개 가능 범위 본인 확인
- [ ] 확인 끝나면 이 주석 블록 삭제 후 레포 public 전환

원천 데이터(비공개, 로컬): C:/Users/Admin/Desktop/옵시디언/포트폴리오/raw/
=========================================================================================== -->
