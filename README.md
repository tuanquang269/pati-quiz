# PATI Quiz — Resilience + Curiosity Assessment

Interactive web quiz đánh giá ứng viên PATI Group, kết hợp 2 validated instruments:

- **CD-RISC-10** (Campbell-Sills & Stein, 2007) — Resilience
- **CEI-II** (Kashdan et al., 2009) — Curiosity

## ✨ Tính năng

- 🎯 16 câu hỏi, ~7-8 phút
- 📱 Mobile-friendly responsive
- ⚡ Single-file HTML, không cần backend
- 🧮 Auto-scoring + recommendation matrix
- 🔒 Privacy-first: data chỉ chạy trong browser, không gửi đâu cả
- 📋 Copy/download kết quả gửi HR

## 🚀 Live demo

👉 **https://tuanquang269.github.io/pati-quiz/**

## 📊 Scoring

| Resilience (0-40) | Curiosity (0-50) | Recommendation |
|---|---|---|
| ≥25 | ≥35 | 🟢 HIRE ngay — A-player |
| ≥25 | 27-34 | 🟡 HIRE OK — Execution role |
| 18-24 | ≥35 | 🟡 HIRE OK — Mid-IC, học nhanh |
| <18 | bất kỳ | 🔴 PASS |

## 📝 Caveat

- Self-report instrument → có thể fake high. Luôn kết hợp với STAR behavioral interview.
- Văn hóa Việt khiêm tốn → adjust norm xuống ~3-5 điểm so US norm.
- Đây là **1 data point**, không phải decision-maker duy nhất.

## 🔧 Tech

Pure HTML/CSS/JavaScript, no dependencies. Mở file `index.html` trong bất kỳ trình duyệt nào.

## 📜 License

CD-RISC-10: Free for academic use, commercial registration ở https://www.cd-risc.com
CEI-II: Public domain (Kashdan et al., 2009)

Quiz wrapper (UI/code): MIT License
