# Version Log / บันทึกเวอร์ชัน

## 2026-11-07 — เพิ่ม Version Log จากต้นฉบับ

- เพิ่ม [Version Log](docs/version-log.md) พร้อมสรุป v0.16.0 และประวัติรุ่นจาก GitHub
- แก้ลิงก์เอกสารให้เปิดใน GitHub ได้ โดยไม่อาศัยรายการแอปที่ยังไม่แปลบนเว็บไซต์
- คงสถานะเอกสารเท่านั้น ยังไม่มีแอป/ตัวติดตั้ง TH หรือผลทดสอบ native ใหม่

## 2026-11-07 — เริ่มต้น repository รุ่นไทย

- เพิ่ม README ภาษาไทย–อังกฤษในโครงสร้างเดียวกับสามแอปรุ่นไทยที่เผยแพร่แล้ว
- เพิ่มคู่มือติดตั้ง Mac/Windows, การเชื่อม Codex/Claude, ข้อมูลต้นทาง และแผนงานคำแปล
- สถานะ: เอกสารและ manifest เท่านั้น ยังไม่มีซอร์สแอปหรือแพ็กเกจ TH ใน repository นี้

## ต้นฉบับ v0.16.0

ต้นทางเผยแพร่ 2026-11-06T20:21:35Z · ตรวจ metadata 07/11/2026 10:59 ICT

- ปรับการประมวลผลข้อมูล keyed-list ในงานร่วมกันให้ใช้ดัชนีภายใน batch — [ต้นทาง](https://github.com/storytold/figcraft/pull/1893)
- แจ้งปฏิเสธรูปแบบเส้นประที่ไม่ถูกต้อง แทนการทิ้งค่าบางส่วนเงียบ ๆ — [ต้นทาง](https://github.com/storytold/figcraft/pull/1899)
- แก้การคงระยะกวาดของวงรีในไฟล์ .fig เมื่อมุมเริ่มต้นหมุนหลายรอบ — [ต้นทาง](https://github.com/storytold/figcraft/pull/1891)

รายการนี้เป็นการเปลี่ยนแปลงของต้นฉบับ ไม่ใช่ changelog ของ binary รุ่นไทย [อ่าน Release Notes ฉบับเต็ม](https://github.com/storytold/figcraft/releases/tag/v0.16.0)

## ประวัติ Release ต้นฉบับที่ตรวจ

- [v0.16.0](https://github.com/storytold/figcraft/releases/tag/v0.16.0) — 2026-11-06T20:21:35Z
- [v0.15.1](https://github.com/storytold/figcraft/releases/tag/v0.15.1) — 2026-11-05T01:48:05Z
- [v0.15.0](https://github.com/storytold/figcraft/releases/tag/v0.15.0) — 2026-11-03T00:56:47Z

## English

2026-11-07: initialized bilingual project documentation, platform-specific installation guidance, upstream metadata and localization status. No application source tree or Thai binary release is included yet. Upstream release changes and Thai project changes are tracked separately.
