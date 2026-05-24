# PATI Quiz v2.0 — Multi-Method Hybrid Assessment

## Mục tiêu
Đánh giá Resilience + Curiosity của ứng viên PATI Group bằng **4 phương pháp khác nhau** để chống faking và tăng predictive validity.

## Cấu trúc 4 phases

| Phase | Method | Items | Time | Đo gì |
|-------|--------|-------|------|-------|
| 1 | SJT (Situational Judgment Test) | 10 scenarios | 12 phút | Behavioral judgment under realistic eCom contexts |
| 2 | Forced-choice (Most/Least like me) | 15 quads | 8 phút | Anti-fake trait preferences (ipsative) |
| 3 | Mini case study + timer | 1 case + 6 Q | 8 phút | Cognitive resilience under time pressure |
| 4 | Open-ended STAR | 1 câu, 150-200 chữ | 5 phút | Curiosity quality + writing |
| **Total** | | **22+22+6+1=51 inputs** | **~33 phút** | |

## Validity checks (embedded)

1. **Lie scale (Social Desirability):** 3 items trong Phase 2 hỏi về trait "ai cũng không có 100%" — nếu candidate chọn extreme positive cả 3 → faking flag
2. **Consistency check:** Phase 1 SJT có 2 cặp scenario tương tự (paraphrased) — nếu candidate trả lời mâu thuẫn → flag
3. **Response time anomaly:** Phase 3 case study có timer — nếu candidate trả lời <30s/câu HOẶC >2min/câu → flag (rushing or stuck)
4. **Word count check:** Phase 4 open-ended — nếu <80 từ hoặc copy-paste rõ ràng → flag

## Scoring philosophy

- **Phase 1 (SJT):** Mỗi câu có 4 options, scored bằng SME ranking (Subject Matter Expert): best=3, ok=2, weak=1, bad=0. Total /30 (10 scenarios × 3 max).
- **Phase 2 (Forced-choice):** Ipsative scoring — mỗi quad cho 1 "most like me" (+2) và 1 "least like me" (-1). Resilience traits: R1-R5. Curiosity traits: C1-C5. Net score /30.
- **Phase 3 (Case):** 6 câu factual + reasoning về case. Scored 0/1 mỗi câu. /6.
- **Phase 4 (STAR):** Keyword-based + length heuristic. 4 criteria (specific situation, action ownership, learning extracted, curiosity demonstrated). 0-2 mỗi criteria. /8.

**Composite Resilience score** = Phase1_resilience + Phase2_R + Phase3 → /44
**Composite Curiosity score** = Phase1_curiosity + Phase2_C + Phase4 → /38
