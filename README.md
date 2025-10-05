# LineBot

## Line Official Account
  - Create New
  - กรอกข้อมูลให้ครบ
  - Setting
      - Messaging API
      - Set Webhook
      - Go Line Developers Console
      - เลือกหรือเพิ่ม Admin
          - Messaging API
          - Channel access token
       
## สร้าง Drive ที่เก็บข้อมูล
  - สร้างโฟลเดอร์
  - คลิกขวา  รับลิงก์ ตั้งค่าเป็น ทุกคนที่มีลิงก์
  - คัดลอก Folder ID จาก URL
`
https://drive.google.com/drive/folders/xxxxxxxxxxxxx
`

## Google Apps Script
  - คลิกสร้างโปรเจกต์ใหม่
  - วางโค้ดที่ `Script`
  - Deploy เป็น Web App
  - ตั้งค่า Who has access: `Anyone`
  - กด Deploy จะได้ URL ของ Web App
`
https://script.google.com/macros/s/xxxxxx/exec
`
  - ไปที่ LINE Developers
  - ในช่อง Webhook URL ใส่ URL ของ Web App
  - กด `Verify` เพื่อทดสอบ
