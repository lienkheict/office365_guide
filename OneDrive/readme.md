# Chia sẻ và lưu trữ tài liệu trên OneDrive

**Mục đích:** Hướng dẫn chi tiết cách sử dụng OneDrive để lưu trữ, đồng bộ, chia sẻ và quản lý tài liệu công việc hàng ngày.  
**Đối tượng:** Toàn thể CBNV đã được cấp tài khoản Microsoft 365.  
**Lưu ý chung:** OneDrive là nơi lưu trữ file cá nhân liên quan công việc (không thay thế SharePoint cho tài liệu chung dự án nếu công ty đã có quy định dùng SharePoint cho tài liệu nhóm).  

---

## Mục lục
1. Truy cập OneDrive
2. Tổ chức thư mục và quy ước đặt tên
3. Tải file lên (Upload) — các phương pháp
4. Đồng bộ (Sync) với máy tính – cài đặt OneDrive Client
5. Chia sẻ file và thư mục — các quyền và lựa chọn
6. Quản lý phiên bản (Version history) và khôi phục file
7. Khôi phục file bị xóa (Recycle bin)
8. Dung lượng, quota và quản lý bộ nhớ
9. Mẹo vận hành, an toàn và chuẩn công ty
10. Những vấn đề thường gặp và cách xử lý nhanh

---

## 1. Truy cập OneDrive

Bạn có thể dùng OneDrive theo 2 cách chính:

### A. Truy cập qua web (OneDrive for web)
1. Mở trình duyệt, truy cập: `https://www.office.com`  
2. Đăng nhập bằng tài khoản công ty.  
3. Chọn ứng dụng **OneDrive** trên trang Microsoft 365.

(Trang web hiển thị giao diện quản lý file, có thanh điều hướng trái: My files, Shared, Recycle bin, v.v.)

![Giao diện OneDrive Web](./img/7.jpg)

### B. Ứng dụng OneDrive trên máy tính (OneDrive client)
- Windows 10/11 thường có sẵn OneDrive client. Nếu chưa có hoặc cần cập nhật, tải và cài đặt từ trang Microsoft hoặc IT sẽ hỗ trợ.
- Sau khi cài, đăng nhập bằng tài khoản công ty để bắt đầu đồng bộ các thư mục.

---

## 2. Tổ chức thư mục và quy ước đặt tên

Để dễ quản lý và tránh nhầm lẫn, tuân thủ một số quy ước đặt tên và cấu trúc:

### Gợi ý cấu trúc

/OneDrive - TenNhanVien
/Du-an
/Bao-cao
/Hop-hop-dong
/Tai-lieu-chung
/Archive (lưu trữ cũ)


### Quy ước đặt tên file
- Sử dụng dấu gạch ngang `-` hoặc gạch dưới `_` thay cho khoảng trắng nếu cần.
- Bao gồm ngày (YYYYMMDD) nếu file là bản ghi theo ngày: `BC-Doanh-so-20251029.xlsx`
- Thêm mã dự án nếu cần: `ARH-PROY01-Ke-hoach-Q4.docx`

### Lý do quan trọng
- Giúp tìm kiếm nhanh, tránh trùng tên, dễ quản lý khi sync và chia sẻ.
- Khi nhiều người cùng truy cập, file rõ ràng làm giảm nhầm lẫn phiên bản.

---

## 3. Tải file lên (Upload)

OneDrive hỗ trợ nhiều cách tải file:

### A. Kéo thả (drag & drop)
- Mở OneDrive web, kéo file hoặc folder từ máy tính vào cửa sổ trình duyệt.

### B. Nút Upload
- Chọn **Upload > Files** hoặc **Upload > Folder** rồi chọn file/thư mục cần upload.

### C. Lưu trực tiếp từ ứng dụng Office
- Trong Word/Excel/PowerPoint: chọn **File > Save As > OneDrive - [Tên bạn]**, chọn thư mục lưu trên OneDrive.

### D. Lưu ý khi tải nhiều file hoặc file lớn
- Đối với file lớn (hàng trăm MB hoặc vài GB), ưu tiên dùng OneDrive client để đồng bộ — client có cơ chế tiếp tục khi kết nối gián đoạn.
- Tránh upload nhiều file cùng lúc nếu mạng nội bộ yếu; upload theo từng nhóm.

---

## 4. Đồng bộ (Sync) với máy tính — Thiết lập OneDrive client

### A. Kích hoạt OneDrive client
1. Mở ứng dụng OneDrive trên Windows (search “OneDrive”).  
2. Đăng nhập bằng tài khoản công ty.  
3. Chọn thư mục bạn muốn đồng bộ (cả My files hoặc chọn từng thư mục con bằng “Choose folders”).

### B. Chức năng chính của OneDrive client
- Tự động đồng bộ file giữa thư mục OneDrive trên máy và đám mây.
- File có thể hiển thị trạng thái: `Available when online`, `Always keep on this device`, `Syncing...`.

