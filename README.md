# 🛡️ THE SENTINEL: Cross-Domain Edge IDS
> **"반도체 공정의 정밀함이 사이버 세상을 지키는 가장 강력한 방패가 됩니다."**

본 프로젝트는 반도체 제조 공정의 초정밀 **이상 탐지(Anomaly Detection)** 알고리즘을 사이버 보안 도메인으로 확장한 **Cross-Domain** 보안 엔진입니다.

---

### 🧠 핵심 연구 배경 (Research Background)
- **Domain Transfer:** 산업 AI 전문가 과정(60시간)에서 습득한 반도체 센서 분석 기술을 CAN-Bus 및 Network 패킷 분석으로 전이 학습.
- **Edge Optimization:** **7KB~100KB**급 TinyML 모델 설계를 통해 저전력 엣지 디바이스 최적화.

### 📊 검증 데이터셋 (Datasets Used)
- **고려대 HCRL Car-Hacking:** DoS, Fuzzy, Spoofing 공격 탐지.
- **CIC-IDS 2017 & NSL-KDD:** 실시간 네트워크 침입 탐지 벤치마크.

### 📈 최종 실험 성과 (Performance Metrics)
> **실측 수치를 바탕으로 산출된 고신뢰성 지표입니다.**

| Metric | Score | 비고 |
| :--- | :---: | :--- |
| **Abnormal Recall** | **1.00** | **차량 공격 탐지율 100% (미탐 0%)** |
| **Weighted Average F1** | **0.98** | 전체 데이터셋 종합 성능 균형 |
| **Model Size** | **~7KB** | **Int8 양자화 기반 초경량화** |
| **Network Accuracy** | **99.99%** | CIC-IDS 2017 실시간 탐지 정확도 |

### ⚙️ 시스템 비교 (System Comparison)
| 구분 | Typical Server-Based IDS | **The Sentinel (Ours)** |
| :--- | :---: | :---: |
| **Model Size** | 100MB+ (Heavy) | **7KB ~ 100KB (Ultra-Light)** |
| **Latency** | 200ms+ | **1ms ~ 5ms (Real-time)** |
| **Platform** | High-end Server | **Mobile & PC Edge** |

---
Copyright (c) 2026 **Joon-yong Lee** Licensed under the MIT License.
