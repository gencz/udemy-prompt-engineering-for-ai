# Five Principles of Prompting

## EN

These five principles help you get clearer, more useful, and more consistent AI outputs.

## 1) Give Direction

### What it means

Clearly state what you want the AI to do, including scope, business context, and objective.

### Prompt pattern

"Provide a clear goal, task, and system context."

### Expected response behavior

The AI gives a more focused, relevant response.

### Example

```text
Design end-to-end test cases for FWD's eCommerce insurance purchase journey,
covering plan selection, customer information, payment, and confirmation.
```

### Note

Be specific about system, scope, user flow, and objective.

---

## 2) Specify Format

### What it means

Define the output structure you want (table, checklist, bullet points, step-by-step, JSON, etc.).

### Prompt pattern

"Tell the AI exactly how the answer should be presented."

### Expected response behavior

Output is easier to use immediately and needs less cleanup.

### Example

```text
Summarize the test cases in a table with columns:
Test Case ID, Scenario, Test Steps, and Expected Result.
```

### Note

Very useful when output is going to slides, reports, docs, or working files.

---

## 3) Provide Examples

### What it means

Give sample input/output so the AI understands your preferred style, detail level, and structure.

### Prompt pattern

"Share a sample prompt or expected output as a reference."

### Expected response behavior

Responses align better with your team standards.

### Example

```text
Example format:
Scenario: Payment success
Steps: Customer selects credit card and confirms payment
Expected Result: Payment is completed successfully

Create 5 more test cases in the same format.
```

### Note

Great when your team already has a standard writing pattern.

---

## 4) Evaluate Quality

### What it means

Ask the AI to review and improve output for completeness, clarity, gaps, and edge cases.

### Prompt pattern

"Ask the AI to review, improve, identify gaps, or suggest missing scenarios."

### Expected response behavior

The AI finds missing cases and improves overall quality.

### Example

```text
Review this test suite and check whether it sufficiently covers:
- validation
- payment failures
- session timeout
- duplicate submission

Suggest improvements and add missing negative cases.
```

### Note

Best used after creating a first draft.

---

## 5) Divide Labor

### What it means

Break a large or complex task into smaller parts so AI can handle each part effectively.

### Prompt pattern

"Split the work by flow, module, or step, then ask AI to handle each part."

### Expected response behavior

More organized output with fewer missed areas.

### Example

```text
Break the eCommerce testing scope into 5 modules:
1) Product selection
2) Customer information
3) Underwriting questions
4) Payment
5) Confirmation

Then create test cases for each module.
```

### Note

Useful for complex workflows with multiple modules and dependencies.

---

## Quick EN Checklist

Before sending your prompt, ask:

- Did I clearly define direction and goal?
- Did I specify output format?
- Did I give examples?
- Did I ask for quality review?
- Did I split large tasks into parts?

---

## TH

หลักการทั้ง 5 ข้อนี้ช่วยให้ได้ผลลัพธ์จาก AI ที่ชัดเจน ใช้งานได้จริง และสม่ำเสมอมากขึ้น

## 1) Give Direction (กำหนดทิศทางให้ชัด)

### ความหมาย

บอกให้ชัดว่าอยากให้ AI ทำอะไร ขอบเขตแค่ไหน และเป้าหมายทางธุรกิจคืออะไร

### รูปแบบคำสั่ง

"ระบุ goal, task และ system context ให้ชัด"

### พฤติกรรมผลลัพธ์ที่คาดหวัง

AI จะตอบได้ตรงประเด็นและเกี่ยวข้องกับงานมากขึ้น

### ตัวอย่าง

```text
ช่วยออกแบบ test case สำหรับ eCommerce insurance purchase journey ของ FWD
ให้ครอบคลุม plan selection, customer information, payment และ confirmation
```

### หมายเหตุ

ยิ่งเจาะจงเรื่องระบบ ขอบเขต user flow และวัตถุประสงค์ ผลลัพธ์ยิ่งดี

---

## 2) Specify Format (กำหนดรูปแบบผลลัพธ์)

### ความหมาย

ระบุรูปแบบคำตอบที่ต้องการ เช่น ตาราง checklist bullet step-by-step หรือ JSON

