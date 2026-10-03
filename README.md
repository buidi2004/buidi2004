<div align="center">

<!-- HEADER BANNER DẠNG SÓNG GRADIENT CAO CẤP -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=buidi2004&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Cloud%20Infrastructure%20%E2%80%A2%20FinTech%20Architect%20%E2%80%A2%20Full-Stack&descAlignY=58&descAlign=50" width="100%"/>

<!-- HIỆU ỨNG GÕ CHỮ TYPING SVG DYNAMIC -->
<a href="https://github.com/buidi2004">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=750&lines=Backend+%26+Cloud+Infrastructure+Engineer;FinTech+Core+Banking+%E2%80%A2+Double-Entry+Ledger;Clean+Architecture+%E2%80%A2+Hexagonal+(Ports+%26+Adapters)+%E2%80%A2+CQRS;Flutter+(Optical+Fragment+Shaders)+%26+React+Native;Ready+to+collaborate+on+high-tech+projects!" alt="Typing SVG" />
</a>

<br/>

<!-- HÀNG HUY HIỆU LIÊN KẾT & PROFILE VIEWS ỔN ĐỊNH 100% -->
<p align="center">
  <a href="https://komarev.com/ghpvc/?username=buidi2004&color=58a6ff&style=for-the-badge&label=PROFILE+VIEWS">
    <img src="https://komarev.com/ghpvc/?username=buidi2004&color=58a6ff&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile Views" />
  </a>
  <a href="https://www.linkedin.com/in/v%C4%83n-d%C4%A9-b%C3%B9i-6270513b0/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.facebook.com/di.di.717541" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" />
  </a>
  <a href="https://zalo.me/0793919384" target="_blank">
    <img src="https://img.shields.io/badge/Zalo-0793919384-0068FF?style=for-the-badge&logo=chat&logoColor=white" alt="Zalo" />
  </a>
</p>

</div>

---

## 👨‍💻 Về bản thân (Engineering Profile)

```yaml
kỹ_sư: Bùi Văn Dĩ (buidi2004)
chuyên_môn: Backend & Cloud Infrastructure Developer • Cross-Platform Mobile Engineer
triết_lý_kỹ_thuật:
  - "Tách bạch trách nhiệm & kiểm thử toàn diện: Clean Architecture, Hexagonal, CQRS + MediatR"
  - "Toàn vẹn dữ liệu tài chính tối đa: Double-Entry Ledger, Idempotency UUID, Outbox Pattern"
  - "Lập trình điều khiển hạ tầng: Tự động cấp phát tài nguyên Docker thật (Docker.DotNet API)"
  - "Đồ họa hiệu năng cao: Viết Fragment Shaders (Impeller/Skia) trên Flutter đạt 120fps"
stack_mũi_nhọn: .NET 8 (C#) • Java 17 (Spring Boot 3) • Python (FastAPI) • Flutter & React Native
fun_fact: Tự build thành công OpenCore EFI macOS Sonoma/Sequoia cho ASUS ROG Strix G15 (AMD Ryzen + NootedRed) 👀
```

> 🎯 *"Mã nguồn tốt không chỉ chạy đúng, mà còn phải chịu lỗi cao, dễ mở rộng và phản ánh chính xác nghiệp vụ thực tế."*

---

## 🧠 Tư duy Thiết kế Hệ thống & Chuẩn mực Kỹ thuật

<table>
<tr>
<td width="50%" valign="top">

### 🏛️ Kiến trúc Phân tầng & Mẫu thiết kế
* **Clean Architecture & Hexagonal (Ports & Adapters):**
  * Tách biệt hoàn toàn `Domain` và `Application` khỏi framework và database.
  * Dependency Inversion tuyệt đối: Tầng trong không phụ thuộc tầng ngoài.
* **CQRS (Command Query Responsibility Segregation):**
  * Tách riêng đường đọc (Queries) và đường ghi (Commands) qua MediatR pipeline.
  * Tối ưu hóa hiệu năng đọc và đơn giản hóa logic nghiệp vụ khi ghi.
* **Kỹ thuật FinTech Chuyên sâu:**
  * **Sổ cái kế toán kép (Double-Entry Ledger):** Mọi giao dịch tiền tệ luôn cân bằng nợ/có (Debit/Credit), loại bỏ hoàn toàn sai lệch số dư.
  * **Máy trạng thái giao dịch (State Machine):** Kiểm soát vòng đời giao dịch chống xung đột trạng thái (Pending ➔ Processing ➔ Completed/Failed).

