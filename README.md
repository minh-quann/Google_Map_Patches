# 🗺️ Google Maps Patched (Bearinmind) & MicroG-RE

Bản đóng gói Google Maps Android tối ưu hóa với các bản vá cao cấp từ **Bearinmind**, mở khóa **tần số quét 120Hz siêu mượt**, đặc biệt **khôi phục hoàn toàn Dòng thời gian (Timeline)** vốn đang bị lỗi/mất trên hàng loạt máy, hỗ trợ đăng nhập tài khoản Google qua **MicroG-RE / ReVanced GmsCore**, chặn quảng cáo, tích hợp cảnh báo giao thông & bắn tốc độ kiểu **Waze**.

---

## 📥 Tải về (Direct Downloads)

> [!NOTE]
> 💡 **Ai không cần tải MicroG-RE?**  
> Nếu trên máy bạn **đã cài sẵn MicroG hoặc MicroG-RE** (thường dùng chung cho **YouTube ReVanced / ReVanced Extended** với tên gói `app.revanced.android.gms`) thì **KHÔNG CẦN TẢI** file MicroG-RE nữa! Bạn chỉ cần tải duy nhất file **Google Maps Patched** về cài là dùng được ngay.

| Ứng dụng | Phiên bản | Dung lượng | Link tải trực tiếp | Ghi chú |
| :--- | :--- | :--- | :--- | :--- |
| **Google Maps Patched** | `v26.36.04.973607363` | ~125 MB | [⬇️ Tải Google Maps APK](https://github.com/minh-quann/Google_Map_Patches/releases/download/v26.36.04/Google_Maps_v26.36.04_Patched.apk) | Mở khóa 120Hz, Timeline hoạt động, Waze alert, Ad-free |
| **MicroG-RE** (GmsCore) | `v7.2.2-dev.2` | ~43 MB | [⬇️ Tải MicroG-RE APK](https://github.com/minh-quann/Google_Map_Patches/releases/download/v26.36.04/MicroG-RE-7.2.2.apk) | *Chỉ tải nếu máy chưa có MicroG/GmsCore* |

👉 **Xem danh sách tải đầy đủ tại mục [Releases](https://github.com/minh-quann/Google_Map_Patches/releases)**

---

## ✨ Các tính năng nổi bật (Highlights)

### 1. 📍 Khôi phục hoàn toàn Dòng thời gian (Timeline) — Cứu cánh cho người dùng Maps!
> [!IMPORTANT]
> **Vấn đề nhức nhối hiện nay**: Google gần đây đã đổi chính sách, **khai tử Timeline trên nền web** và chuyển sang lưu trữ cục bộ liên kết chặt với Google Play Services. Hậu quả là hàng loạt máy (đặc biệt là máy xách tay/nội địa, máy dùng app mod, máy không có chứng nhận GMS chuẩn) bị **mất sạch lịch sử vị trí**, liên tục báo lỗi *"Dòng thời gian không khả dụng"* hoặc không thể tải dữ liệu.

* **Hoạt động trơn tru 100%**: Bản vá này can thiệp trực tiếp vào hệ thống định vị để khôi phục hoàn toàn tính năng Timeline. Mọi lộ trình di chuyển, các địa điểm ghé thăm, thời gian dừng chân theo từng ngày đều được **tự động ghi nhận chính xác và hiển thị mượt mà**.
* **Bảo mật & Lưu trữ cục bộ (On-device)**: Dữ liệu hành trình được lưu an toàn ngay trên bộ nhớ điện thoại của bạn, đảm bảo tính riêng tư tuyệt đối và không lo bị Google quét hay khóa dịch vụ.
* **Xuất file GPX & Sao lưu tiện lợi**:
  * Hỗ trợ xuất dữ liệu chuyến đi ra file định dạng **`.gpx`** để xem lại cung đường phượt hoặc nhập vào các ứng dụng thể thao, bản đồ chuyên dụng khác.
  * Hỗ trợ nhập và xuất dữ liệu lịch sử từ Google Takeout.

---

### 2. 🚀 Mở khóa tần số quét màn hình 120Hz (120Hz Refresh Rate)
* **Khắc phục điểm yếu cố hữu của Google Maps gốc**: Google luôn giới hạn cứng Maps ở mức **60Hz**, khiến cảm giác vuốt cuộn bản đồ, xoay góc nhìn trên màn hình tần số quét cao bị khựng giật khó chịu.
* **Mượt mà tuyệt đối**: Bản vá gỡ bỏ hoàn toàn giới hạn 60Hz, cho phép toàn bộ giao diện và thao tác lướt bản đồ chạy ở tần số quét tối đa **120Hz**, mang lại trải nghiệm vuốt chạm cực kỳ mượt mà.
* **Cách kích hoạt**:
  > Vào **Google Maps** $\rightarrow$ Chạm vào **Avatar tài khoản** ở góc trên bên phải $\rightarrow$ Chọn **Cài đặt (Settings)** $\rightarrow$ Chọn mục **Tùy biến (Customization)** $\rightarrow$ Gạt bật công tắc **120 refresh rate**.

---

### 3. 🛡️ Đăng nhập tài khoản qua MicroG-RE / ReVanced GmsCore
* Đăng nhập tài khoản Google bình thường trên ứng dụng đã mod mà không bị Google Play Services chặn chữ ký số.
* Đồng bộ danh sách địa điểm đã lưu (*Yêu thích, Muốn đến, Gắn sao...*).
* Dùng chung tài nguyên với **ReVanced GmsCore / MicroG-RE** (`app.revanced.android.gms`).

---

### 4. 🚗 Cảnh báo Camera giao thông & Quá tốc độ (Kiểu Waze)
* **Cảnh báo Camera phạt nguội & bắn tốc độ**: Phát chuông thông báo và hiển thị vị trí camera phía trước từ dữ liệu OpenStreetMap (bán kính 25 – 175 km).
* **Chuông báo chạy quá tốc độ**: Tự động phát âm thanh cảnh báo khi xe vượt quá tốc độ tối đa của cung đường (app gốc chỉ đổi màu đỏ chứ không có tiếng chuông).
* **Tích hợp cảnh báo Waze**: Hiển thị cảnh báo chướng ngại vật, tai nạn, chốt cảnh sát từ Waze trực tiếp lên bản đồ.

---

### 5. 🚫 Chặn quảng cáo & Tinh gọn giao diện
* Loại bỏ hoàn toàn các ghim địa điểm quảng cáo tài trợ (Promoted Pins) trên bản đồ.
* Chặn kết quả tìm kiếm được tài trợ (Sponsored Ads).
* Ẩn các khối tóm tắt AI Gemini rườm rà và danh sách doanh nghiệp quảng cáo dưới chân địa chỉ.
* Tùy chọn ẩn các tab ít dùng (*Khám phá, Đóng góp*) để giao diện bản đồ thông thoáng tối đa.

---

### 6. 🔋 Chế độ siêu tiết kiệm pin Pixel (Power Saving Mode)
* Mang tính năng độc quyền của Google Pixel lên máy Honor: Khi đang dẫn đường, bấm nút nguồn để chuyển sang màn hình đen AMOLED tối giản, chỉ hiển thị mũi tên rẽ tiếp theo. Giúp máy siêu mát và tiết kiệm pin tối đa khi đi đường dài.

---

### 7. 🎛️ Tiện ích điều khiển & Giao diện bo góc chuẩn
* Thêm nút `+` và `-` to rõ trực tiếp trên màn hình dẫn đường để phóng to/thu nhỏ dễ dàng bằng 1 ngón tay.
* Giữ nguyên thiết kế bo cong tròn mềm mại chuẩn Material You nguyên bản của Google.

---

## 📱 Hướng dẫn cài đặt & Thiết lập chuẩn cho máy HONOR (MagicOS)

### Bước 1: Cài đặt ứng dụng
1. Nếu máy **chưa có** MicroG / GmsCore: Cài file **`MicroG-RE-7.2.2.apk`** trước.
2. Cài file **`Google_Maps_v26.36.04_Patched.apk`**.
3. Mở Google Maps $\rightarrow$ Bấm vào Avatar góc trên bên phải $\rightarrow$ **Đăng nhập** tài khoản Google.
4. Cấp quyền hệ thống:
   * **Vị trí**: Chọn **Luôn cho phép** để tính năng Timeline ghi nhận hành trình ngầm chính xác nhất.
   * **Thông báo**: Cho phép để nhận âm thanh dẫn đường và cảnh báo camera.

---

### Bước 2: Thiết lập pin cho MicroG trên HONOR (Rất quan trọng)
Trên MagicOS, để MicroG không chạy ngầm gây hao pin nhưng vẫn kích hoạt tức thì khi mở Google Maps:

1. Vào **Cài đặt** $\rightarrow$ **Pin** $\rightarrow$ **Khởi chạy ứng dụng**.
2. Tìm ứng dụng **MicroG-RE** (hoặc **microG Services**).
3. Chuyển từ chế độ *Tự động quản lý* sang **Quản lý thủ công**:
   * ❌ **Tắt**: Tự khởi chạy (*Auto-launch*)
   * ❌ **Tắt**: Chạy ngầm (*Run in background*)
   * ✅ **BẬT DUY NHẤT**: **Khởi chạy thứ cấp (Secondary launch)**
> 💡 *Với thiết lập này, MicroG sẽ ngủ sâu hoàn toàn khi không dùng đến (tiết kiệm 100% pin), nhưng hễ bạn mở Google Maps lên là MagicOS sẽ tự động gọi MicroG dậy để đồng bộ dữ liệu.*

---

### Bước 3: Khắc phục lỗi bấm link không mở app Maps trên HONOR
Do cơ chế bảo mật của MagicOS trên Android 12+, các ứng dụng mod bị ẩn nút gán liên kết thủ công. Bạn chọn 1 trong 2 cách sau:

* **Cách 1: Không cần máy tính (Khuyên dùng)**
  * Tải và cài đặt ứng dụng mã nguồn mở **[LinkSheet](https://github.com/1f20/LinkSheet/releases)** (hoặc trên F-Droid).
  * Đặt LinkSheet làm trình xử lý liên kết mặc định. Từ đây, bất cứ khi nào bạn bấm vào một liên kết Google Maps từ Zalo, Messenger, SMS... LinkSheet sẽ chuyển thẳng vào Google Maps Patched mà không bị đẩy ra trình duyệt web.

* **Cách 2: Nếu có máy tính kết nối ADB (Thực hiện trong 5 giây)**
  * Chạy câu lệnh sau qua terminal / cmd:
    ```bash
    adb shell pm set-app-links --package com.google.android.apps.maps 2 all
    adb shell pm set-app-links-user-selection --user 0 --package com.google.android.apps.maps true all
    ```

---

## 📜 Nguồn & Bản quyền
* Bản vá dựa trên dự án mã nguồn mở **[bearinmindcat/morphe-patches](https://github.com/bearinmindcat/morphe-patches)**.
* Dự án MicroG-RE bởi **[WSTxda/MicroG-RE](https://github.com/WSTxda/MicroG-RE)**.
* Framework vá ứng dụng bởi **[Morphe](https://morphe.software)**.