### รูปแบบคำสั่ง

"บอก AI ว่าต้องการให้ตอบในรูปแบบไหน"

### พฤติกรรมผลลัพธ์ที่คาดหวัง

ได้คำตอบที่พร้อมใช้งานทันที แก้น้อยลง

### ตัวอย่าง

```text
สรุป test case เป็นตาราง โดยมีคอลัมน์:
Test Case ID, Scenario, Test Steps, Expected Result
```

### หมายเหตุ

เหมาะมากเมื่อจะนำผลลัพธ์ไปใส่สไลด์ รายงาน หรือเอกสารทีม

---

## 3) Provide Examples (ให้ตัวอย่างอ้างอิง)

### ความหมาย

ให้ตัวอย่างเพื่อให้ AI เข้าใจสไตล์ ระดับรายละเอียด และโครงสร้างที่ต้องการ

### รูปแบบคำสั่ง

"ให้ sample prompt หรือ expected output เป็นตัวอย่าง"

### พฤติกรรมผลลัพธ์ที่คาดหวัง

คำตอบจะใกล้เคียงมาตรฐานงานของทีมมากขึ้น

### ตัวอย่าง

```text
ตัวอย่างรูปแบบ:
Scenario: Payment success
Steps: ลูกค้าเลือกบัตรเครดิตและยืนยันการจ่ายเงิน
Expected Result: ชำระเงินสำเร็จ

สร้างเพิ่มอีก 5 เคสในรูปแบบเดียวกัน
```

### หมายเหตุ

มีประโยชน์มากเมื่อทีมมี template มาตรฐานอยู่แล้ว

---

## 4) Evaluate Quality (ประเมินและยกระดับคุณภาพ)

### ความหมาย

ให้ AI ช่วยตรวจงานว่าครบ ชัดเจน มีช่องว่างหรือ edge case ที่ขาดไปหรือไม่

### รูปแบบคำสั่ง

"ให้ AI review/improve และชี้ช่องว่างที่ยังไม่ครอบคลุม"

### พฤติกรรมผลลัพธ์ที่คาดหวัง

AI ช่วยหาเคสที่ตกหล่นและยกระดับคุณภาพผลลัพธ์

### ตัวอย่าง

```text
ช่วย review test suite นี้ว่า cover เพียงพอหรือยังในเรื่อง:
- validation
- payment failure
- session timeout
- duplicate submission

และเสนอเคสที่ยังขาด โดยเฉพาะ negative case
```

### หมายเหตุ

เหมาะใช้หลังจากมีร่างแรกแล้ว

---

## 5) Divide Labor (แบ่งงานให้เป็นส่วนย่อย)

### ความหมาย

แตกงานใหญ่เป็นโมดูล/ขั้นตอนย่อย เพื่อให้ AI จัดการแต่ละส่วนได้แม่นยำขึ้น

### รูปแบบคำสั่ง

"แยกงานตาม flow/module/step แล้วให้ AI ทำทีละส่วน"

### พฤติกรรมผลลัพธ์ที่คาดหวัง

ได้ผลลัพธ์ที่เป็นระบบมากขึ้น และลดโอกาสตกหล่น

### ตัวอย่าง

```text
แบ่งขอบเขตการทดสอบ eCommerce เป็น 5 ส่วน:
1) Product selection
2) Customer information
3) Underwriting questions
4) Payment
5) Confirmation

จากนั้นสร้าง test case แยกตามแต่ละส่วน
```

### หมายเหตุ

เหมาะกับงานซับซ้อนที่มีหลาย flow หรือหลายโมดูล

---

## เช็กลิสต์สั้น ๆ (TH)

ก่อนส่ง prompt ให้เช็กว่า:

- กำหนดทิศทางและเป้าหมายชัดหรือยัง?
- ระบุรูปแบบผลลัพธ์หรือยัง?
- มีตัวอย่างอ้างอิงหรือยัง?
- ขอให้ประเมินคุณภาพหรือยัง?
- งานใหญ่ถูกแบ่งเป็นส่วนย่อยแล้วหรือยัง?
