# [Chapter 6] 재고 관리(ICQA) 및 예외 처리

## 6.1 ICQA(Inventory Control & Quality Assurance)
- **주기적 순환 실사(Cycle Count)**: WMS 로케이션과 실제 재고의 일치율(Net Accuracy) $99.8\%$ 이상 유지
- **유통기한 모니터링**: 잔여 소비기한 30% 이하 품목 조기 격리(Quarantine)

## 6.2 오피킹, 파손, 분실 발생 시 프로토콜
```mermaid
sequenceDiagram
    participant Worker as 현장 작업자
    participant PDA as PDA/WMS
    participant Lead as 공정 관리자(Lead/PS)
    participant ICQA as ICQA 부서

    Worker->>PDA: 오류 보고 (품절/파손/바코드불량)
    PDA->>Lead: 안돈(Andon) 알림 발생
    Worker->>Lead: 실물 확인 요청
    Lead->>ICQA: 로케이션 동결(Freeze) 및 재실사 요청
    ICQA->>PDA: 재고 수량 보정 또는 파손 처리(Write-off)
```
- 임의로 다른 위치의 상품을 가져가 대체하는 행위 엄격 금지 (재고 왜곡 원인 1위)
