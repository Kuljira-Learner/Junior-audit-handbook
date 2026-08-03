# 📊 Audit Analytics Portfolio

## การจำลองการตรวจสอบงบการเงิน (Financial Statement Audit Simulation)

> **พัฒนาเพื่อฝึกทักษะการตรวจสอบบัญชี (Audit) และการวิเคราะห์ข้อมูล (Audit Analytics) ด้วย Microsoft Excel และ Python**

---

## 👋 ยินดีต้อนรับ

โปรเจกต์นี้เป็นการจำลองการตรวจสอบงบการเงินของบริษัท **ABC Manufacturing Co., Ltd.** โดยอ้างอิงกระบวนการทำงานของผู้สอบบัญชีในบริษัท Big 4 และบริษัทตรวจสอบบัญชีชั้นนำ

ภายในโปรเจกต์ประกอบด้วยข้อมูลทางบัญชี (Raw Data), เอกสารประกอบการตรวจสอบ (Audit Working Papers), การวิเคราะห์ข้อมูล (Data Analytics) และการจัดทำรายงานสรุปผลการตรวจสอบ เพื่อแสดงขั้นตอนการทำงานของ **Junior Audit Associate** ตั้งแต่เริ่มต้นจนจบกระบวนการตรวจสอบ

---

# 🎯 วัตถุประสงค์ของโครงการ

โครงการนี้จัดทำขึ้นเพื่อ

* ฝึกการจัดทำ Audit Working Papers ตามแนวทางการทำงานจริง
* เรียนรู้การตรวจสอบงบการเงินในแต่ละวงจรบัญชี
* ประยุกต์ใช้ Excel และ Python ในการวิเคราะห์ข้อมูลทางบัญชี
* ฝึกคิด วิเคราะห์ และสรุปผลการตรวจสอบอย่างเป็นระบบ
* สร้าง Portfolio เพื่อใช้สมัครงานด้าน Audit และ Accounting

---

# 🧾 ขอบเขตการตรวจสอบ

โครงการครอบคลุมการตรวจสอบบัญชีในหัวข้อสำคัญ ดังนี้

| ลำดับ | หัวข้อ                           | วัตถุประสงค์                             |
| ----: | -------------------------------- | ---------------------------------------- |
|    01 | 💰 Cash & Bank                   | ตรวจสอบเงินสดและเงินฝากธนาคาร            |
|    02 | 💵 Revenue                       | ตรวจสอบการรับรู้รายได้และ Cut-off        |
|    03 | 📒 Accounts Receivable           | วิเคราะห์ลูกหนี้และการยืนยันยอด          |
|    04 | 📦 Inventory                     | ตรวจสอบสินค้าคงเหลือและการตีราคา         |
|    05 | 🏭 Property, Plant & Equipment   | ตรวจสอบสินทรัพย์ถาวรและค่าเสื่อมราคา     |
|    06 | 💳 Accounts Payable              | ตรวจสอบเจ้าหนี้การค้า                    |
|    07 | 👨‍💼 Payroll                    | ตรวจสอบเงินเดือนและค่าจ้าง               |
|    08 | 🧾 Tax                           | ตรวจสอบภาษีเงินได้นิติบุคคล              |
|    09 | 📈 Financial Statement Analytics | วิเคราะห์งบการเงินและอัตราส่วนทางการเงิน |
|    10 | 🛡️ Internal Control Testing     | ประเมินระบบควบคุมภายใน                   |

---

# 🗂 โครงสร้างโปรเจกต์

```text
Audit-Analytics-Portfolio
│
├── 📄 README.md
│
├── 📁 Raw Data
│   ├── Trial Balance
│   ├── General Ledger
│   ├── Bank Statement
│   ├── Sales Invoice
│   ├── Purchase Invoice
│   ├── Inventory Records
│   └── Payroll Data
│
├── 📁 Working Papers
│   ├── 01-Cash
│   ├── 02-Revenue
│   ├── 03-Accounts Receivable
│   ├── 04-Inventory
│   ├── 05-PPE
│   ├── 06-Accounts Payable
│   ├── 07-Payroll
│   ├── 08-Tax
│   ├── 09-Financial Statement Analytics
│   └── 10-Internal Control
│
├── 📁 Python Notebooks
│
├── 📁 Reports
│
└── 📁 Images
```

---

# 🔍 วิธีการตรวจสอบ (Audit Procedures)