</td>
<td width="50%" valign="top">

### ⚙️ Hạ tầng, Chịu lỗi & Hiệu năng
* **Lập trình Điều khiển Hạ tầng (IaaS / PaaS Engine):**
  * Tương tác trực tiếp với Docker daemon API (`Docker.DotNet`) để tự động khởi tạo VPS, Database container, Object Storage.
  * Cấp chứng chỉ SSL Let's Encrypt tự động qua ACME Protocol.
* **Cơ chế Chịu lỗi & Toàn vẹn (Resiliency & Idempotency):**
  * **Idempotency Key:** Kiểm tra trùng lặp request tại tầng Gateway/Filter, ngăn chặn trừ tiền hay tạo tài nguyên 2 lần.
  * **Try/Catch Rollback:** Tự động dọn dẹp tài nguyên dở dang khi gặp lỗi, bảo vệ hệ sinh thái không rò rỉ bộ nhớ/port.
  * **Hangfire Background Workers:** Xử lý hàng đợi tác vụ nặng bất đồng bộ với cơ chế Exponential Backoff Retry.
* **Giao tiếp Thời gian thực (Real-Time Communication):**
  * Đồng bộ luồng dữ liệu tức thời qua **WebSocket (STOMP/SockJS)** và **SignalR**.

</td>
</tr>
</table>

---

## 🛠️ Kho Công nghệ & Công cụ (Comprehensive Tech Stack)

<div align="center">

<!-- BANNER SKILL ICONS HIỆN ĐẠI TỰ THAY ĐỔI SÁNG/TỐI -->
<img src="https://skillicons.dev/icons?i=dotnet,cs,java,spring,python,fastapi,php,postgres,mysql,flutter,dart,react,ts,js,docker,redis,rabbitmq,githubactions&theme=dark" alt="Tech Stack Banner" />

</div>

<br/>

**💻 Backend & Core Frameworks**
<p align="left">
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python_3-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP_8-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
</p>

**📱 Mobile & Frontend Ecosystem**
<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Expo_SDK_52-000020?style=for-the-badge&logo=expo&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React_Vite-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
</p>

**☁️ Database, Cloud & DevOps Infrastructure**
<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
  <img src="https://img.shields.io/badge/MinIO_S3-C72C48?style=for-the-badge&logo=minio&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Render_IaC-46E3B7?style=for-the-badge&logo=render&logoColor=black"/>
</p>

---

## 🌟 5 Dự án Trọng điểm (Featured Case Studies)

```
┌────────────────────────────────────────────────────────────────────────────────────────┐
│                        CÁC DỰ ÁN HỆ THỐNG TRỌNG ĐIỂM (CASE STUDIES)                    │
├──────────────────────────────┬─────────────────────────────┬───────────────────────────┤
│ 🌐 Cloud PaaS & Auto-Prov    │ 🏦 FinTech & Core Banking   │ 👗 Modern Full-Stack E-Com│
│ • CloudServiceStore (.NET)   │ • Core Banking Engine (Java)│ • IVIE Wedding (FastAPI)  │
│                              │ • Flutter E-Wallet (Shaders)│                           │
│                              │ • React Native Client       │                           │
└──────────────────────────────┴─────────────────────────────┴───────────────────────────┘
```