### C. Selective Sync (Chọn thư mục đồng bộ)
- Nếu bộ nhớ máy nhỏ, trong cài đặt OneDrive chọn **Choose folders** để chỉ đồng bộ những thư mục cần thiết.

### D. Sử dụng Files On-Demand
- Tính năng Files On-Demand giúp hiển thị file trên máy tính mà không chiếm dung lượng thực sự, chỉ download khi mở. Chọn `Free up space` nếu muốn chỉ giữ bản trực tuyến.

### E. Đồng bộ trên macOS
- Tương tự: cài OneDrive, đăng nhập, chọn thư mục đồng bộ.

### F. Lưu ý bảo mật khi dùng máy công cộng
- Không bật tùy chọn “Keep me signed in” trên máy công cộng.
- Sau sử dụng trên máy lạ, sign out (đăng xuất) từ OneDrive client và trình duyệt.

---

## 5. Chia sẻ file và thư mục — Các quyền và lựa chọn

OneDrive hỗ trợ nhiều kiểu chia sẻ. Hiểu đúng các tùy chọn sẽ tránh lộ thông tin không mong muốn.

### A. Hai cách chia sẻ chính
1. **Share link (chia sẻ link)**: Tạo liên kết truy cập (có thể là "Anyone with the link" hoặc "People in your organization" hoặc "Specific people").  
2. **Invite people (mời trực tiếp)**: Nhập email người nhận và gửi lời mời; bạn có thể đặt quyền truy cập.

### B. Các quyền chia sẻ
- **Can view** (Chỉ xem): Người nhận chỉ xem, không chỉnh sửa.  
- **Can edit** (Có thể chỉnh sửa): Người nhận có thể sửa, xóa, tải về.  
- **Expiration (Hết hạn)**: Bạn có thể đặt ngày hết hạn cho link (nếu tổ chức bật tính năng).  
- **Password (Mật khẩu)**: Một số tổ chức có bật tùy chọn thêm mật khẩu cho link chia sẻ.

### C. Các loại link (phổ biến)
- **Anyone with the link**: Bất kỳ ai có link đều truy cập — không yêu cầu đăng nhập. Dùng cẩn trọng, nên hạn chế dùng cho tài liệu nhạy cảm.  
- **People in [Organization]**: Chỉ người trong công ty có thể mở link. Thường an toàn cho nội bộ.  
- **Specific people**: Chỉ những email cụ thể được cấp quyền.

### D. Cách chia sẻ (web)
1. Chọn file hoặc thư mục → nhấp **Share**.  
2. Chọn kiểu link và quyền (view/edit).  
3. Nhập email người nhận (nếu mời trực tiếp) và kèm lời nhắn nếu cần.  
4. Nhấn **Send** hoặc **Copy link** để dán vào nơi khác.

![Chia sẻ file trên OneDrive Web](./img/8.jpg)

### E. Chia sẻ từ OneDrive client (máy tính)
- Chuột phải file/thư mục trong thư mục OneDrive → chọn **Share** → làm tương tự như trên.

### F. Sự khác biệt so với SharePoint
- OneDrive là không gian cá nhân của mỗi người (dù có thể chia sẻ).  
- SharePoint/Teams là nơi lưu trữ tài liệu chung của nhóm/dự án; khi tài liệu cần quản lý nhóm dài hạn, hãy lưu tại SharePoint.

---

## 6. Quản lý phiên bản (Version history)

OneDrive lưu lịch sử phiên bản của file Office (Word/Excel/PowerPoint) và một số loại file khác. Đây là công cụ quan trọng khi cần phục hồi nội dung trước đó.

### A. Xem và khôi phục phiên bản
1. Chọn file → Nhấp chuột phải → **Version history** (Lịch sử phiên bản).  
2. Danh sách các phiên bản sẽ hiện ra, kèm ngày giờ và người chỉnh sửa.  
3. Chọn phiên bản muốn xem hoặc **Restore** để phục hồi phiên bản đó làm bản hiện tại.

![Version history trên OneDrive](./img/9.jpg)

### B. Lưu ý
- Phiên bản thường giữ trong một khoảng thời gian do chính sách của tổ chức; nếu cần giữ lâu dài, lưu bản sao offline hoặc lưu vào thư mục Archive.
- Khi nhiều người cùng sửa, version history rất hữu ích để tra lại nội dung hoặc rollback.

---

## 7. Khôi phục file bị xóa (Recycle bin)

Nếu lỡ xóa file trên OneDrive, bạn có thể phục hồi nhanh:

### A. Trên OneDrive web
1. Chọn **Recycle bin** ở thanh điều hướng trái.  
2. Chọn file cần khôi phục → nhấn **Restore**.

