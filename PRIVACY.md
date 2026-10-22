# Chính sách quyền riêng tư — KeToanTools và extension "KeToanTools - Công cụ hữu ích cho kế toán viên"

Hiệu lực từ: 22/10/2026
Đơn vị cung cấp: **HD Web Services** — Liên hệ: **lienhe@hdweb.info**

## 1. Phạm vi

Chính sách áp dụng cho ứng dụng KeToanTools trên Windows và extension Chrome
"KeToanTools - Công cụ hữu ích cho kế toán viên" đi kèm. Extension đưa dữ liệu hóa đơn điện tử và giấy chứng nhận
xuất xứ (C/O) của chính doanh nghiệp bạn từ cổng dịch vụ công về ứng dụng trên máy tính của bạn.

## 2. Dữ liệu được xử lý

| Dữ liệu | Nguồn | Mục đích |
|---|---|---|
| MST và tên của tài khoản đang đăng nhập | Trang cổng thuế, EcoSys | Lưu dữ liệu đúng doanh nghiệp, hiển thị trong extension |
| Danh sách hóa đơn, tệp XML, chi tiết hóa đơn (tên, MST người mua/bán, hàng hóa, số tiền, thuế) | hoadondientu.gdt.gov.vn | Xem, lọc, ghi chú, xuất Excel trong KeToanTools |
| Hồ sơ C/O và tệp đính kèm | ecosys.gov.vn | Lưu trữ, tra cứu trong KeToanTools |
| Cookie phiên đăng nhập của cổng thuế | Trình duyệt | Gắn vào yêu cầu gửi tới chính cổng thuế |
| Tiến độ đồng bộ, trạng thái kết nối, địa chỉ local của ứng dụng | Extension, ứng dụng | Hiển thị trạng thái |

Chúng tôi **không** thu thập mật khẩu cổng thuế. Bạn tự đăng nhập và nhập captcha trên trang chính thức.

## 3. Dữ liệu được lưu và gửi đi đâu

- Dữ liệu hóa đơn và C/O chỉ được gửi tới KeToanTools đang chạy **trên cùng máy tính** (địa chỉ 127.0.0.1) và lưu
  tại thư mục bạn chọn. Không có máy chủ trung gian; nhà phát triển không nhận được dữ liệu này.
- Cookie phiên chỉ được dùng trong trình duyệt để gửi yêu cầu tới chính cổng thuế; extension không lưu và không gửi
  cookie/token cho ứng dụng hay bên nào khác.
- Extension lưu trong bộ nhớ của Chrome (`chrome.storage.local`) các thông tin trạng thái ở mục 2, gồm MST và tên
  tài khoản gần nhất; không lưu nội dung hóa đơn.
- Không quảng cáo, không công cụ phân tích hay theo dõi hành vi, không bán hoặc chia sẻ dữ liệu cho bên thứ ba.

## 4. Kết nối mạng khác của ứng dụng

- **Cập nhật ứng dụng:** KeToanTools kiểm tra và tải bản mới từ GitHub (github.com). GitHub thấy địa chỉ IP của máy;
  yêu cầu không kèm MST hay dữ liệu hóa đơn.
- **Tải PDF gốc (khi bạn bấm):** ứng dụng gửi mã tra cứu và MST người bán của hóa đơn đó tới trang tra cứu của nhà
  cung cấp hóa đơn điện tử tương ứng, như khi bạn tự tra cứu.

## 5. Lưu giữ và xóa

Dữ liệu nằm trên máy của bạn đến khi bạn xóa. Xóa đơn vị trong ứng dụng, xóa thư mục dữ liệu hoặc gỡ ứng dụng/extension
để xóa. Gỡ extension sẽ xóa dữ liệu trạng thái trong `chrome.storage.local`.

## 6. Bảo mật

Ứng dụng chỉ lắng nghe trên 127.0.0.1 và chỉ nhận dữ liệu từ extension có đúng định danh; mỗi phiên dùng khóa ngẫu
nhiên. Bạn chịu trách nhiệm bảo vệ máy tính và thư mục dữ liệu của mình (sao lưu, quyền truy cập).

## 7. Liên hệ và thay đổi

Câu hỏi về quyền riêng tư: **lienhe@hdweb.info**. Khi chính sách thay đổi, chúng tôi cập nhật ngày hiệu lực ở đầu trang.

KeToanTools là phần mềm độc lập, không phải sản phẩm của cơ quan nhà nước.
