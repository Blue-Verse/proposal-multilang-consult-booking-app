# 외국인 대상 다국어 지원 상담 및 예약 플랫폼 앱(MVP) — 제안 분석 로그

> 생성일: 2026-05-12
> 공고 URL: https://www.wishket.com/project/155264/

## 1. 공고 파싱 결과

```yaml
job:
  title: "외국인 대상 다국어 지원 상담 및 예약 플랫폼 앱(MVP) 구축"
  category: "개발/디자인/기획 · Android · iOS · 기타(IT 서비스 구축)"
  budget_range: "30,000,000원 (예상 / 평균 29,000,000 / 최저 28,000,000)"
  duration: "90일"
  tech_stack:
    - "Flutter 또는 React Native (제안 요망)"
    - "Node.js 또는 Spring Boot (제안 요망)"
    - "Google Cloud Translation API"
  description: |
    법무법인 소속 외국인센터에서 운영할 외국인 대상 다국어 지원 상담 및 예약 플랫폼 앱(MVP) 구축.
    국내 거주 외국인의 언어 장벽을 해소하기 위한 전용 플랫폼.
    내부 IT 인력 부재 → 기획·디자인·개발 턴키 수행 요구.
    아랍어 포함 최소 7개국 언어 지원 + 번역 API 비용 최적화 + 연내 런칭 목표.
  requirements:
    - "이메일/SNS 회원가입 및 외국인/상담사/관리자 3단계 권한 분리"
    - "분야별 상담 카테고리 + 텍스트/이미지 첨부 문의"
    - "상담사별 캘린더 예약, 타임존 자동 변환"
    - "예약 확정/취소/변경 알림"
    - "최소 7개국 언어 + 아랍어 RTL 완벽 대응"
    - "고정 UI 사전 리소스, 사용자 콘텐츠는 버튼 클릭 시 API 호출"
    - "번역 결과 서버 캐싱(원문 해시 키)"
    - "관리자 회원/문의/신고/블라인드 운영 기능"
    - "iOS/Android 크로스플랫폼 동시 출시"
    - "개인정보 보호법 준수, API 키 보안 관리"
  client_questions: []
  deadline: "2026-05-26"
  job_post_url: "https://www.wishket.com/project/155264/"
  urls: []
  images: []
  priority:
    - "1순위: 산출물 완성도"
    - "2순위: 금액"
    - "3순위: 일정 준수"
  out_of_scope:
    - "실시간 채팅"
```

## 2. URL/이미지 분석

참고 URL/이미지 없음. 공고 본문에 외부 참고 링크 및 첨부 이미지가 포함되어 있지 않았습니다.

## 3. 실현 가능성 분석 (내부용)

- 프로젝트 유형: **모바일 앱(Flutter)** + 어드민 웹(Next.js) + BE — "조건부 가능" + 모바일 버퍼 +20%
- 기본 공수 (AI 보조 전):
  - 기획/PRD/IA: 8 M/D
  - Figma 디자인 (앱 + 어드민): 15 M/D
  - 앱 FE 개발 (Flutter): 35 M/D
  - 어드민 FE 개발 (Next.js): 15 M/D
  - BE 개발 (NestJS): 30 M/D
  - 다국어/번역 캐싱: 8 M/D
  - DevOps/배포: 6 M/D
  - QA/테스트: 8 M/D
  - **합계: 125 M/D**
- AI 보조 반영 (가중 평균 절감 50%): 62.5 M/D
- 모바일 버퍼 +20%: 75 M/D
- 달력 일수 환산: 75 × 7/5 ≈ **105일**
- 클라이언트 예상: **90일**
- 차이: 15일 (17% 초과) → **20% 이내 → 클라이언트 기간(90일) 그대로 제안**, 스코프(실시간 채팅 제외) 및 단계별 마일스톤으로 일정 보호
- 판정: **지원 가능**. 산출물 완성도 1순위에 맞춰 단계별 데모/산출물 패키지 전략으로 대응

## 4. 포트폴리오 매칭

매칭 가이드 (모바일 앱 + 다국어 + 예약 + 크로스플랫폼):

| 순위 | 프로젝트 | 매칭 점수 | 근거 |
|------|----------|----------|------|
| 1 | **Connectin** | ★★★★★ | Flutter 크로스플랫폼 + 베트남어 등 다국어 + 3개월 풀 딜리버리 + 마이크로서비스 BE + RBAC |
| 2 | **Calendar Share** | ★★★★★ | Flutter + 캘린더 기반 시간 관리 + 7종 알림 디스패처 + Firebase/Supabase BE |
| 3 | **Pilates App** | ★★★★☆ | React Native + 예약/캘린더 + 회원/강사/관리자 3단계 권한 + Android/iOS/Web 동시 출시 |
| 4 | Harmony Link | ★★★★☆ | Flutter + NestJS + 멀티 플랫폼 + 보호자 커뮤니케이션 (보조 사례) |
| 5 | Fortune App | ★★★☆☆ | Flutter + 다국어(한/영) + 3개월 빠른 딜리버리 (보조 사례) |

