**🔙[HOME](README.md)**

# Security Control

## 2FA by using Google Prompt
### Two-Factor Authentication
- something you know : ชื่อ Gmail และ รหัสผ่าน
- something you have : โทรศัพท์มือถือ

![Mail Name](/img/security-control/mail-name.PNG)
![Mail Password](/img/security-control/mail-password.PNG)
![Mail 2FA](/img/security-control/mail-2FA.PNG)
![Mail 2FA](/img/security-control/mail-verify.png)
#### ปล. ขออนุญาต sensor ชื่อ gmail กับ โทรศัพท์มือถือที่ใช้ ครับ

## Control Functions : Preventative
- การเปิดการยืนยันแบบ 2 ขั้นตอน ของ Google ก็คือการป้องกันคนอื่นเข้ามาใช้บัญชีของเราโดยไม่ได้รับอนุญาต โดย 2FA ที่เลือกใช้งานคือ Google Prompt โดยการทำงานของ Google Prompt คือ การที่เรากรอกชื่อ Gmail และรหัสผ่าน (something you know) หลังจากนั้นจะมีข้อความหรือหน้าต่างของ Google ขึ้นมาในโทรศัพท์มือถือของเรา (something you have) จะมีให้กดเลือก "ไม่อนุญาต" กับ "ใช่ ฉันเอง" ถ้าหากเราไม่ใช่คนที่เข้าสู่ระบบก็สามารถกด "ไม่อนุญาต" ได้เลย ระบบก็จะไม่ให้เข้าสู่ระบบ แต่ถ้าเราเป็นคนเข้าสู่ระบบก็กด "ใช่ ฉันเอง" ได้เลย หลังจากนั้นระบบก็จะเข้าสู่ระบบให้ ซึ่งวิธีนี้จะช่วยให้คนที่ไม่มีโทรศัพท์มือถือของเราไม่สามารถเข้าสู่ระบบหรือเข้าสู่บัญชีของเราได้

## Types of Security Controls : Techincal Control
- การยืนยันแบบ 2 ขั้นตอน (2FA) โดยใช้ Google Prompt เป็นเทคนิคที่ใช้ในการยืนยันตัวตนของเราในการเข้าสู่ระบบหรือเข้าสู่บัญชี โดยเป็นการใช้เทคโนโลยีมาใช้งานในการยืนยันตัวตน

## สรุป
- การยืนยันแบบ 2 ขั้นตอนเป็นเรื่องที่ดี ที่เราควรจะตั้งค่า เพราะถ้าหากเรายังใช้การยืนยันตัวตนโดยกรอกแค่ชื่อ Gmail กับ รหัสผ่าน จะทำให้บัญชีของเรามีความปลอดภัยที่น้อยและเสี่ยงต่อการถูก Hack ได้ง่าย
- การยืนยันแบบ 2 ขั้นตอน โดยใช้ Google Prompt
  - มี Control Functions เป็น Preventative 
  - มี Types of Security Controls เป็น Technical Control
