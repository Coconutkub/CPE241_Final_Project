
อธิบายเร็ว 1 บรรทัด "meta data"
ทำหน้าที่คล้าย "พจนานุกรม" ของโปรเจกต์ โดยบอกว่าโปรเจกต์นี้ชื่ออะไร ใช้เวอร์ชันอะไร รันยังไง และต้องใช้ dependencies อะไรบ้าง

มีไว้เพื่ออะไร?
- จัดการ ข้อมูลโปรเจกต์ (เช่นชื่อ, เวอร์ชัน)
- ใช้ ติดตั้ง dependencies (เมื่อเพิ่มพวก express, axios, ฯลฯ มันจะมาอยู่ใน dependencies)
- สั่งรันสคริปต์ต่าง ๆ ผ่าน npm run เช่น npm run test
- จำเป็นสำหรับการ deploy หรือแชร์โปรเจกต์กับคนอื่น

{
  "name": "server",                // ชื่อโปรเจกต์
  "version": "1.0.0",              // เวอร์ชันของโปรเจกต์
  "description": "",              // คำอธิบายโปรเจกต์ (ยังไม่ได้ใส่)
  "main": "index.js",             // จุดเริ่มต้นของโปรแกรม (ไฟล์หลัก)
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1" 
    // คำสั่งที่จะรันเมื่อพิมพ์ `npm test` (ตอนนี้ยังไม่มี test จริง)
  },
  "keywords": [],                 // คีย์เวิร์ดสำหรับค้นหาโปรเจกต์นี้ (ยังไม่ได้ใส่)
  "author": "",                   // ชื่อผู้เขียนโปรเจกต์ (ยังไม่ได้ใส่)
  "license": "ISC"                // ใบอนุญาต (license) ที่ใช้
}