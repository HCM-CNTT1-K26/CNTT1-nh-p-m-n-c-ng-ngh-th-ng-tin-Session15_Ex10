# CNTT1-nh-p-m-n-c-ng-ngh-th-ng-tin-Session15_Ex10
### Phần 1: Phân tích & Đề xuất

**1. Yêu cầu bài toán:**

* **Đầu vào:** Nhóm 4-5 người cần kênh làm việc rõ ràng, không bị trôi bài, dễ tìm tài liệu và theo dõi deadline.
* **Đầu ra:** Chọn được quy trình giao tiếp giúp chốt việc nhanh, không mất file và hợp lý với thói quen của nhóm.

**2. Đánh giá nhanh 2 giải pháp:**

* **Zalo:** Dễ dùng, ai cũng có sẵn trên điện thoại. Nhưng tin nhắn trôi rất nhanh, file cũ hay bị hết hạn và không quản lý công việc chuyên sâu được.


* **Lark Suite:** Phân channel rõ ràng, gom việc theo luồng (Thread), tạo task có deadline 1-click. Điểm trừ là cả nhóm phải mất 1-2 ngày học cách dùng.



---

### Phần 2: So sánh & Chốt lựa chọn

**3. Bảng so sánh 5 tiêu chí:**

| Tiêu chí nghiệp vụ | Zalo | Lark Suite |
| --- | --- | --- |
| 1. Không trôi tin nhắn | ⚠️ | ✅ |
| 2. Quản lý công việc | ⚠️ | ✅ |
| 3. Miễn phí & Dễ dùng | ✅ | ⚠️ |
| 4. Tìm lại lịch sử | ❌ | ✅ |
| 5. Giao tiếp bất đồng bộ | ❌ | ✅ |

**4. Chốt lựa chọn: Dùng giải pháp kết hợp (Hybrid)**

* **Dùng Lark làm chính (Nội bộ):** Cho cả nhóm dùng để trao đổi code, lưu docs và chốt deadline.
* **Dùng Zalo làm phụ (Đối ngoại):** Chỉ dùng khi cần liên lạc với đối tác/thầy cô bên ngoài.

**Giải quyết 3 bẫy dữ liệu:**

* *Bẫy 1 (Thành viên Kinh doanh dùng điện thoại):* Lark có ứng dụng điện thoại chạy rất mượt, xem docs hay check task thoải mái.
* *Bẫy 2 (Mất 1-2 ngày học Lark):* Đáng để đổi. Thà chậm 1-2 ngày chuẩn hóa quy trình còn hơn sát deadline lại bị mất file hay trôi việc.


* *Bẫy 3 (Đối tác dùng Zalo):* Nhóm tạo riêng 1 box Zalo phụ để nhắn tin với đối tác, còn việc nội bộ vẫn giữ trên Lark.

---

### Phần 3: Thiết kế Channel & Quy tắc nhóm

**5. Cấu trúc 5 Channel trên Lark:**

1. `#01-thong-bao`: Chỉ Trưởng nhóm đăng thông báo quan trọng, lịch họp.
2. `#02-dev-ky-thuat`: Cho ban Kỹ thuật bàn code, gửi link demo/build.
3. `#03-kinh-doanh`: Ban Kinh doanh bàn kế hoạch tiếp thị, tài liệu pitching.
4. `#04-tai-lieu-chung`: Lưu trữ file thiết kế, biên bản họp, tài liệu chung.
5. `#05-tra-da-xuat-the`: Nhắn tin chém gió, giải trí tự do.

**Cách chặn spam `@all` ("Quy tắc cờ đỏ"):**

* **Khóa quyền `@all`:** Chỉ trưởng nhóm/trưởng ban mới được tag `@all`.
* **Dùng Reply in Thread:** Ai trả lời tin nhắn nào thì gõ trực tiếp vào ô *Reply* của tin đó để tránh làm phiền người khác.
* **Quy tắc cờ đỏ:** Cố tình tag `@all` cho việc không gấp hoặc nhắn linh tinh vào ban đêm sẽ bị tính 1 cờ đỏ / phạt quỹ nhóm.
