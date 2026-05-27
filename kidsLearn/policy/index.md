   # 🔒 Chính Sách Bảo Mật KidsLearn

> **Phiên bản:** 1.0 (Draft)
> **Ngày hiệu lực:** [Cần điền sau khi legal review]
> **Liên hệ:** privacy@kidslearn.vn

> ⚠️ **Lưu ý:** Đây là bản DRAFT chưa qua legal review. Cần luật sư chuyên về luật bảo vệ trẻ em (COPPA, GDPR-K, Luật trẻ em Việt Nam) rà soát trước khi public.

---

## 1. Cam Kết Tổng Quan

KidsLearn được thiết kế **dành riêng cho trẻ em từ 2–6 tuổi** dưới sự giám sát của phụ huynh. Chúng tôi cam kết:

- ✅ **Không bán** dữ liệu cá nhân của trẻ em hoặc phụ huynh cho bên thứ ba
- ✅ **Không hiển thị quảng cáo bên thứ ba** trong ứng dụng
- ✅ **Không có chức năng chat/social** giữa trẻ em với người lạ
- ✅ **Không có in-app purchase trong khu vực trẻ em** — tất cả thanh toán chỉ diễn ra trong Khu phụ huynh có khóa PIN
- ✅ **Tuân thủ COPPA** (Children's Online Privacy Protection Act — Hoa Kỳ) và các quy định tương đương tại Việt Nam và EU (GDPR-K)
- ✅ **Lưu trữ dữ liệu tại Việt Nam** theo Luật An ninh mạng

---

## 2. Dữ Liệu Chúng Tôi Thu Thập

### 2.1 Dữ liệu phụ huynh (chủ tài khoản)

| Loại | Mục đích | Bắt buộc? |
|------|----------|-----------|
| Email | Đăng nhập, gửi báo cáo tuần, đặt lại mật khẩu | Có |
| Họ tên hiển thị | Cá nhân hóa giao diện | Không (tuỳ chọn) |
| Avatar URL (nếu đăng nhập Google/Apple) | Hiển thị ảnh đại diện | Không |
| Apple ID hoặc Google ID (nếu social login) | Xác thực, không lưu tên thật | Không |

### 2.2 Dữ liệu trẻ em (do phụ huynh nhập)

| Loại | Mục đích | Bắt buộc? |
|------|----------|-----------|
| Tên gọi (có thể là biệt danh) | Cá nhân hóa lời chào trên màn hình | Có |
| Ngày sinh | Xác định nhóm tuổi để áp dụng curriculum phù hợp | Có |
| Giới tính | Cá nhân hóa avatar (tuỳ chọn) | Không |
| Tiến độ học tập | Tự điều chỉnh độ khó, hiển thị huy hiệu | Tự động |
| Thời gian sử dụng | Giới hạn thời gian học hằng ngày | Tự động |

**Chúng tôi KHÔNG thu thập từ trẻ em:**
- ❌ Họ tên đầy đủ
- ❌ Địa chỉ nhà
- ❌ Số điện thoại
- ❌ Ảnh chụp khuôn mặt (trừ khi phụ huynh chủ động thêm ảnh vào bộ thẻ tự tạo — ảnh chỉ lưu trên máy cục bộ, KHÔNG upload server)
- ❌ Vị trí địa lý (location)
- ❌ Lịch sử duyệt web

### 2.3 Dữ liệu kỹ thuật

| Loại | Mục đích |
|------|----------|
| Thiết bị (model iPhone/iPad, iOS version) | Hỗ trợ kỹ thuật, tối ưu hiệu năng |
| Crash logs ẩn danh | Sửa lỗi |
| Analytics ẩn danh (qua Mixpanel/Amplitude) | Hiểu hành vi sử dụng tổng quát — KHÔNG gắn với user ID cá nhân |

---

## 3. Cách Chúng Tôi Sử Dụng Dữ Liệu

| Mục đích | Pháp lý cơ sở | Có chia sẻ với bên thứ ba? |
|----------|---------------|---------------------------|
| Vận hành ứng dụng học tập | Hợp đồng dịch vụ | Không |
| Gửi báo cáo tiến độ tuần qua email | Hợp đồng dịch vụ | SendGrid/SES (xử lý kỹ thuật, có DPA) |
| Push notification nhắc nhở streak | Sự đồng ý của phụ huynh | APNs (Apple) |
| Phân tích sử dụng ẩn danh | Lợi ích chính đáng | Mixpanel (dữ liệu ẩn danh) |
| Xác thực thanh toán | Hợp đồng dịch vụ | App Store / Google Play |
| Lưu trữ media (ảnh deck custom) | Hợp đồng dịch vụ | **KHÔNG** — ảnh deck tự tạo chỉ lưu cục bộ trên máy |

**Chúng tôi KHÔNG:**
- Bán dữ liệu cho công ty marketing
- Sử dụng dữ liệu trẻ em để training AI model bên thứ ba
- Cho phép theo dõi cross-app (App Tracking Transparency: opt-out mặc định)

---

## 4. Quyền Của Phụ Huynh

Theo COPPA và Luật Trẻ em Việt Nam, phụ huynh có toàn quyền:

| Quyền | Cách thực hiện |
|-------|----------------|
| Xem toàn bộ dữ liệu của trẻ | Khu phụ huynh → Báo cáo chi tiết |
| Xóa hồ sơ trẻ và tất cả tiến độ | Khu phụ huynh → Xóa hồ sơ trẻ (alert confirm) |
| Xóa tài khoản phụ huynh | Khu phụ huynh → Xóa tài khoản (mọi dữ liệu liên quan bị xóa trong 30 ngày) |
| Yêu cầu xuất dữ liệu (DSAR) | Gửi email `privacy@kidslearn.vn` — phản hồi trong 30 ngày |
| Rút lại sự đồng ý | Đăng xuất hoặc xóa app |
| Khiếu nại | Gửi email hoặc liên hệ Cục An toàn thông tin (Bộ TT&TT) |

---

## 5. Bảo Mật Dữ Liệu

| Lớp bảo vệ | Triển khai |
|------------|------------|
| Mật khẩu | Bcrypt 12 rounds (không bao giờ lưu plaintext) |
| Token đăng nhập | JWT 15 phút + refresh token 7 ngày, lưu trong iOS Keychain |
| Truyền dẫn | TLS 1.2+ cho mọi request API |
| Lưu trữ at-rest | AWS RDS PostgreSQL với encryption at-rest enabled |
| Phân tách dữ liệu | Mỗi tài khoản tách biệt qua RBAC + row-level security |
| Backup | Hàng ngày, mã hóa, lưu 30 ngày |
| Khu phụ huynh | Khóa bằng PIN 4 chữ số (tránh trẻ vào nhầm) |

**Trong trường hợp data breach:** Chúng tôi sẽ thông báo cho phụ huynh bị ảnh hưởng trong vòng 72 giờ qua email + push notification, đồng thời báo cáo cơ quan chức năng theo quy định.

---

## 6. Lưu Trữ Dữ Liệu

| Loại dữ liệu | Thời gian lưu | Lý do |
|--------------|---------------|-------|
| Tài khoản đang hoạt động | Vô thời hạn (đến khi xóa) | Vận hành dịch vụ |
| Tài khoản đã xóa | 30 ngày grace period, sau đó hard-delete | Cho phép khôi phục nếu xóa nhầm |
| Crash logs | 90 ngày | Debug |
| Analytics ẩn danh | 13 tháng | Năm trước so sánh |
| Subscription receipts | 7 năm | Quy định kế toán Việt Nam |

**Lưu trữ địa lý:** Server đặt tại AWS Singapore (gần Việt Nam, độ trễ thấp) với bản backup tại Việt Nam (đối tác data center địa phương) để tuân thủ Luật An ninh mạng.

---

## 7. Cookies & Tracking

KidsLearn là ứng dụng native iOS, **KHÔNG** sử dụng cookies trình duyệt. Chúng tôi sử dụng:

- **App Tracking Transparency (ATT):** Mặc định **Không Theo Dõi** — chúng tôi không bao giờ yêu cầu trẻ em hoặc phụ huynh cho phép tracking cross-app
- **Anonymous device identifier** (do Apple cung cấp, có thể reset bất cứ lúc nào): để phân tích sử dụng ẩn danh

---

## 8. Quảng Cáo

**KidsLearn cam kết HOÀN TOÀN không có quảng cáo bên thứ ba** trong toàn bộ vòng đời sản phẩm. Chúng tôi tin rằng quảng cáo không phù hợp với trẻ em dưới 6 tuổi.

---

## 9. Liên Kết Ngoài

Trong khu phụ huynh, có thể có liên kết đến:
- App Store / Play Store (thanh toán)
- Trang web KidsLearn (FAQ, hỗ trợ)
- Trang chính sách bảo mật phiên bản tiếng Anh

Khu trẻ em **KHÔNG** chứa bất kỳ liên kết ngoài nào.

---

## 10. Thay Đổi Chính Sách

Khi cập nhật chính sách, chúng tôi sẽ:
- Push notification cho mọi tài khoản
- Email cho tài khoản đang hoạt động
- Yêu cầu phụ huynh **đồng ý lại** nếu thay đổi ảnh hưởng đáng kể (vd: thêm bên xử lý dữ liệu mới)

---

## 11. Liên Hệ

| Mục đích | Email |
|----------|-------|
| Quyền dữ liệu (xem, xóa, xuất) | privacy@kidslearn.vn |
| Hỗ trợ kỹ thuật | support@kidslearn.vn |
| Báo cáo bảo mật | security@kidslearn.vn |
| Hợp tác B2B (trường mầm non) | partners@kidslearn.vn |

**Địa chỉ pháp lý:** [Cần điền địa chỉ công ty đăng ký]

**Người đại diện pháp lý:** [Cần điền tên + chức danh]

---

*Tài liệu được tạo lần đầu: Tháng 5/2026*
*Cần legal review trước khi public*
