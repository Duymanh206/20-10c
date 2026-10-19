# 🌸 Món Quà Tương Tác 3D Ngày Phụ Nữ Việt Nam 20/10 ✨

Một trang web 3D tương tác lãng mạn, tinh tế và ngọt ngào được xây dựng bằng **HTML5, CSS3, Three.js và JavaScript Vanilla**, dành tặng ngày Phụ nữ Việt Nam 20/10.

Trang web mang phong cách điện ảnh huyền ảo, không gian ngân hà lung linh ngập tràn cánh hoa hồng rơi, đom đóm phát sáng, đóa hoa 3D hoành tráng và các lời chúc ấm áp.

---

## 🌟 Trải Nghiệm & Tính Năng Nổi Bật

### 1. 🌌 Bối Cảnh Vũ Trụ Lãng Mạn (Dreamy Cosmic Sky)
- Bầu trời đêm mộng mơ chuyển sắc từ tím than đậm (`#07040a`) sang tím hồng pastel ngọt ngào.
- Hiệu ứng sao băng chao liệng, bầu trời sao lấp lánh và hơn 90 chú đom đóm dập dờn êm dịu.
- Cơn mưa cánh hoa hồng 3D rơi lả tả xoay lượn tự nhiên theo luồng không khí.
- Phông chữ nghệ thuật Google Font `'Mali'` nét tròn mềm mại, hỗ trợ tiếng Việt trọn vẹn.

### 2. 🌹 Giai Đoạn 1: Bó Hoa Ma Thuật (Màn hình mở đầu)
- Bó hoa hồng phấn bồng bềnh lơ lửng ở tâm màn hình với hào quang dịu nhẹ và hiệu ứng 3D Parallax mượt mà theo cử chỉ chuột / con quay hồi chuyển trên điện thoại.
- **Tương tác chạm (Click / Tap):**
  - Tự động phát nhạc nền lãng mạn (có nút bật/tắt âm thanh tiện lợi ở góc phải màn hình).
  - 6 từ khóa dễ thương (*"Xinh đẹp"*, *"Rạng rỡ"*, *"Vui vẻ"*, *"Hạnh phúc"*, *"May mắn"*, *"Bình an"*) bay lên tỏa quanh bó hoa với hiệu ứng nảy mềm mại.
  - Hướng dẫn đổi thành: *"Ấn giữ bó hoa để mở điều bất ngờ"*.
- **Tương tác ấn giữ (Press & Hold):**
  - Vòng sáng tiến trình SVG chuyển động quanh bó hoa trong 1.5 giây, bó hoa rung nhẹ tích tụ năng lượng ánh sáng.
  - Hiệu ứng lóe sáng điện ảnh (*Anamorphic Star Flare*) bung nở rực rỡ để đưa người xem vào không gian 3D.

### 3. ✨ Giai Đoạn 2: Đóa Hoa 3D Rực Rỡ & Ngân Hà Điều Ước
- Không gian 3D tương tác 360 độ (cho phép kéo/vuốt xoay đa chiều, chụm 2 ngón tay hoặc cuộn chuột để phóng to/thu nhỏ mượt mà).
- **Trung tâm không gian:** Bó hoa hồng 3D lộng lẫy bọc giấy gói hồng pastel buộc nơ lụa mềm mại, có hiệu ứng bung nở phóng to nhẹ (*Zoom-in Pulse*) rồi ổn định uyển chuyển.
- **Vành đai Ngân hà bao quanh:**
  - **12 tấm thiệp kính mờ pha lê (Glassmorphism Cards):** Thiết kế sắc nét, viền neon phát sáng, nhấp vào để xem chi tiết từng lời chúc ngọt ngào.
  - **6 câu chúc 3D Neon Glow phát sáng:** Bay lơ lửng ở quỹ đạo thoãng đãng, không che khuất đóa hoa trung tâm.
- Dưới đáy màn hình có hướng dẫn tinh tế: *"Kéo để xoay không gian • Chụm hai ngón để phóng to"*.