추천 3개: Connectin · Calendar Share · Pilates App.

## 5. 최종 제안 요약

- 지원 금액: **27,000,000원 (VAT 별도)** — 클라이언트 예상의 90% 적용
- 지원 기간: **90일** — 클라이언트 희망 기간 수용, 단계별 마일스톤 6회로 산출물 1순위 보호
- 핵심 제안 포인트:
  1. 번역 API 3중 캐싱(정적 리소스 / 명시적 버튼 호출 / PG+Redis 영속) → 동일 원문 재호출 0건
  2. 아랍어 RTL 완전 대응(Directionality + intl, 폼/이미지/숫자 표기 포함)
  3. RBAC 3단계 권한 + 별도 Next.js 어드민(운영 효율 + 보안 분리)
  4. 마일스톤 종료 시 산출물 패키지 단계 인수인계 → 1순위(산출물 완성도) 충족
- 범위 외 명시: 실시간 채팅, 결제, 자동 통역(STT/TTS), 마케팅 도구 → 일정/비용 안정성 확보

## 6. 최종 산출물 (8단계 출력 전문)

### 6-1. 제안서 사이트 URL

```
https://proposal-router.claude-ai-b27.workers.dev/proposal-multilang-consult-booking-app/
```

### 6-2. 지원 금액

```
27,000,000원
```

> 산정 근거: 클라이언트 예상 금액(30,000,000원)의 90% 적용. VAT 별도.

### 6-3. 지원 기간

```
90일
```

> 기간 근거: 클라이언트 희망 기간 90일 수용. 6개 마일스톤(M1~M6)으로 분할하여 산출물 완성도(1순위)를 보호하며, 실시간 채팅 등 명시된 범위 외 항목을 고정하여 일정 안정성 확보.

### 6-4. 클라이언트 질문 답변

해당 없음 (공고 내 클라이언트 별도 질문 없음).

### 6-5. 지원 내용

안녕하세요, 외국인 대상 다국어 지원 상담 및 예약 플랫폼 앱(MVP) 구축 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-multilang-consult-booking-app/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- 법무법인 외국인센터용 다국어(7개국, 아랍어 RTL 포함) 상담·예약 모바일 플랫폼(MVP) 턴키 구축
- 핵심 도전 과제: ① 번역 API 비용 폭증 방지(캐싱 아키텍처), ② 아랍어 RTL 완전 대응, ③ 외국인 사용자·상담사·관리자 3단계 권한 분리, ④ iOS/Android 동시 출시, ⑤ 90일 내 연내 런칭
- 우선순위 1순위(산출물 완성도) 충족을 위해 마일스톤 종료마다 산출물 패키지 인수인계 정례화
- 명시된 범위 외(실시간 채팅) 고정으로 일정/비용 안정성 확보

■ 작업 일정

[Phase 1] Day 1–14 — 기획/설계
- 요구사항 정의서, IA, 화면 설계서, ERD, API 명세서, 다국어 정책 문서

[Phase 2] Day 15–28 — UI/UX 디자인
- 앱·어드민 Figma 디자인 원본, 아랍어 RTL 가이드, 다국어 글자 변동 가이드

[Phase 3] Day 29–60 — 코어 개발
- 인증/RBAC, 상담 문의, 캘린더 예약(타임존 자동 변환), 다국어 리소스, 번역 프록시 + 3중 캐싱, 관리자 1차

[Phase 4] Day 61–75 — 운영 기능 + 알림
- 신고/차단/블라인드 워크플로우, FCM 푸시 + 이메일 다국어 템플릿, 베타 빌드

[Phase 5] Day 76–85 — QA/검수
- 기능·회귀 QA, 7개 언어 + 아랍어 RTL 검수 체크리스트, 결함 우선순위별 수정

[Phase 6] Day 86–90 — 출시/인수인계
- App Store/Play Store 심사 대응 및 출시, 산출물 패키지 + 관리자 매뉴얼 인수인계

