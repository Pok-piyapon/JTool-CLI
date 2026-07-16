# 🚀 JTOOL CLI

> เครื่องมือ CLI คู่ใจที่จะช่วยเปลี่ยนโค้ด Java สุดซับซ้อนของบริษัท ให้กลายเป็นเรื่องกล้วย ๆ สำหรับ Junior Developer!

**JTOOL CLI** เป็นเครื่องมือ Command Line Interface (CLI) ที่พัฒนาด้วยภาษา Java ออกแบบมาเพื่อช่วยลดช่องว่างและประหยัดเวลาให้กับนักพัฒนาซอฟต์แวร์ระดับเริ่มต้น (Junior Developers) ในการทำความเข้าใจ Codebase ขนาดใหญ่ขององค์กร ช่วยเซฟพลังงานสมองของพี่ ๆ ซีเนียร์ และลดความมึนตึ้บของน้อง ๆ ได้เป็นอย่างดี

---

## ✨ Features (ความสามารถหลัก)

* 🔍 **Automated Code Review:** ช่วยรีวิวโค้ดเบื้องต้น วิเคราะห์โครงสร้าง และให้คำแนะนำตาม Best Practices เพื่อให้โค้ดของน้อง ๆ สอดคล้องกับมาตรฐานของทีม
* 📝 **Project Summarization:** สรุปภาพรวมของโปรเจกต์ ออกมาเป็นใจความสำคัญ ช่วยให้เห็นว่าโมดูลไหนทำหน้าที่อะไร และเชื่อมโยงกันอย่างไร
* 📄 **Smart Docs Generation:** สร้างเอกสารประกอบการอธิบายโค้ด (Documentation) ที่อ่านง่าย ภาษาเป็นมิตร ไม่ต้องเสียเวลานั่งงมอ่านโค้ดทีละบรรทัด

---

## 🛠️ Prerequisites (สิ่งที่ต้องมีก่อนเริ่ม)

ก่อนที่จะใช้งาน JTOOL CLI เครื่องของคุณต้องติดตั้งสิ่งเหล่านี้ก่อน:

* **Java Development Kit (JDK):** เวอร์ชัน 17 ขึ้นไป
* **Build Tool:** Maven หรือ Gradle (ขึ้นอยู่กับว่าใช้ตัวไหนในโปรเจกต์)

---

## 📦 Installation (การติดตั้ง)

1. **Clone โปรเจกต์นี้ลงเครื่อง:**
   ```bash
   git clone [https://github.com/your-organization/jtool-cli.git](https://github.com/your-organization/jtool-cli.git)
   cd jtool-cli

## 🛠️ Tech Stack

| Category | Technology |
| :------- | :--------- |
| 🤖 AI | **DeepSeek API** (Primary), **OpenAI API** (Fallback) |
| 📊 Diagram Rendering | **Mermaid.js** (Rendered in-browser with JavaScript) |
| 📝 Documentation | **HTML + Bootstrap 5** (Primary), **docxjs** (Optional) |
| 🔧 Java Parser | **JavaParser** |
| 💻 CLI Framework | **Picocli** |
| 📦 Build Tool | **Maven** |
| 🧪 Testing | **JUnit 5** |

## ✨ Optional Features

- 🤝 Collaborative development over a local network using the host's local IP
- 📄 Export documentation as HTML or DOCX
- 🔄 Automatic AI provider failover (DeepSeek → OpenAI)
- 📊 Interactive Mermaid diagram rendering

## 📦 จำนวน Modules ใน JTOOL CLI
มีทั้งหมด 9 Modules แบ่งเป็น 2 กลุ่ม:

#🧩 6 Core Modules (ทำงานหลัก)
	Module	หน้าที่
 - jtool-cli	รับคำสั่งจากผู้ใช้ (Picocli)
 - jtool-parser	อ่านและแปลงโค้ด Java เป็น AST (JavaParser)
 - jtool-ai	เรียก AI วิเคราะห์โค้ด (DeepSeek API)
 - jtool-diagram	สร้าง Diagram ด้วย Mermaid syntax
 - jtool-docs	สร้างเอกสาร HTML 3 ระดับ
 - jtool-report	สร้างรายงาน Code Review
#⚙️ 3 Support Modules (ตัวช่วย)
	Module	หน้าที่
 - jtool-config	จัดการตั้งค่าและ API keys
 - jtool-cache	เก็บผลลัพธ์ซ้ำ ลดค่าใช้จ่าย AI
 - jtool-export	บันทึกไฟล์เอกสาร/รายงาน