### 4. 💌 Bức Thư Tình Cảm (UI Popup Overlay)
- Nút phong bì thư ở góc phải màn hình với hiệu ứng nhịp đập thu hút (*Heartbeat Animation*).
- Thiệp hồng kem ấm áp (`#fff0f3`), bo góc tinh tế với hiệu ứng gõ chữ máy tính (*Typewriter Effect*):
  - **Tiêu đề:** *"Thân gửi,"*
  - **Nội dung:** *"Nhân ngày 20/10, mình có một món quà nhỏ tự tay chuẩn bị dành tặng cho bạn. Chúc bạn luôn xinh đẹp, rạng rỡ, ngập tràn niềm vui và luôn nở nụ cười thật tươi trên môi. Mong rằng mọi điều tốt đẹp và dịu dàng nhất sẽ luôn đồng hành cùng bạn trên chặng đường phía trước!"*
  - **Chữ ký:** *"Hoàng Duy Mạnh ✨"*

---

## 🛠️ Cấu Trúc Thư Mục

```text
├── index.html           # Trang web chính (chứa toàn bộ giao diện, hiệu ứng 3D & logic)
├── assets/
│   ├── bouquet.jpg      # Ảnh bó hoa màn hình mở đầu
│   ├── bouquet_glow.png # Texture bó hoa 3D tách nền trong suốt chất lượng cao
│   ├── music.mp3        # File nhạc nền mặc định
│   └── README.md        # Hướng dẫn thay thế tài nguyên
└── README.md            # Tài liệu dự án
```

---

## ⚙️ Tùy Biến Nhanh (`CONFIG`)

Toàn bộ nội dung lời chúc, hình ảnh và bài hát được đặt ở đầu thẻ `<script>` trong file `index.html`:

```javascript
const CONFIG = {
    title: "Chúc Mừng Ngày Phụ Nữ Việt Nam 20/10 🌸",
    bouquetImage: 'assets/bouquet.jpg',
    musicUrl: 'assets/THẾ GIỚI CỦA ANH.mp3', // Bài hát Thế Giới Của Anh

    // 6 từ khóa bay lên khi chạm bó hoa
    keywords: [
        { text: "Xinh đẹp", icon: "🌸" },
        { text: "Rạng rỡ", icon: "✨" },
        { text: "Vui vẻ", icon: "☀️" },
        { text: "Hạnh phúc", icon: "💖" },
        { text: "May mắn", icon: "🍀" },
        { text: "Bình an", icon: "🕊️" }
    ],

    // 6 câu chúc 3D Neon bay lơ lửng
    greetings: [
        "Chúc một nửa thế giới 20/10 ngập tràn niềm vui ✨",
        "Luôn giữ nụ cười tươi và rạng rỡ thế này nhé",
        "Mong mọi điều dịu dàng nhất sẽ đến với bạn",
        "Chúc bạn ngày hôm nay và 365 ngày đều hạnh phúc 🌸",
        "Mong rằng cuộc sống luôn đối xử dịu dàng với bạn",
        "Chúc bạn luôn gặp nhiều may mắn và bình an"
    ],

    // Bức thư tình cảm
    letter: {
        title: "Thân gửi,",
        content: "...",
        signature: "Hoàng Duy Mạnh ✨"
    }
};
```

---

## 🚀 Triển Khai (Deploy)

Dự án là trang tĩnh thuần (`Vanilla HTML/CSS/JS`) nên có thể triển khai miễn phí và tức thì trên:
- **GitHub Pages:** Vào mục `Settings` > `Pages` > chọn nhánh `main` và thư mục `/ (root)` > `Save`.
- **Vercel / Netlify:** Kết nối repository `Duymanh206/20-10c` và bấm `Deploy`.

---

💖 Chúc một nửa thế giới có một ngày 20/10 thật hạnh phúc, rạng rỡ và tràn đầy niềm vui!
