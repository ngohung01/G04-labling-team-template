# Nhật ký tuần 01 · 15/09 – 21/09/2026

> **File ví dụ** — tên, số liệu và link đều là giả. Tuần mới thì copy
> [`_mau-tuan.md`](_mau-tuan.md) thành `tuan-02.md`.

**Lead 1:** [ngohung01](https://github.com/ngohung01)
**Dữ liệu / task CVAT:** Ảnh giao thông đô thị — [task 204](https://cvat.note.transformerlabs.ai/tasks/204)

<br>

**Lead 2:** [thaianthai15](https://github.com/thaianthai15)
**Dữ liệu / task CVAT:** Ảnh giao thông đô thị — [task 150](https://cvat.note.transformerlabs.ai/tasks/150)


## Thành viên và phân công

| Thành viên | Vị trí | Phân công tuần này |
|---|---|---|
| Ngô Văn Hưng ([ngohung01](https://github.com/ngohung01)) | Lead · Reviewer · Annotator | Chia job, chốt edge case, review xác suất 10% mọi job; gán job 1450  |
| Nguyễn An Thái ([thaianthai15](https://github.com/thaianthai15)) | Lead · Reviewer · Annotator | Chia job, chốt edge case, review xác suất 10% mọi job; gán job 1666  |
| Lê Danh Trung ([TrungLD-ux](https://github.com/TrungLD-ux)) | Annotator | Job 1451, 1667 |
| Trương Công Hoài Nam ([merlin2003-ai](https://github.com/merlin2003-ai)) | Annotator | Job 1452, 1668  |
| Nguyễn Lê Thế Anh ([Theanh271](https://github.com/Theanh271)) | Annotator |  Job 1453, 1669  |
 
## Công việc

| # | Nội dung công việc | Annotator | Reviewer | Hoàn thành | Ghi chú |
|---|---|---|---|---|---|
| 1 | Job 1450 — 25 ảnh, gán nhãn bbox_polygon | [ngohung01](https://github.com/ngohung01) | [thaianthai15](https://github.com/thaianthai15) | 🟡 60% | Đã vẽ hết bbox thuộc loại Object instance , còn Drivable area và Lane marking đang làm|
| 2 | Job 1451 — 25 ảnh, gán nhãn bbox_polygon | [TrungLD-ux](https://github.com/TrungLD-ux) |[thaianthai15](https://github.com/thaianthai15)| 🟡 70% | nhãn cơ bản còn đường vạch đường, một số biển báo  |
| 3 | Job 1452 — 25 ảnh, gán nhãn bbox_polygon | [merlin2003-ai](https://github.com/merlin2003-ai) |[thaianthai15](https://github.com/thaianthai15)| 🟡 50% | Đã vẽ Drivable area , còn lại đang làm  |
| 4 | Job 1453 — 25 ảnh, gán nhãn bbox_polygon | [Theanh271](https://github.com/Theanh271) |[thaianthai15](https://github.com/thaianthai15)| 🟡 70% | Đã thực hiện khoảng 70%, chủ yếu đã khoanh các vehicle cơ bản; còn một số vehicle nhỏ/xa, bị che khuất hoặc boundary chưa rõ. |
| 6 | Đọc lại guideline §3,§4, gom các ca chưa rõ | [ngohung01](https://github.com/ngohung01) | — | ✅ 100% | Ra P-001, P-002 |

Mức hoàn thành: ✅ xong **và đã qua review** · 🟡 đang làm (ghi %) · ⛔ bị chặn (ghi lý do) · ⬜ chưa bắt đầu

## Tổng kết

- Đã gán: 0 / 200 ảnh ()
- Qua review lần đầu: 0% 
- Edge case mới: P-001

## Vướng mắc

>- P-002 (xe bị che khuất) chưa chốt nên job 103 phải dừng. Lead đã gửi câu hỏi lên BTC.
>- P-003: vẽ lại box y hệt qua các frame liên tiếp mất ~40% thời gian job 105.
>  Đang cân nhắc làm tool trong [`source-tool/`](../source-tool/).

## Kế hoạch tuần 02

>- Chốt P-002, mở lại job 103.
>- Xong job 102, 104, 105.
>- Quyết định có làm tool cho P-003 hay dùng chế độ Track sẵn có của CVAT.