| หัวข้อ                 | วิธีการที่ใช้                                    |
| ---------------------- | ------------------------------------------------ |
| 💰 Cash                | Bank Reconciliation, Cash Count                  |
| 💵 Revenue             | Duplicate Test, Cut-off Testing                  |
| 📒 Accounts Receivable | Aging Analysis, Subsequent Receipt, Confirmation |
| 📦 Inventory           | Roll-forward, Inventory Count, NRV Testing       |
| 🏭 PPE                 | Depreciation Recalculation                       |
| 💳 Accounts Payable    | Supplier Reconciliation                          |
| 👨‍💼 Payroll          | Gross-to-Net Recalculation                       |
| 🧾 Tax                 | Corporate Income Tax Recalculation               |
| 📈 Financial Statement | Ratio Analysis และ Trend Analysis                |
| 🛡️ Internal Control   | Walkthrough และ Control Testing                  |

---

# 📊 Audit Analytics

ภายในโปรเจกต์มีการประยุกต์ใช้เทคนิคการวิเคราะห์ข้อมูลเพื่อสนับสนุนการตรวจสอบบัญชี ได้แก่

✅ Duplicate Invoice Detection

✅ Revenue Cut-off Testing

✅ Journal Entry Testing

✅ Accounts Receivable Aging

✅ Inventory Roll-forward

✅ Financial Ratio Analysis

✅ Trend Analysis

✅ Exception Report

✅ Bank Reconciliation

✅ Dashboard Visualization

---

# 🛠 เครื่องมือที่ใช้

| โปรแกรม         | การใช้งาน                                  |
| --------------- | ------------------------------------------ |
| Microsoft Excel | Audit Working Papers และการวิเคราะห์ข้อมูล |
| Pivot Table     | สรุปข้อมูล                                 |
| Power Query     | จัดเตรียมข้อมูล                            |
| Python          | วิเคราะห์ข้อมูลและตรวจสอบรายการผิดปกติ     |
| Pandas          | Data Cleaning และ Data Analysis            |
| NumPy           | คำนวณข้อมูล                                |
| Matplotlib      | สร้างกราฟและ Dashboard                     |

---

# 📂 Working Papers

| Working Paper | รายละเอียด                               |
| ------------- | ---------------------------------------- |
| A-100         | Cash Lead Schedule & Bank Reconciliation |
| B-100         | Revenue Audit                            |
| C-100         | Accounts Receivable Audit                |
| D-100         | Inventory Audit                          |
| E-100         | Property, Plant & Equipment              |
| F-100         | Accounts Payable Audit                   |
| G-100         | Payroll Audit                            |
| H-100         | Tax Audit                                |
| I-100         | Financial Statement Analytics            |
| J-100         | Internal Control Testing                 |

---

# 📚 มาตรฐานการสอบบัญชีที่เกี่ยวข้อง

* ISA 315 – Risk Assessment
* ISA 330 – Responses to Assessed Risks
* ISA 500 – Audit Evidence
* ISA 520 – Analytical Procedures
* ISA 530 – Audit Sampling
* ISA 550 – Related Parties
* ISA 560 – Subsequent Events
* ISA 570 – Going Concern
* ISA 580 – Written Representations
* ISA 700 – Forming an Opinion

---

# 🎯 ทักษะที่ได้รับ

* Audit Working Papers
* Financial Statement Audit
* Substantive Testing
* Analytical Procedures
* Risk Assessment
* Audit Documentation
* Advanced Microsoft Excel
* Python for Audit Analytics
* Data Cleaning
* Financial Analysis
* Internal Control Evaluation

---

# 📷 ตัวอย่างผลงาน

ภายใน Repository นี้ประกอบด้วย

* 📊 Dashboard การวิเคราะห์ข้อมูล
* 📑 Audit Working Papers
* 📈 Financial Analytics
* 🏦 Bank Reconciliation
* 📦 Inventory Analysis
* 💵 Revenue Testing
* 📒 Accounts Receivable Aging
* 🧮 Python Notebook

---

# ✅ ผลลัพธ์ของโครงการ

หลังจากดำเนินโครงการนี้ ผู้จัดทำสามารถ

* จำลองการตรวจสอบงบการเงินได้ครบทุกขั้นตอน
* จัดทำ Audit Working Papers ตามแนวทางการปฏิบัติงานของผู้สอบบัญชี
* ใช้ Excel และ Python เพื่อวิเคราะห์ข้อมูลทางบัญชี
* ตรวจพบรายการผิดปกติและจัดทำเอกสารประกอบการตรวจสอบ
* สรุปผลการตรวจสอบและจัดทำรายงานอย่างเป็นระบบ

---

# 👩‍💼 ผู้จัดทำ

**Kuljira Pulkham**

Bachelor of Accountancy

Audit Analytics Portfolio

Microsoft Excel • Python • Financial Statement Audit • Data Analytics

---

> **หมายเหตุ:** โครงการนี้จัดทำขึ้นเพื่อการศึกษา การพัฒนาทักษะด้านการตรวจสอบบัญชี และการสร้าง Portfolio สำหรับการสมัครงาน โดยใช้ข้อมูลจำลองเพื่อการเรียนรู้เท่านั้น