### B. Thời hạn lưu trong Recycle bin
- File sẽ nằm trong Recycle bin một khoảng thời gian theo chính sách (thường 30 ngày hoặc theo cấu hình quản trị). Sau thời hạn đó, file có thể bị xóa vĩnh viễn.

### C. Khi file bị xóa vĩnh viễn
- Nếu file bị xóa cả ở Recycle bin, liên hệ IT — trong một số trường hợp họ có thể khôi phục từ snapshot hoặc backup (tùy chính sách sao lưu của công ty).

---

## 8. Dung lượng, quota và quản lý bộ nhớ

### A. Kiểm tra dung lượng
- Trên OneDrive web, vào **Settings > OneDrive settings** hoặc nhìn biểu tượng dung lượng để biết bạn còn bao nhiêu GB.

### B. Quota thông thường
- Mỗi tài khoản Microsoft 365 Basic có dung lượng gói cho trước (do IT/Quản trị quy định). Nếu gần đầy, xóa file không cần thiết hoặc di chuyển file cũ sang Archive/SharePoint.

### C. Giải phóng không gian
- Sử dụng tính năng **Free up space** trên file (trên máy) để giữ file chỉ trực tuyến.  
- Xóa file lớn, media không cần thiết, hoặc lưu trữ tạm thời trên ổ cứng gắn ngoài nếu cần.

---

## 9. Mẹo vận hành, an toàn và chuẩn công ty

### A. Mẹo dùng hàng ngày
- Luôn lưu file vào thư mục OneDrive khi làm việc để tự động đồng bộ và tránh mất dữ liệu khi máy gặp sự cố.  
- Dùng **Save As > OneDrive** thay vì lưu local nếu file phục vụ công việc chung hoặc cần truy cập từ nhiều thiết bị.  
- Khi gửi file cho nhiều người, cân nhắc chia sẻ link thay vì đính kèm file lớn qua email.

### B. Bảo mật
- Không chia sẻ link “Anyone with the link” cho tài liệu nhạy cảm.  
- Khi chia sẻ file quan trọng, dùng kiểu “Specific people” hoặc “People in organization” và tắt quyền chỉnh sửa nếu chỉ cần xem.  
- Kích hoạt xác thực đa yếu tố (MFA) nếu tổ chức yêu cầu để bảo vệ tài khoản.

### C. Quy định lưu trữ công ty
- Tuân thủ chính sách lưu trữ tài liệu của công ty (ví dụ: tài liệu hợp đồng phải lưu tại thư mục hợp đồng với mã hóa/quyền truy cập giới hạn).  
- Không lưu thông tin cá nhân nhạy cảm ngoài quy định.

---

## 10. Những vấn đề thường gặp và cách xử lý nhanh

### Vấn đề: File không đồng bộ (Sync stuck)
- Kiểm tra trạng thái OneDrive client (biểu tượng trên taskbar).  
- Thử **Pause syncing** rồi **Resume**.  
- Kiểm tra tên file có ký tự không hợp lệ (ví dụ: `: * ? < > |`) — đổi tên file.  
- Khởi động lại OneDrive client hoặc đăng xuất rồi đăng nhập lại.

### Vấn đề: Người được mời không mở được link
- Kiểm tra loại link (Anyone vs Specific people). Nếu link là “Specific people”, đảm bảo người nhận là email đúng.  
- Nếu người ngoài công ty, họ có thể tham gia bằng trình duyệt; kiểm tra họ có bị chặn bởi firewall hay không.

### Vấn đề: Muốn thu hồi quyền chia sẻ
- Chọn file → **Manage access** → thu hồi link hoặc thay đổi quyền (Remove link / Stop sharing).

### Vấn đề: File bị ghi đè trong khi nhiều người sửa
- Khuyến nghị dùng Office Online (Word/Excel Online) để cùng chỉnh đồng thời; Office Online hỗ trợ đồng bộ thay đổi theo thời gian thực.  
- Nếu xảy ra xung đột, OneDrive sẽ tạo bản sao xung đột hoặc lưu bản cục bộ; kiểm tra và hợp nhất nội dung bằng tay.

---

## Kết luận và tài liệu tham khảo nhanh

- OneDrive là công cụ lưu trữ cá nhân công việc, mạnh về đồng bộ và chia sẻ nhanh.  
- Luôn theo quy ước đặt tên và cấu trúc thư mục để dễ quản lý.  
- Khi chia sẻ, cân nhắc quyền và loại link để đảm bảo an toàn thông tin.  
- Gặp sự cố liên quan đến khôi phục vĩnh viễn hoặc cài đặt nâng cao, liên hệ IT: `it@vietmygroup.vn`.

**Tiếp theo:** [Hướng dẫn tạo cuộc họp trực tuyến (Teams)](./teams.md) • [Hướng dẫn Email (Outlook)](./email.md)


