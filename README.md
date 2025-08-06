# 🎨 LiveCraft Resource Pack Submission Guide

ยินดีต้อนรับสู่ระบบ submission โมเดลของ LiveCraft!  
ที่นี่คุณสามารถเสนอ custom model data สำหรับไอเท็มในเซิร์ฟเวอร์ของเราได้อย่างปลอดภัยผ่าน GitHub โดยใช้ branch `model-submissions`

---

## 📦 โครงสร้างไฟล์ที่ต้องใช้

กรุณาสร้างโฟลเดอร์ของคุณใน `model-submissions/` โดยใช้ชื่อที่ไม่ซ้ำกัน เช่น:
    └── model-submissions/assets/minecraft/
                                    <!-- └── items/stick.json | ในกรณีที่ยังไม่มี stick.json -->
                                    └── models/item/xiques/custom-stick.json
                                    └── textures/item/xiques/custom-stick.png

---

> 🔒 อย่าแก้ไขไฟล์นอกโฟลเดอร์ของคุณ
> 🔒 ห้าม push เข้า branch `main` โดยตรง

---

## 🧩 วิธี Submit โมเดล

1. **Fork** repo นี้
2. **Clone** repo และ checkout ไปที่ branch `model-submissions`:
   ```bash
   git checkout model-submissions
3. สร้างโฟลเดอร์ของคุณและเพิ่มไฟล์โมเดล
4. Commit และ Push:
   git add .
   git commit -m "Add stick model by xiques"
   git push origin model-submissions

---

## ✅ Checklist ก่อน Submit
- [ ] ใช้ชื่อโฟลเดอร์ไม่ซ้ำกับ submission อื่น
- [ ] ใช้ CustomModelData ที่ไม่ชนกับของคนอื่น
- [ ] ทดสอบแล้วว่าโมเดลไม่ทำให้ resource pack พัง

---

## 🔔 แจ้งเตือน
ทุกครั้งที่มีการ push เข้า model-submissions จะมีการแจ้งเตือนใน Discord
ทีมงานจะตรวจสอบและ merge เข้าสู่ branch หลัก (main) หากผ่านเกณฑ์

---

## 💬 ติดต่อทีมงานหากคุณมีคำถามหรือปัญหาในการ submit โมเดล
สามารถติดต่อผ่าน Discord: #model-submissions หรือ DM ทีมงานได้เลย

---

ขอบคุณที่ร่วมสร้างโลกของ LiveCraft ให้สวยงามและมีชีวิต! 🌍