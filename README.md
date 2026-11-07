# DeckCraft TH — งานนำเสนอภาษาไทย

โครงการเตรียมรุ่นภาษาไทยอิสระของ [DeckCraft โดย storytold / ArtCraft](https://github.com/storytold/deckcraft) ในชุด [วันละ Craft / One Per Craft](https://github.com/tapanapon-com/one-per-craft) เอนจินและคุณสมบัติหลักเป็นผลงานของผู้พัฒนาต้นฉบับ

[ดาวน์โหลดต้นฉบับ v0.16.0](https://github.com/storytold/deckcraft/releases/tag/v0.16.0) · [คู่มือ Mac](docs/install-macos.md) · [คู่มือ Windows](docs/install-windows.md) · [Version Log](docs/version-log.md) · [English](#english)

## สถานะรุ่นไทย

**ยังไม่เผยแพร่แอปหรือตัวติดตั้งภาษาไทย** Repository นี้เริ่มต้นด้วย README คู่มือ และ manifest อ้างอิงต้นทาง ยังไม่ได้รวมซอร์สโค้ดแอปหรือคำแปลที่พร้อมแจก การสร้าง repo ไม่ใช่การประกาศว่าแอปรุ่นไทยเสร็จแล้ว

| รายการ | สถานะ |
| --- | --- |
| Release ต้นฉบับที่ตรวจ | [v0.16.0](https://github.com/storytold/deckcraft/releases/tag/v0.16.0) |
| แพ็กเกจภาษาไทยของ Tapanapon | ยังไม่เผยแพร่ |
| เนื้อหา repo นี้ | เอกสารและข้อมูลอ้างอิงต้นทาง |
| ตรวจ Release ล่าสุด | 07/11/2026 22:57 ICT |

ลิงก์ดาวน์โหลดด้านบนเป็นไฟล์ต้นฉบับของ storytold / ArtCraft ไม่ใช่ตัวติดตั้ง TH และอาจมีภาษาที่รองรับต่างกันตามรุ่น อ่าน [ข้อมูลต้นทาง](UPSTREAM.md) และ [สถานะคำแปล](docs/localization-th.md)

## ทำอะไรได้บ้าง

ความสามารถต่อไปนี้เป็นของแอปต้นฉบับ ไม่ใช่ผลการพัฒนารุ่นไทยเพิ่มเติม:

- สร้างสไลด์ด้วย themes, layouts, ข้อความ ภาพ ตาราง และกราฟ
- เพิ่ม transitions และ animations
- เปิดหรือบันทึก PPTX และนำเสนอแบบเต็มหน้าจอ

## ภาพหน้าจอ

ดูภาพและตัวอย่างจาก [README ต้นฉบับ](https://github.com/storytold/deckcraft/blob/main/README.md) ขณะนี้ยังไม่มีภาพหน้าจอแอปรุ่นไทยที่ยืนยันสำหรับ repo นี้ จึงไม่ใช้ภาพจำลองเป็นหลักฐานว่าแปลเสร็จแล้ว

## ดาวน์โหลดและติดตั้งบน Mac

1. เปิด [GitHub Release ต้นฉบับ v0.16.0](https://github.com/storytold/deckcraft/releases/tag/v0.16.0) แล้วขยาย Assets
2. เลือกไฟล์ `macos-universal.dmg` ตามข้อกำหนดระบบของต้นฉบับ
3. บันทึกงานและปิดแอปเดิม เปิด DMG แล้วลากแอปเข้า Applications
4. เปิดจาก Applications และตรวจข้อมูลภาษาในแอปรุ่นนั้น

อ่าน [คู่มือ Mac ของแอปนี้](docs/install-macos.md) ไฟล์ Source code ZIP เป็นซอร์สสำหรับ build ไม่ใช่ตัวติดตั้ง

## ดาวน์โหลดและติดตั้งบน Windows

1. เปิด [Release ต้นฉบับ](https://github.com/storytold/deckcraft/releases/tag/v0.16.0) แล้วเลือก Windows ให้ตรงสถาปัตยกรรมเครื่อง
2. ใช้ MSI เพื่อติดตั้ง หรือ Portable ZIP แล้ว Extract All ก่อนเปิด `.exe`
3. เก็บไฟล์ในชุด Portable ไว้ครบ และตรวจ checksum ของรุ่นเดียวกัน

อ่าน [คู่มือ Windows ของแอปนี้](docs/install-windows.md) ปุ่มหลักอ้างอิง Windows x64; สถาปัตยกรรมอื่นดูใน Assets ของต้นทาง

## เชื่อมกับ Codex หรือ Claude

ต้นฉบับมี CLI/MCP สำหรับเรียกเครื่องมือของแอป อ่าน [คู่มือเชื่อม AI](docs/automation.md) โดยตรวจ CLI และ arguments ของรุ่นที่ติดตั้งก่อน โหมด headless ทำงานแยกจากหน้าต่าง GUI ที่เปิดอยู่

## รุ่นต้นฉบับนี้เปลี่ยนอะไร?

สรุปบางรายการของ v0.16.0 จาก Release Notes ต้นทาง:

- ปุ่ม Preview ของ transition เริ่มเล่นตัวอย่างจากสไลด์ก่อนหน้า — [ต้นทาง](https://github.com/storytold/deckcraft/pull/1679)
- รักษาขนาด bullet ที่ผู้สร้างกำหนดเป็นหน่วย points — [ต้นทาง](https://github.com/storytold/deckcraft/pull/1588)
- เพิ่มป้ายชื่อให้ตัวเลือกของเอฟเฟกต์แอนิเมชัน — [ต้นทาง](https://github.com/storytold/deckcraft/pull/1579)

อ่าน [CHANGELOG](CHANGELOG.md) และ [Version Log ต้นฉบับ](docs/version-log.md) การเปลี่ยนแปลงข้างต้นยังไม่ได้ถูกอ้างว่าเข้าแพ็กเกจ TH แล้ว

## ขอบเขตคำแปลและการตรวจสอบ

ยังไม่มีจำนวนคำแปล ผล build หรือผลทดสอบแอปรุ่นไทยที่ประกาศสำหรับ repository นี้ การตรวจในรอบเริ่มต้นครอบคลุมความครบของเอกสาร รูปแบบ manifest และลิงก์ที่เลือกจาก Release ต้นทางเท่านั้น

เมื่อเริ่มนำซอร์สแอปเข้ามาพัฒนาต่อ ต้องบันทึก revision ต้นทาง ตรวจคำแปล/ฟอนต์ ทดสอบ และตรวจแพ็กเกจก่อนเผยแพร่รุ่นไทย ดู [แผนงาน](docs/localization-th.md)

## ต้นฉบับ เครดิต และสัญญาอนุญาต

- ต้นฉบับ: [DeckCraft โดย storytold / ArtCraft](https://github.com/storytold/deckcraft)
- คำอธิบายและการติดตามรุ่นไทย: Tapanapon / วันละ Craft
- เอกสารที่สร้างใหม่ใน repo นี้ใช้ [MIT](LICENSE) ส่วนโค้ด ฟอนต์ ภาพ และเครื่องหมายการค้าของต้นฉบับคงสิทธิ์และใบอนุญาตของเจ้าของ ไม่ได้เปลี่ยนเป็น MIT ตามเอกสารนี้
- เป็นโครงการอิสระ ไม่ใช่รุ่นทางการหรือได้รับการรับรองจากผู้สร้าง DeckCraft/ArtCraft

## English

DeckCraft TH is an independent Thai-edition preparation project for [DeckCraft by storytold / ArtCraft](https://github.com/storytold/deckcraft). The upstream contributors created the engine and application features. Tapanapon / One Per Craft maintains these Thai/English project notes and upstream references.

### Features and workflow

Build slides with themes, layouts, media, charts and animations, work with PPTX and present full screen. See the upstream README for supported workflows and limitations. Source capabilities are not a claim of completed Thai localization.

### Downloads and installation

The verified upstream release is [v0.16.0](https://github.com/storytold/deckcraft/releases/tag/v0.16.0). Mac users can select the upstream Universal DMG; Windows users can select the matching MSI or portable ZIP in Assets. See [Mac instructions](docs/install-macos.md) and [Windows instructions](docs/install-windows.md). Source archives require a build.

### Coverage and validation

**This repository currently contains documentation and an upstream manifest only. It does not yet contain a localized application source tree or Thai installers.** No Thai translation count, native test result or binary release is claimed. The existing three published Thai apps are listed in the [central hub](https://github.com/tapanapon-com/one-per-craft).

### Source and credits

Original application by storytold / ArtCraft. This is not an official or endorsed distribution. New project documentation is MIT-licensed; upstream code, assets, fonts and trademarks retain their own terms. Read [UPSTREAM](UPSTREAM.md) and [NOTICE](NOTICE.md).
