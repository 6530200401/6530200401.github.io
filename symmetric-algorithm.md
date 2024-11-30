# Symmetric Algorithm

- **CISSP Glossary** [https://www.isc2.org/certifications/cissp/cissp-student-glossary#s](https://www.isc2.org/certifications/cissp/cissp-student-glossary#s) นิยามไว้ว่า
  - "Operate with a single cryptographic key that is used for both encryption and decryption of the message."
  - **ChatGPT** แปลได้ว่า "ทำงานด้วยกุญแจเข้ารหัสเพียงดอกเดียวที่ใช้ทั้งในการเข้ารหัสและถอดรหัสข้อความ"
  - **Gemini** แปลไว้ว่า "ทำงานโดยใช้กุญแจเข้ารหัสเพียงกุญแจเดียว ซึ่งใช้ทั้งในการเข้ารหัสและถอดรหัสข้อความ"

---

- **NIST Glossary** [https://csrc.nist.gov/glossary/term/symmetric_cryptography](https://csrc.nist.gov/glossary/term/symmetric_cryptography)
  - คำศัพท์ที่ใช้จะเป็น Symmetric Cryptography แทน Symmetric Algorithm ซึ่งนิยามไว้ว่า
  - "A cryptographic algorithm that uses the same secret key for its operation and, if applicable, for reversing the effects of the operation"
  - **ChatGPT** แปลได้ว่า "อัลกอริทึมการเข้ารหัสที่ใช้กุญแจลับเดียวกันทั้งสำหรับการทำงานและ (ถ้ามี) สำหรับการย้อนกลับผลลัพธ์ของการทำงาน"
  - **Gemini** แปลไว้ว่า "อัลกอริทึมการเข้ารหัสที่ใช้กุญแจลับเดียวกันในการดำเนินการ และหากมีการย้อนกลับกระบวนการ ก็จะใช้กุญแจลับเดียวกันนี้"

---

# สรุปเองได้ว่า
  - "Symmetric algorithm คือ อัลกอริทึมที่ใช้เข้ารหัสและถอดรหัส โดยจะใช้กุญแจเดียวกันทั้งการเข้าและถอดรหัส"

# การใช้ Symmetric Algorithm ในชีวิตประจำวัน
  - การเข้ารหัสข้อความ อย่างเช่น การส่งข้อความในแอป Line หรือ Telegram เป็นต้น มีการใช้ Symmetric Algorithm เพื่อป้องกันการดักฟังจากผู้ประสงค์ไม่ดี
  - การเข้ารหัสธุรกรรมออนไลน์ อย่างเช่น เมื่อมีการทำธุรกรรมออนไลน์ อย่างการโอนเงิน เป็นต้น จะมีการส่งข้อมูลส่วนตัวและข้อมูลทางการเงินไปด้วย เพื่อความปลอดภัยจึงมีการใช้ Symmetric Algorithm เพื่อป้องกันคนมาขโมยข้อมูลของเรา