### 1️⃣ CloudServiceStore — Cloud Hosting Platform (PaaS)
> **Mã nguồn:** [`buidi2004/object-oriented-software-programming`](https://github.com/buidi2004/object-oriented-software-programming)  
> **Định vị:** Nền tảng Điện toán đám mây thu nhỏ với khả năng tự động cấp phát tài nguyên thật qua Docker Engine.

* **Kiến trúc xây dựng:**
  * Áp dụng chuẩn **.NET Clean Architecture** phân tách 5 tầng (`Domain`, `Application`, `Infrastructure`, `WebApi`, `Tests`).
  * Thực thi mô hình **CQRS kết hợp MediatR Pipeline Behaviors**; xác thực dữ liệu đầu vào qua FluentValidation trước khi chạm hạ tầng.
* **Cơ chế Cấp phát Hạ tầng Tự động (Real Provisioning):**
  * Tương tác trực tiếp với Docker socket thông qua thư viện `Docker.DotNet` để spin up các container VPS độc lập, cơ sở dữ liệu (`Postgres`, `MySQL`, `Redis`) và MinIO Object Storage.
  * Tự động yêu cầu và cài đặt chứng chỉ SSL Let's Encrypt qua giao thức ACME (`AcmeProvisioningService`).
* **Kỹ thuật Chống lỗi & Bền bỉ:**
  * **IdempotencyKey:** Gắn định danh duy nhất vào từng `ResourceProvisioningWorker` nhằm ngăn chặn cấp phát trùng tài nguyên khi mạng chập chờn.
  * **Try/Catch Rollback:** Tự động hủy và dọn dẹp các tài nguyên dở dang nếu một mắt xích gặp lỗi, bảo vệ hệ thống không bị tràn port hay cạn RAM.
  * **Hangfire Background Jobs:** Tích hợp `AutomaticRetry` xử lý các lỗi tạm thời từ Docker daemon.
* **CI/CD:** Quy trình tự động kiểm thử (`ci-develop.yml`) và triển khai sản phẩm (`deploy-main.yml`).

---

### 2️⃣ Sen Hồng Core Banking Engine — Financial E-Wallet Backend
> **Mã nguồn:** [`buidi2004/app-mono-di-va-khoa`](https://github.com/buidi2004/app-mono-di-va-khoa)  
> **Định vị:** Trái tim hệ thống Tài chính & Ví điện tử đạt chuẩn Ngân hàng, đề cao tính toàn vẹn và bảo mật tuyệt đối.

* **Kiến trúc Hexagonal & Domain-Driven Design (DDD):**
  * Thiết kế theo **Hexagonal Architecture (Ports and Adapters)**: Tách rời nghiệp vụ ví (`WalletService`, `LedgerService`, `AuthService`) khỏi Adapter giao tiếp ngoài (`REST Controllers`, `PostgreSQL Adapter`).
  * Đạt độ bao phủ kiểm thử cao cấp: **263/263 Automated Tests Passed**.
* **Nghiệp vụ Tài chính Chuyên sâu:**
  * **Sổ cái kép (Double-Entry Ledger):** Thực hiện quy tắc bất biến trong ngành tài chính `Tổng Nợ = Tổng Có` thông qua cặp thực thể `JournalEntry` và `LedgerPosting`.
  * **Máy trạng thái Giao dịch (Transaction State Machine):** Chặn đứng các tình trạng race condition và xung đột giao dịch song song.
  * **Outbox Pattern & Message Queue:** Đồng bộ thông điệp giao dịch qua RabbitMQ và Redis Cache đảm bảo tính nhất quán cuối cùng (Eventual Consistency).
  * **Bảo mật:** JWT Authentication, tự động xoay vòng Refresh Token, Idempotency Filter ngăn chặn gian lận nạp/rút tiền.

---

### 3️⃣ Sen Hồng E-Wallet — Flutter Clean Architecture Client
> **Mã nguồn:** [`buidi2004/mobile-nganhang`](https://github.com/buidi2004/mobile-nganhang)  
> **Định vị:** Ứng dụng Ví điện tử Flutter hiệu năng cao với công nghệ đồ họa Fragment Shaders quang học.

* **Đồ họa Cấp cao với Flutter Fragment Shaders (Impeller/Skia):**
  * Tự phát triển bộ widget kính quang học **Liquid Glass** bằng custom fragment shaders, giải quyết triệt để lỗi chạm xuyên (touch-through bug) trên Android.
  * Phân tầng chất lượng đồ họa thông minh: `GlassQuality.premium` cho thẻ tài khoản trọng tâm và `GlassQuality.minimal` cho danh sách lịch sử giao dịch cuộn mượt mà 60/120fps.
  * Thanh điều hướng `GlassScaffold` với cơ chế `contentAwareBrightness` tự động biến đổi màu sắc biểu tượng theo nội dung cuộn bên dưới.
* **Bảo mật & Trạng thái Ứng dụng:**
  * Điều hướng **Stateful Shell Route (`go_router`)** bảo toàn trạng thái khi di chuyển giữa các phân hệ tài chính.
  * Bộ chặn mạng Dio thông minh: `AuthInterceptor` quản lý phiên và `IdempotencyInterceptor` tự sinh UUID chống trùng giao dịch.
  * Bàn phím số bảo mật `CustomPinNumpad` và sinh trắc học FaceID/Vân tay (`local_auth`).

---

### 4️⃣ Sen Hồng Digital Banking — React Native Client
> **Mã nguồn:** [`buidi2004/nganhangfe`](https://github.com/buidi2004/nganhangfe)  
> **Định vị:** Ứng dụng Ngân hàng số đa nền tảng React Native với giao diện Dark Mode chuẩn Private Banking.

* **Nghiệp vụ Ngân hàng Số Thực tế:**
  * Tích hợp cổng chuyển tiền nhanh liên ngân hàng **VietQR 24/7** và tạo mã QR nhận tiền cá nhân chuẩn EMVCo.
  * Quản lý danh mục thẻ quốc tế (Visa/Mastercard/JCB) và thanh toán hóa đơn tiện ích đa dịch vụ.
* **Real-time Engine & WebSocket:**
  * Lắng nghe biến động số dư và thông báo nạp/chuyển tiền tức thời qua kênh **WebSocket (STOMP / SockJS)** kết nối trực tiếp Core Banking.
* **Nền tảng & Trải nghiệm:**
  * Xây dựng trên **Expo SDK 52** và **TypeScript**; tối ưu hóa giao diện Dark Mode sang trọng, bảo mật đa lớp với mã PIN và xác thực sinh trắc học.

---

### 5️⃣ IVIE Wedding Studio — Full-Stack Multi-Service Platform
> **Mã nguồn:** [`buidi2004/webbandocuoi`](https://github.com/buidi2004/webbandocuoi)  
> **Định vị:** Nền tảng Thương mại dịch vụ cho thuê & bán sản phẩm cưới với cấu trúc Multi-service hiện đại.

* **Kiến trúc Đa tầng (Micro-Services nhẹ):**
  * **Storefront Khách hàng:** Giao diện React + Vite tối ưu tốc độ render và SEO.
  * **Core REST API:** Xây dựng bằng **FastAPI (Python)** tận dụng cơ chế bất đồng bộ (async/await) xử lý tải cao, kết nối PostgreSQL.
  * **Hệ thống Quản trị (Admin Panel):** Tách biệt hoàn toàn, vận hành trên **Streamlit (Python)** giúp ban quản trị theo dõi đơn hàng và cập nhật catalog trực quan.
* **DevOps & Triển khai Tự động (Infrastructure as Code):**
  * Thiết lập tệp điều phối `render.yaml` tự động build, cấu hình biến môi trường và deploy đồng thời 3 dịch vụ lên Cloud Render chỉ với một cú commit.

---

### 💻 Điểm nhấn Kỹ thuật Hệ thống & Low-Level (Specialized Skill)
> **Mã nguồn:** [`buidi2004/hackintosh-rog513ih`](https://github.com/buidi2004/hackintosh-rog513ih)  
> **Định vị:** Bộ cấu hình OpenCore EFI hoàn chỉnh cho laptop gaming ASUS ROG Strix G15 (G513IH).

* **Năng lực can thiệp Hệ điều hành & Phần cứng:**
  * Can thiệp bảng ACPI và viết patch SSDT chuyên dụng (`SSDT-dGPU-Off.aml`) để vô hiệu hóa card rời NVIDIA GTX 1650, tối ưu thời lượng pin và nhiệt độ.
  * Cấu hình kexts điều khiển vi sai cho bàn di chuột I2C (`VoodooI2C`), phím bấm ASUS, Intel Wi-Fi & Bluetooth.
  * Kích hoạt tăng tốc đồ họa phần cứng iGPU AMD Radeon Mobile thông qua NootedRed, target chuẩn SMBIOS `MacBookPro16,2`.

---

## 📊 Thống kê & Hoạt động GitHub (GitHub Metrics)

<div align="center">

<!-- CẶP THỐNG KÊ TOKYO NIGHT CÂN ĐỐI 50-50 -->
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=buidi2004&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=buidi2004&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

<!-- GITHUB STREAK STATS -->
<p align="center">
  <img src="https://streak-stats.demolab.com?user=buidi2004&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<!-- ACTIVITY GRAPH RỘNG ĐẸP MẮT -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=buidi2004&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="Activity Graph" />
</p>

<!-- SNAKE CONTRIBUTION ANIMATION CHẠY TRỰC TIẾP TỪ WORKFLOW CỦA BẠN -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/buidi2004/buidi2004/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/buidi2004/buidi2004/output/github-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/buidi2004/buidi2004/output/github-snake.svg" width="100%"/>
</picture>

</div>

---

<div align="center">

⭐️ **Cảm ơn bạn đã ghé thăm hồ sơ kỹ thuật của mình! Luôn cởi mở trước những bài toán kiến trúc thử thách.** ⭐️

<br/>

<a href="https://github.com/buidi2004">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
</a>

</div>
