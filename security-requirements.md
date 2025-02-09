# 5.1.3 Input Validation

## Details
Verify that all input (HTML form fields, REST requests, URL parameters, HTTP
headers, cookies, batch files, RSS feeds, etc) is validated using positive
validation (allow lists). 



 ## Meaning by ChatGPT
 ตรวจสอบให้แน่ใจว่าทุกการป้อนข้อมูล (ฟอร์ม HTML, คำขอ REST, พารามิเตอร์ URL, หัวข้อ HTTP, คุกกี้, ไฟล์ชุดคำสั่ง, ฟีด RSS, ฯลฯ) ได้รับการตรวจสอบโดยใช้การตรวจสอบเชิงบวก (allow lists) 



## Meaning by Gemini
การตรวจสอบว่าข้อมูลป้อนเข้าทั้งหมด (ช่องแบบฟอร์ม HTML, คำขอ REST, พารามิเตอร์ URL, ส่วนหัว HTTP, คุกกี้, ไฟล์แบทช์, ฟีด RSS ฯลฯ) ได้รับการตรวจสอบโดยใช้การตรวจสอบเชิงบวก (รายการที่อนุญาต)


## My Summary
ตรวจสอบข้อมูลทั้งหมดที่ถูกอินพุต (เช่น จากฟอร์ม HTML, การร้องขอ API, พารามิเตอร์ URL, คุกกี้, คำขอหรือไฟล์ต่างๆ) ได้รับการอนุญาตการตรวจสอบอย่างถูกต้องและปลอดภัย (โดยใช้รายการที่อนุญาตหรือ "allow list")


## Example
คุกกี้ (Cookies) ตรวจสอบ Session ID กับฐานข้อมูล:
 - เมื่อผู้ใช้งานล็อกอินสำเร็จ เซิร์ฟเวอร์จะสร้าง Session ID ให้และบันทึกในฐานข้อมูล เมื่อผู้ใช้ส่งคำขอ (request) Session ID จากคุกกี้จะถูกส่งมาด้วย ระบบต้อง ตรวจสอบว่า Session ID นั้นถูกต้องหรือไม่ ตรวจสอบค่า Session ID กับรายการที่อนุญาต เป็นการตรวจสอบว่า Session ID ถูกต้องก่อนให้สิทธิ์เข้าถึง 
 
## Members

[6530250093 ธนพัฒน์ อุไรวงษ์](https://friday1313.github.io/security-requirement)

[6530200835 สรสิช ปัญญางค์](https://bossmahob.github.io/security-requirements)
