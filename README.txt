# ทะเบียนวิสัญญี PWA

ไฟล์ชุดนี้พร้อมอัปขึ้น GitHub Pages ได้ทันที

## ไฟล์หลัก
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png

## วิธีใช้งานย่อ
1. อัปโหลดทุกไฟล์ขึ้น GitHub repo
2. ไปที่ Settings > Pages
3. เลือก Deploy from a branch
4. เลือก main และ /(root)
5. เปิดลิงก์ที่ได้ใน Safari/Chrome
6. Add to Home Screen / Install app

## หมายเหตุ
ถ้า iframe ไม่แสดง ให้เพิ่มใน Apps Script:

```javascript
return HtmlService.createHtmlOutputFromFile('Index')
  .setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL);
```
