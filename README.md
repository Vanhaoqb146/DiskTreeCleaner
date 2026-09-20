# DiskTree Cleaner Pro

<div align="center">

<img src="assets/logo.png" alt="DiskTree Cleaner Pro Logo" width="128" height="128" />

**Phần Mềm Phân Tích & Dọn Dẹp Dung Lượng Ổ Đĩa Thông Minh Chuẩn Windows Fluent UI**  
*The Modern, High-Performance Disk Space Analyzer & Intelligent Cleaner for Windows*

[![Downloads](https://img.shields.io/github/downloads/Vanhaoqb146/DiskTreeCleaner/total.svg?style=for-the-badge&color=2563EB&logo=github)](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases)
[![Latest Release](https://img.shields.io/github/v/release/Vanhaoqb146/DiskTreeCleaner?style=for-the-badge&color=10B981)](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011%20(64--bit)-0078D4?style=for-the-badge&logo=windows)](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases)
[![Language](https://img.shields.io/badge/Language-Ti%E1%BA%BFng%20Vi%E1%BB%87t%20%7C%20English-F59E0B?style=for-the-badge)](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases)

<br />

[**⬇️ TẢI BỘ CÀI ĐẶT MỚI NHẤT (DOWNLOAD v1.5.1)**](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases/download/v1.5.1/DiskTreeCleaner_Setup_1.5.1.exe)


</div>

---

## 🇻🇳 Giới thiệu tổng quan

**DiskTree Cleaner Pro** là giải pháp phần mềm chuyên sâu dành cho hệ điều hành Windows, giúp người dùng quét trực quan hóa toàn bộ cây thư mục, theo dõi tốc độ phình to của ổ cứng và dọn dẹp dung lượng rác an toàn tuyệt đối.

Được phát triển với phong cách giao diện **Fluent Design Dark / Light** hiện đại, phần mềm kết hợp giữa khả năng phân tích biểu đồ khối (Treemap Visualizer) cực nhanh và các thuật toán phân tích chuyên sâu cho lập trình viên, ứng dụng hệ thống và tệp tin trùng lặp.

### 🌟 Các tính năng nổi bật

1. **🌳 Cây Thư Mục & Biểu Đồ Khối Trực Quan (Disk Tree & Treemap):**
   * Quét đa luồng tốc độ cao hàng triệu tệp tin chỉ trong vài giây.
   * Biểu đồ Treemap tương tác cho phép phóng to, thu nhỏ và nhận diện ngay những thư mục đang chiếm dung lượng khổng lồ.

2. **📈 Dòng Thời Gian Biến Động Dung Lượng (Storage Timeline Intelligence - Tối ưu vượt bậc ở v1.5.1):**
   * So sánh biến thiên chi tiết từng thư mục giữa 2 mốc bất kỳ qua cơ sở dữ liệu SQLite v2.
   * **Bộ lọc phát thải thông minh (Smart Filtering) & Lưu trữ 30 ngày**: Thu gọn database SQLite từ 18.5 GB xuống chỉ còn ~17.7 MB, hoàn toàn miễn nhiễm với nguy cơ phình to đĩa và hỗ trợ đọc song song không độ trễ.
   * Cơ chế **Zero False Delta (Chống báo ảo)**: Phân định rõ ràng quét đầy đủ vs quét dở dang, tuyệt đối không tính số liệu ảo gây hoang mang cho người dùng.
   * Biểu đồ Thác nước (Waterfall Card) trực quan 4 chỉ số: Phát sinh, Giải phóng, Biến thiên ròng, Tỷ lệ xác định.
   * Ngăn kéo bằng chứng (Evidence Drawer) và công cụ dự báo cạn kiệt ổ đĩa theo thời gian thực.

3. **🔔 Thông Báo Hệ Thống Windows Native (Mới ở v1.5.0):**
   * Tự động gửi thông báo qua khay hệ thống khi hoàn tất quét trong lúc ứng dụng chạy ngầm hoặc thu nhỏ.
   * Nhấp vào thông báo sẽ tự động đưa ứng dụng lên và mở thẳng đến trang kết quả.

4. **⚡ Làm Sạch Thùng Rác Lớn Bất Đồng Bộ (Mới ở v1.5.0):**
   * Cơ chế dọn thùng rác dung lượng lớn hoàn toàn chạy ngầm, không bao giờ gây đơ hay treo máy, hỗ trợ hộp thoại tiến trình và nút hủy an toàn.

5. **📊 Bóc Tách Dung Lượng Ứng Dụng (App Storage Intelligence):**
   * Phân tích chi tiết từng phần mềm đã cài đặt trên Windows.
   * Tách bạch rõ ràng: Dung lượng cài đặt thực tế, Cache tạm thời, Dữ liệu người dùng (User Data) và Registry.

6. **🧑‍💻 Dọn Dẹp Lập Trình Viên & Cache (Developer & Cache Cleaner):**
   * Tự động quét và dọn sạch các thư mục nặng hàng chục GB của lập trình viên: `node_modules`, Python `.venv`, `.pytest_cache`, Gradle, Maven, NuGet, Cargo, Docker cache,...

7. **🔍 Quét Tệp Trùng Lặp & Tự Do Lựa Chọn (Deep Duplicate Finder Pro):**
   * Áp dụng thuật toán băm SHA-256 đối chiếu byte-to-byte chính xác 100%.
   * Toàn quyền chọn giữ lại hoặc xóa bất kỳ bản sao nào, hỗ trợ mở trực tiếp trong File Explorer.

8. **🛡️ An Toàn Tuyệt Đối & Phục Hồi (Safety & Undo Support):**
   * Cơ chế xóa mặc định đưa vào Thùng rác (Recycle Bin) hoặc Cách ly (Quarantine).
   * Có lịch sử dọn dẹp và tính năng hoàn tác (Undo) an toàn.

9. **🌐 Đa Ngôn Ngữ Song Ngữ 100%:**
   * Chuyển đổi mượt mà tức thì giữa Tiếng Việt và English trực tiếp trong cài đặt.

---

## 🇬🇧 Overview (English)

**DiskTree Cleaner Pro** is a modern disk space management suite for Windows, providing deep folder tree visualization, intelligent storage trend monitoring, and safe developer-grade cleaning tools.

### Key Highlights
* **High-Speed Treemap & Tree Analyzer:** Interactive hierarchical visualization showing exactly where your disk space went.
* **Storage Timeline Intelligence (New in v1.5.0):** SQLite v2 change tracking between any two snapshots with Zero False Delta protection, visual waterfall cards, and evidence drawer.
* **Windows Native Notifications (New in v1.5.0):** Background scan completion toasts with 1-click navigation to results.
* **Non-Blocking Large Recycle Bin Cleaner (New in v1.5.0):** Async recycle bin purging with smooth progress dialog and safe cancellation.
* **App Storage Intelligence:** Breaks down application footprint into binary size, cache files, user data, and registry entries.
* **Developer Cleaner:** Reclaims gigabytes from developer environments (`node_modules`, `.venv`, Gradle, Cargo, NuGet, Docker).
* **Deep Duplicate Finder Pro:** Byte-to-byte SHA-256 deduplication with free selection and instant Explorer integration.
* **Safe by Design:** Full Recycle Bin integration, rule-based folder protection, and undo history.
* **100% Bilingual:** Dynamic on-the-fly switching between Vietnamese and English.

---

## 📦 Tải về & Cài đặt (Installation)

1. Tải bản cài đặt chính thức tại [GitHub Releases](https://github.com/Vanhaoqb146/DiskTreeCleaner/releases/latest).
2. Chạy file `DiskTreeCleaner_Setup_1.5.1.exe` và làm theo chỉ dẫn.

### 🔒 Đối soát tính toàn vẹn (SHA-256 Checksum)
Trước khi cài đặt, bạn có thể kiểm tra tính toàn vẹn của tệp tải về trong PowerShell:
```powershell
Get-FileHash -Algorithm SHA256 .\DiskTreeCleaner_Setup_1.5.1.exe
```
* **Bản phát hành:** `v1.5.1`
* **Mã băm SHA-256 chuẩn:**
  `7793AEFCA8822064482264AB5C05A286E362936117365278840174D682692FB3`

> ### ⚠️ Lưu ý khi cài đặt trên Windows 11 / Windows 10
> 
> * **Nếu gặp thông báo SmartScreen ("Windows protected your PC")**:
>   Nhấp chuột vào dòng **"More info"** (Thông tin thêm) ➔ Bấm nút **"Run anyway"** (Vẫn chạy) để hoàn tất cài đặt.
> 
> * **Nếu bị tính năng Smart App Control (SAC) trên Windows 11 chặn**:
>   Do phần mềm mới phát hành chưa có chứng chỉ số mở rộng của Microsoft, Windows 11 có thể tự động chặn. Bạn hãy vào **Cài đặt Windows (Settings)** ➔ **Privacy & Security** ➔ **Windows Security** ➔ **App & browser control** ➔ Chọn **Smart App Control** và chuyển sang **Off** (Tắt) hoặc **Evaluation** trước khi tiến hành cài đặt.


## 💻 Yêu cầu hệ thống (System Requirements)

* **Hệ điều hành:** Windows 10 (64-bit, phiên bản 1809 trở lên) hoặc Windows 11 (64-bit).
* **Phần cứng:** CPU 64-bit 1.5 GHz+, RAM tối thiểu 2 GB (khuyến nghị 4 GB), dung lượng ổ đĩa trống 100 MB.
* **Quyền hạn:** Không yêu cầu quyền Administrator khi quét thông thường (chỉ cần quyền Admin khi dọn rác hệ thống sâu).

---

## 📬 Liên hệ & Hỗ trợ (Support & Licensing)

* **Tác giả / Nhà phát triển:** Van Hao
* **Email:** vanhaoqb146@gmail.com
* **Báo cáo lỗi (Issue Tracker):** [GitHub Issues](https://github.com/Vanhaoqb146/DiskTreeCleaner/issues)