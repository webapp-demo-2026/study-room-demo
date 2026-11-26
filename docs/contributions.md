# การมีส่วนร่วม (ตัวอย่างรูปแบบ) — ระบบจองห้องติวของคณะ

> ตัวอย่างวิธีกรอก: ชื่อสมาชิกใช้ "สมาชิก A–D" แทนชื่อจริง ลิงก์ issue ชี้ไปที่ Repository สาธิต `study-room-demo`

| ชิ้นงาน | เจ้าของ | ลิงก์ issue / commit |
|---|---|---|
| Persona + บันทึกสัมภาษณ์ (persona.md) | สมาชิก A | issue "Persona และบันทึกสัมภาษณ์" + commit ที่เพิ่ม `docs/persona.md` |
| Requirement FR/NFR (requirements.md) | สมาชิก B | issue "Requirement" + commit ที่เพิ่ม `docs/requirements.md` |
| Use Case Diagram + คำอธิบาย (use-cases.md, usecase.vsdx) | สมาชิก C | issue "Use Cases" + commit |
| Product Backlog + Sprint 1 บน Project Board | สมาชิก D (Product Owner) | การ์ด US-01–US-10 บนกระดาน |
| Context Diagram + DFD Level 0 | สมาชิก B และ C | commit ที่เพิ่ม `docs/context.vsdx`, `docs/dfd0.vsdx` |
| User Flow + Wireframe | สมาชิก A | commit ที่เพิ่ม `docs/wireframes/` |
| Figma Prototype | สมาชิก A และ D | ลิงก์ Prototype "can view" |
| แผนและผลทดสอบ Usability | สมาชิก C (Scrum Master) | commit ที่เพิ่ม `docs/usability-test.md` |

## คำอธิบายรายคน (คนละ 3–5 บรรทัด) — ตัวอย่าง 1 คน
สมาชิก B: เขียน FR-01–FR-10 จากบันทึกสัมภาษณ์ P1–P3 และกฎที่เจ้าหน้าที่ใช้อยู่ แต่ละข้อมีวิธีตรวจแบบผ่าน/ไม่ผ่าน
NFR ทั้ง 6 ข้อเลือกหมวดตาม ISO/IEC 25010:2023 และใส่ตัวเลขที่วัดได้ ข้อที่แก้หลังเพื่อนตรวจคือ NFR-01 ซึ่งเดิมเขียนว่า "ค้นหาเร็ว"
ร่วมกับสมาชิก C ตรวจ balancing ระหว่าง Context Diagram กับ DFD Level 0 ทีละเส้น
