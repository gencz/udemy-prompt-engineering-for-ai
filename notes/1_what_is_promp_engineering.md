# What is Prompt Engineering?

## EN

### Definition

Prompt engineering is the practice of designing clear, specific instructions so an AI model produces more accurate, useful, and relevant outputs.

In simple terms: better instructions usually lead to better results.

### Core elements (from the slide + expanded)

Good prompting usually includes:

1. **Role** — tell the AI what role to take
	- Example: "You are a senior product marketing writer."
2. **Context** — provide background information
	- Example: audience, product, constraints, goals
3. **Task** — state exactly what to do
	- Example: "Write a launch email for Feature X."
4. **Output format** — define the shape of the response
	- Example: bullets, JSON, table, length, tone
5. **Examples / constraints** — show what “good” looks like and set limits
	- Example: include CTA, avoid jargon, max 120 words

### Why prompt engineering matters

- **Higher quality:** responses become more focused and actionable.
- **Consistency:** easier to get repeatable outputs across runs.
- **Efficiency:** fewer retries means less time and lower cost.
- **Control:** easier to enforce brand tone, structure, and compliance.

### Practical prompt template

Use this pattern when you start:

```text
Role: You are a [role].
Context: [important background].
Task: [specific task].
Requirements: [rules, constraints, must-have points].
Output format: [table/bullets/JSON/length/tone].
Quality bar: [how success is judged].
```

### Example: weak vs strong prompt

**Weak prompt**

```text
Explain prompt engineering.
```

**Stronger prompt**

```text
You are an AI instructor for beginners.
Explain prompt engineering in under 150 words.
Use simple language, one real-world example, and 3 bullet-point tips.
End with one common mistake to avoid.
```

### Common mistakes

- Prompt is too vague.
- Missing business context or user audience.
- No output format, so responses become inconsistent.
- Too many goals in one request.
- No constraints (length, tone, rules).

### Quick quality checklist

Before sending your prompt, check:

- Is the task clear and singular?
- Did I include enough context?
- Did I specify output format and length?
- Did I define tone and constraints?
- Did I mention what “good” means?

---

## TH

### ความหมาย

Prompt Engineering คือการออกแบบคำสั่งให้ชัดเจนและเฉพาะเจาะจง เพื่อให้ AI ตอบได้ **ถูกต้อง ใช้งานได้จริง และตรงกับความต้องการ** มากขึ้น

พูดง่าย ๆ คือ: “สั่งดี ผลลัพธ์ก็ดีขึ้น”

### องค์ประกอบหลัก (จากสไลด์ + เพิ่มรายละเอียด)

โดยทั่วไป prompt ที่ดีควรมี:

1. **Role (บทบาท)** — บอกว่าอยากให้ AI เป็นใคร
	- ตัวอย่าง: "คุณคือนักการตลาดสาย B2B ระดับ Senior"
2. **Context (บริบท)** — ให้ข้อมูลพื้นหลังที่จำเป็น
	- เช่น กลุ่มเป้าหมาย เป้าหมายธุรกิจ ข้อจำกัด
3. **Task (งานที่ต้องทำ)** — ระบุสิ่งที่ต้องการให้ชัดเจน
	- ตัวอย่าง: "เขียนอีเมลเปิดตัวฟีเจอร์ใหม่"
4. **Output format (รูปแบบผลลัพธ์)** — กำหนดรูปแบบคำตอบ
	- เช่น bullet, ตาราง, JSON, ความยาว, โทนภาษา
5. **Examples / Constraints (ตัวอย่าง/ข้อกำหนด)** — บอกสิ่งที่ควรมีหรือห้ามมี
	- เช่น ต้องมี CTA, ไม่ใช้ศัพท์เทคนิค, ไม่เกิน 120 คำ

### ทำไม Prompt Engineering สำคัญ

- **คุณภาพดีขึ้น:** คำตอบตรงประเด็นและนำไปใช้ได้มากขึ้น
- **สม่ำเสมอ:** ได้ผลลัพธ์ใกล้เคียงกันในหลายรอบ
- **ประหยัดเวลา/ค่าใช้จ่าย:** แก้ prompt น้อยลง ลองซ้ำน้อยลง
- **ควบคุมได้มากขึ้น:** บังคับโทน รูปแบบ และกติกาได้ง่าย

### เทมเพลตที่ใช้ได้จริง

ใช้โครงนี้เวลาเริ่มเขียน prompt:

```text
Role: คุณคือ [บทบาท]
Context: [ข้อมูลพื้นหลังที่สำคัญ]
Task: [งานที่ต้องการ]
Requirements: [เงื่อนไข/ข้อบังคับ/ประเด็นที่ต้องมี]
Output format: [รูปแบบคำตอบ + ความยาว + โทน]
Quality bar: [นิยามว่าคำตอบที่ดีคืออะไร]
```

### ตัวอย่าง: Prompt อ่อน vs Prompt ที่ดีขึ้น

**แบบอ่อน**

```text
อธิบาย prompt engineering
```

**แบบที่ดีขึ้น**

```text
คุณคือผู้สอน AI สำหรับผู้เริ่มต้น
อธิบาย prompt engineering ความยาวไม่เกิน 150 คำ
ใช้ภาษาง่าย มีตัวอย่างการใช้งานจริง 1 ตัวอย่าง และสรุปเป็น 3 bullet
ปิดท้ายด้วยข้อผิดพลาดที่พบบ่อย 1 ข้อ
```

### ข้อผิดพลาดที่พบบ่อย

- โจทย์กว้างเกินไป
- ไม่ให้บริบทสำคัญ
- ไม่กำหนดรูปแบบผลลัพธ์
- ขอหลายงานเกินไปใน prompt เดียว
- ไม่กำหนดข้อจำกัด (ความยาว โทน กฎ)

### เช็กลิสต์ก่อนส่ง Prompt

- งานชัดเจนและมีเป้าหมายเดียวหรือยัง?
- ให้บริบทเพียงพอหรือยัง?
- ระบุรูปแบบผลลัพธ์และความยาวแล้วหรือยัง?
- ระบุโทนภาษาและข้อจำกัดแล้วหรือยัง?
- บอกเกณฑ์ความสำเร็จของคำตอบแล้วหรือยัง?
