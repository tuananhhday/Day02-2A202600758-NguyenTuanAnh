# Day02 - AI Product Labs

## Student Information

- Name: Nguyễn Tuấn Anh
- Student ID: 2A202600758
- Course: AI20K
- Lab: Day 02 - AI Product Labs

---

## Project Overview

Trong bài lab này, nhóm thực hiện quy trình:

1. Scan các vấn đề thực tế.
2. Chọn Top 3 Candidate Problems.
3. Hội tụ và chọn 1 problem cuối cùng.
4. Validation và Research.
5. Thiết kế Workflow hiện tại và Workflow tương lai.
6. So sánh No AI / Rule / Workflow / Agent.
7. Đưa ra quyết định Go / Not Yet / No-Go.

Problem cuối cùng nhóm lựa chọn:

> Cognitive Reframing khi sinh viên nhận feedback tiêu cực.

---

## Selected Problem

Nhiều sinh viên khi nhận feedback tiêu cực thường diễn giải thành đánh giá về bản thân thay vì xem đó là góp ý cho bài làm.

Điều này dẫn đến:

- Cảm xúc tiêu cực.
- Trì hoãn sửa bài.
- Giảm động lực học tập.
- Khó chuyển feedback thành hành động cụ thể.

---

## Proposed Solution

Nhóm đề xuất một AI Workflow hỗ trợ Cognitive Reframing.

AI hỗ trợ:

- Tách Fact / Feeling / Interpretation.
- Đặt câu hỏi reflection.
- Đề xuất cách nhìn cân bằng hơn.
- Chuyển feedback thành action items.

Người dùng vẫn:

- Tự đánh giá.
- Tự quyết định cách hành động.
- Tự chịu trách nhiệm cho kết quả cuối cùng.

---

## Why Workflow Instead of Agent?

Sau khi so sánh:

| Approach | Nhận định |
|-----------|-----------|
| No AI | Người dùng tự xử lý toàn bộ |
| Rule | Khó xử lý các tình huống đa dạng |
| Workflow | Phù hợp nhất với bài toán |
| Agent | Over-engineering và khó kiểm soát |

Nhóm quyết định chọn **Workflow**.

---

## Key Learnings

Qua bài lab này em học được rằng:

- Không nên bắt đầu từ AI rồi mới đi tìm bài toán.
- Cần xác định đúng actor, workflow và bottleneck trước.
- AI chỉ tạo giá trị khi được đặt đúng vị trí trong workflow.
- Một Workflow đơn giản nhưng đúng pain point có giá trị hơn một Agent phức tạp.

---

## Repository Structure

```text
.
├── 01-individual-problem-scan/
│   ├── 01-individual-problem-scan.md
│   └── 01-individual-problem-scan-workflow-card-1.png
├── 02-group-problem-statement/
│   └── 02-group-problem-statement.md
├── 03-individual-reflection/
│   └── 03-individual-reflection.md
└── README.md
```

---

## Final Decision

**GO**

Lý do:

- Actor rõ ràng.
- Workflow rõ ràng.
- Có thể đo lường impact.
- Có boundary an toàn.
- AI tạo giá trị thực sự ở bước Cognitive Reframing.