■ 마일스톤 및 산출물
- M1 (Day 14): 기획 산출물 승인
- M2 (Day 28): Figma 디자인 완성본 승인
- M3 (Day 60): 코어 기능(인증/상담/예약/번역 캐싱) + 어드민 1차 완료
- M4 (Day 75): 운영 기능(차단/신고/블라인드) + 알림 통합 + 베타 빌드 제공
- M5 (Day 85): QA 완료, RTL/다국어 검수 통과
- M6 (Day 90): 스토어 출시 + 인수인계 패키지(요구사항 정의서, 화면 설계서, 디자인 원본, 소스 코드, ERD, API 명세서, 관리자 매뉴얼)

■ 미팅 시 협의 필요 사항
- 지원 7개 언어 최종 선정 (영/러/베/몽/아랍 + 한국어 + 1종 등)
- BE/인프라 선정 (NestJS + GCP Cloud Run 권장 vs AWS ECS)
- SNS 로그인 범위 (Google/Apple 필수, Kakao 등 추가 여부)
- 다국어 고정 텍스트 번역본 제공 일정 및 포맷(엑셀/ARB)
- 월 단위 유지보수 범위 및 단가 (출시 이후)
- App Store/Play Store 개발자 계정 보유 여부 및 등록 명의

---

<유사 프로젝트 진행 경험>

▶ Connectin — 디지털 명함 & 네트워킹 플랫폼 (2025.05~2025.08, 3개월)
- 프로젝트 유형: 크로스플랫폼 모바일 앱 + 마이크로서비스 BE (베트남 시장 진출)
- 핵심 기능: Flutter iOS/Android 동시 출시, 다국어 UI, OCR 명함 스캔, BLE 근거리 탐색, E2E 암호화
- 유사점: Flutter 단일 코드베이스로 iOS/Android 동시 출시, 다국어 적용, RBAC, 3개월 풀 딜리버리 — 본 공고와 동일한 출시 전략·일정
- 기술 스택: Flutter, Dart, Next.js, Express, TypeScript, PostgreSQL, 마이크로서비스

▶ Calendar Share — 소셜 캘린더 앱 (2025.01~, MVP)
- 프로젝트 유형: B2C Flutter 앱 + 캘린더/소셜 융합
- 핵심 기능: 캘린더 기반 일정 등록/공유, 7종 알림 디스패처, QR 디스커버리, Firebase + Supabase 듀얼 백엔드
- 유사점: 캘린더 기반 시간 관리 UI + 타임존 처리 + 알림 디스패처 — 본 공고의 상담사 캘린더 예약·확정/취소/변경 알림 도메인 직결
- 기술 스택: Flutter, Firebase, Supabase, Provider, FCM

▶ Pilates App — 필라테스 프랜차이즈 관리 (2019.09~2019.12, 4개월)
- 프로젝트 유형: B2B2C 예약·관리 앱 (Android/iOS/Web 동시 출시)
- 핵심 기능: 수업 예약, 강사 캘린더, 출결/CRM, 회원·강사·관리자 3단계 권한 분리, 3 플랫폼 동시 출시
- 유사점: 예약 시스템 + 가용 시간 캘린더 + 3단계 권한 + 모바일 + 관리자 웹 동시 출시 — 본 공고의 도메인 구조와 동일 패턴
- 기술 스택: React Native, React, Node.js, JavaScript

---

<사용 기술과 툴>

▶ 개발 기술
- Frontend (App): Flutter (Dart) — 단일 코드베이스 iOS/Android 동시 출시
- Admin Web: Next.js + TypeScript
- Backend: NestJS (TypeScript) — 모듈러 아키텍처
- DB: PostgreSQL (메인) + Redis (번역 캐시/세션)
- 외부 API: Google Cloud Translation API v3 (BE 프록시 + 3중 캐싱)
- 알림: Firebase Cloud Messaging (Push) + 이메일(SES/SendGrid)
- 보안: JWT + 리프레시 토큰, HTTPS, Secret Manager 기반 API 키 관리

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions
- 클라우드: GCP (Cloud Run + Cloud SQL) 또는 AWS (ECS + RDS) — 협의 후 결정
- 컨테이너: Docker

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues

### 6-6. 관련 포트폴리오 추천

1. **Connectin** — Flutter 크로스플랫폼 + 다국어 + 마이크로서비스 BE, 3개월 풀 딜리버리 경험 (본 공고의 출시 전략·일정과 동일)
2. **Calendar Share** — Flutter 캘린더 기반 시간 관리 + 타임존 처리 + 7종 알림 디스패처 (예약/알림 도메인 직결)
3. **Pilates App** — 예약 시스템 + 강사 캘린더 + 회원·강사·관리자 3단계 권한 + 3 플랫폼 동시 출시 (도메인 구조 동일)
