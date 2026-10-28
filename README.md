# 📦 스마트 물류센터 온보딩 가이드 레포지토리

본 저장소는 스마트 물류창고 신규 입사자 및 현장 작업자의 빠른 적응과 안전한 현장 근무를 지원하기 위해 제작된 **온보딩 가이드북** 문서를 관리하는 프로젝트입니다.

---

## 📚 문서 구조 및 목차

전체 가이드북은 통합본([WAREHOUSE_ONBOARDING_GUIDE.md](./WAREHOUSE_ONBOARDING_GUIDE.md))과 `onboarding/` 디렉터리 내 7개의 독립된 챕터별 파일로 구성되어 있습니다.

```
📁 ai/
├── 📄 WAREHOUSE_ONBOARDING_GUIDE.md   # 전체 통합 온보딩 가이드북
├── 📁 onboarding/                      # 챕터별 분할 가이드북
│   ├── 📄 01_company_and_overview.md   # Chapter 1: 회사 소개 및 물류센터(FC) 개요
│   ├── 📄 02_safety_guidelines.md      # Chapter 2: 안전보건 가이드 (Safety First)
│   ├── 📄 03_system_and_devices.md     # Chapter 3: 기본 시스템 및 장비 사용법 (PDA / WMS)
│   ├── 📄 04_inbound_and_stow.md       # Chapter 4: 입고(Inbound) 및 재고 보관(Stow) 프로세스
│   ├── 📄 05_outbound_pick_pack.md     # Chapter 5: 출고(Outbound) 프로세스: 피킹 & 패킹
│   ├── 📄 06_icqa_and_exception.md     # Chapter 6: 재고 관리(ICQA) 및 예외 처리
│   └── 📄 07_daily_routine_and_faq.md  # Chapter 7: 일일 근무 루틴, 평가 지표(KPI) 및 FAQ
└── 📄 README.md                        # 저장소 및 문서 안내 설명서 (현재 파일)
```

---

## 📖 챕터별 상세 설명

| 챕터 | 문서명 | 주요 내용 |
| :---: | :--- | :--- |
| **01** | [01_company_and_overview.md](./onboarding/01_company_and_overview.md) | 센터 핵심 가치, 물류 흐름도(Mermaid), 현장 복장 규정 및 반입 금지 물품 안내 |
| **02** | [02_safety_guidelines.md](./onboarding/02_safety_guidelines.md) | 지게차 안전 반경, 보행자 통로 규칙, 중량물 취급 3원칙, 화재·비상 대피 매뉴얼 |
| **03** | [03_system_and_devices.md](./onboarding/03_system_and_devices.md) | WMS 기본 개념, PDA 바코드 스캐너 조작 요령, 8자리 로케이션 바코드 체계 |
| **04** | [04_inbound_and_stow.md](./onboarding/04_inbound_and_stow.md) | 입고 검품 기준, 선입선출(FIFO) 원칙, 골든존(Golden Zone) 적재 가이드 |
| **05** | [05_outbound_pick_pack.md](./onboarding/05_outbound_pick_pack.md) | 오더 피킹 최적 동선, 3중 스캔 확인, 완충재 및 H자형 박스 테이핑 규정 |
| **06** | [06_icqa_and_exception.md](./onboarding/06_icqa_and_exception.md) | 주기적 순환 실사(Cycle Count), 오피킹·파손·결품 발생 시 안돈(Andon) 보고 체계 |
| **07** | [07_daily_routine_and_faq.md](./onboarding/07_daily_routine_and_faq.md) | 일일 교대 근무 루틴, 주요 성과 지표(UPH/오류율), 신규 입사자 FAQ |

---

## 💡 문서 활용 및 기여 가이드
- **현장 교육 시**: 개별 챕터 문서를 태블릿/PDA 또는 인쇄물 형태로 배포하여 사용합니다.
- **내용 수정/추가 시**: `main` 브랜치에서 새로운 기능 브랜치(`feature/...`)를 생성하여 작업 후 Pull Request를 통해 반영합니다.
