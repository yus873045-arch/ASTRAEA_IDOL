# Astraea Idol Academy — วิธีขึ้น GitHub Pages

1. แตกไฟล์ zip นี้ในเครื่องก่อน (อย่าอัปโหลดทั้ง zip)
2. สร้าง Repository ใหม่บน GitHub (Public) แล้วกด Add file → Upload files
3. ลาก "ไฟล์และโฟลเดอร์ทั้งหมดข้างใน" ขึ้นไป ต้องมี `index.html` อยู่ชั้นแรกสุดของ repo พร้อมโฟลเดอร์ `assets` แล้วกด Commit changes
4. Settings → Pages → Deploy from a branch → main → / (root) → Save
5. รอ 1-2 นาที เว็บจะอยู่ที่ https://ชื่อผู้ใช้.github.io/ชื่อrepo/

## แก้ไขข้อมูลภายหลัง
- ข้อความทั้งหมดอยู่ใน `index.html` ในก้อน `<script id="astraea-content" type="application/json">` (อย่าลบเครื่องหมาย " , { } [ ])
- เปลี่ยนรูป: อัปโหลดรูปใหม่ทับชื่อไฟล์เดิมในโฟลเดอร์ `assets`
