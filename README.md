# 🎮 ผจญภัยเมืองผังงาน Flowgorithm (Flowgorithm IF-THEN Adventure)

[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Online-brightgreen?logo=github)](https://pages.github.com/)
[![HTML5](https://img.shields.io/badge/Tech-HTML5_Canvas_&_CSS3-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-yellow?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PWA](https://img.shields.io/badge/PWA-Ready-blueviolet?logo=pwa)](https://web.dev/progressive-web-apps/)
[![Target Audience](https://img.shields.io/badge/Target-ม.1_ถึง_ม.3_(Grade_7--9)-blue)](https://www.scimath.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

สื่อการเรียนรู้เชิงปฏิสัมพันธ์ (Interactive Web Game) รูปแบบ Platformer เพื่อสอนการออกแบบผังงานแบบมีเงื่อนไข (**IF-THEN, AND, OR**) และชนิดข้อมูลตัวแปรตามมาตรฐานโปรแกรม **Flowgorithm** สำหรับนักเรียนชั้นมัธยมศึกษาปีที่ 1 - 3 (วิชาวิทยาการคำนวณ)

---

## 🌟 จุดเด่นของเกม (Key Highlights)

- 📱 **เล่นบนโทรศัพท์มือถือได้อย่างเสถียร 100% (Ultra-stable Mobile Playability):**
  - **Multi-Touch Gamepad:** แผงควบคุม D-Pad สไลด์นิ้วซ้าย-ขวาได้ต่อเนื่อง และปุ่มกระโดดขนาดใหญ่
  - **Haptic Vibration:** ระบบสั่นตอบสนองเบาๆ ที่ปลายนิ้วเมื่อกระโดดหรือกดปุ่ม
  - **Auto-Scale Virtual Resolution:** ไม่ว่าจอมือถือจะยาว 20:9 หรือ 16:9 ฉากและพื้นดินจะอยู่พอดีกับระดับสายตาเสมอ
  - **Retina / Hi-DPI Display:** ตัวอักษรและกราฟิกคมชัดระดับ HD ทุกความละเอียด
  - **Delta-Time (dt) Physics:** รองรับจอรีเฟรชเรท 60Hz, 90Hz, 120Hz ลื่นไหลไม่กระตุก ตัวละครไม่ตกทะลุพื้น
  - **ปุ่ม Fullscreen (⛶):** ซ่อนแถบเบราว์เซอร์ เล่นได้เต็มจอเสมือน Native App
  - **Web Audio Unlocked:** เสียงสังเคราะห์ด้วย Web Audio API ทำงานเสถียรบน iOS Safari และ Android Chrome
  - **LocalStorage Auto-Save:** จดจำชื่อผู้เล่น ตัวละคร คะแนนสูงสุด และการเปิด/ปิดเสียงไว้เสมอ

- 💻 **รองรับการขึ้น GitHub Pages ทันที (GitHub Ready):**
  - รวมโค้ดเป็นระบบ Zero-Dependency ไม่ต้องติดตั้งโปรแกรมหรือเซิร์ฟเวอร์
  - มีไฟล์ `.nojekyll` ป้องกัน Jekyll parser รบกวนการทำงาน
  - รองรับ PWA (`manifest.json` + `sw.js`) สามารถกด **"Add to Home Screen"** บนมือถือเพื่อเล่นแบบออฟไลน์ได้

- 📊 **จำลองสัญลักษณ์ Flowgorithm ด้วย Pure CSS:**
  - `Main` / `End`: แคปซูลมน
  - `Declare`: สี่เหลี่ยมผืนผ้าสีเหลืองพาสเทล พร้อมระบุ Data Type (`Integer`, `Real`, `String`, `Boolean`)
  - `Input`: สี่เหลี่ยมด้านขนานสีฟ้า
  - `Assign`: สี่เหลี่ยมผืนผ้าสีส้มทอง
  - `Output`: สี่เหลี่ยมด้านขนานสีเขียว
  - `If`: สี่เหลี่ยมข้าวหลามตัด แยกกิ่ง `True` และ `False`
  - พร้อมหน้าต่าง **Flowgorithm Pseudocode** เปรียบเทียบซอร์สโค้ดจริง

---

## 📚 เนื้อหาบทเรียนที่ครอบคลุม (ม.1 - ม.3)

1. **การประกาศตัวแปร (Declare) & ชนิดข้อมูล:** `Integer` (จำนวนเต็ม), `Real` (ทศนิยม), `String` (ข้อความ), `Boolean` (`true`/`false`)
2. **ตัวดำเนินการเปรียบเทียบใน Flowgorithm:** ความแตกต่างระหว่างการกำหนดค่า `=` และการเปรียบเทียบ `==` รวมถึง `!=`, `>`, `<`, `>=`, `<=`
3. **ตัวดำเนินการทางตรรกะ (Logical Operators):** `and` (จริงทั้งคู่), `or` (จริงอย่างน้อยหนึ่ง), `not` (กลับค่าความจริง)
4. **การคำนวณทางคณิตศาสตร์:** การใช้ Modulo `%` เพื่อตรวจเลขคู่/เลขคี่
5. **การเชื่อมข้อความ (String Concatenation):** การใช้เครื่องหมาย `&` ในบล็อก Output
6. **กฎการตั้งชื่อตัวแปร (Naming Rules):** ตัวอักษรภาษาอังกฤษ, ห้ามเว้นวรรค, ห้ามใช้อักขระพิเศษ
7. **โครงสร้างทางเลือกซ้อน (Nested If):** การตัดเกรด 4, 3, 2, 1, 0
8. **การเขียนช่วงเงื่อนไข (Range Condition):** เช่น `(score >= 50) and (score < 60)`
9. **ตารางไล่ค่าตัวแปร (Trace Table) & Debugging:** การตรวจจับข้อผิดพลาด `Type Mismatch` และ `Syntax Error`

---

## 🕹️ มินิเกมและระบบบอส

- 🧩 **มินิเกมจัดเรียงผังงาน (Flowchart Sequencing):**
  - ด่าน 1: ระบบตัดเกรดผ่าน/ไม่ผ่าน (`Main` ➔ `Declare` ➔ `Input` ➔ `If` ➔ `Output` ➔ `End`)
  - ด่าน 2: ระบบคำนวณราคาส่วนลดสินค้า (`Declare Real` ➔ `Input price` ➔ `If price >= 500` ➔ `Assign total` ➔ `Output`)
- 👾 **ศึกบอส Compiler Bugzilla:**
  - ตอบคำถามต่อเนื่อง 5 ข้อ เพื่อหา Bug ในผังงาน (เช่น ลืมบล็อก `Declare`, ใช้ `=` แทน `==`, ต่อสายสลับกิ่ง True/False) เพื่อกำจัดบั๊ก

---

## 🚀 วิธีเปิดใช้งานและนำขึ้น GitHub Pages

### 1. เล่นบนเครื่องคอมพิวเตอร์ / สมาร์ตโฟนทันที
- เปิดไฟล์ `index.html` ด้วยเว็บเบราว์เซอร์ใดก็ได้ (Chrome, Safari, Edge, Firefox)

### 2. นำขึ้น GitHub Pages ฟรีใน 3 ขั้นตอน
1. สร้าง New Repository บน [GitHub](https://github.com/) (เช่น `flowgorithm-game`)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไป:
   - `index.html`
   - `.nojekyll`
   - `manifest.json`
   - `sw.js`
   - `README.md`
3. ไปที่แท็บ **Settings** ➔ **Pages** ➔ ที่หัวข้อ **Build and deployment**:
   - Source: เลือก **Deploy from a branch**
   - Branch: เลือก **main** หรือ **master** โฟลเดอร์ `/ (root)` แล้วกด **Save**
4. รอระบบประมวลผลประมาณ 1-2 นาที คุณจะได้ URL เว็บไซต์ เช่น:
   `https://<your-username>.github.io/flowgorithm-game/` ส่งให้นักเรียนเล่นได้ทั่วโลก!

---

## 🎮 การควบคุม (Controls)

| อุปกรณ์ | การเดินซ้าย-ขวา | การกระโดด | เปิด/ปิดเสียง | ขยายเต็มจอ |
|:---|:---|:---|:---|:---|
| **สมาร์ตโฟน / แท็บเล็ต** | แผงปุ่มสัมผัส ◀ ▶ | ปุ่มสัมผัส ▲ | ปุ่ม 🔊 บนแถบ HUD | ปุ่ม ⛶ บนแถบ HUD |
| **คอมพิวเตอร์** | ปุ่ม `A` / `D` หรือ `←` / `→` | ปุ่ม `Spacebar` หรือ `W` / `↑` | ปุ่ม 🔊 บนแถบ HUD | ปุ่ม ⛶ บนแถบ HUD |

---

## 📄 ใบอนุญาต (License)
โครงการนี้เผยแพร่ภายใต้ใบอนุญาต [MIT License](LICENSE) สามารถนำไปใช้ในการเรียนการสอน ปรับแต่ง และพัฒนาต่อยอดได้อย่างอิสระ
