# Astraea Idol Academy — วิธีขึ้น GitHub Pages

1. สร้าง Repository ใหม่บน GitHub (Public)
2. กด **Add file → Upload files** แล้วลาก "ไฟล์และโฟลเดอร์ทั้งหมดข้างใน" โฟลเดอร์นี้ขึ้นไป
   (ต้องมี `index.html` อยู่ที่หน้าแรกสุดของ repo ไม่ใช่ซ้อนอยู่ในโฟลเดอร์อื่น และต้องมีโฟลเดอร์ `assets`)
   กด Commit changes
3. ไปที่ **Settings → Pages** เลือก Source = *Deploy from a branch*, Branch = `main`, Folder = `/ (root)` แล้วกด Save
4. รอ 1-2 นาที เว็บจะอยู่ที่ `https://ชื่อผู้ใช้.github.io/ชื่อrepo/`

## แก้ไขข้อมูลภายหลัง
- ข้อความทั้งหมดอยู่ใน `index.html` ในก้อน `<script id="astraea-content" type="application/json">`
  เปิดไฟล์ใน GitHub (ไอคอนดินสอ) แล้วแก้ข้อความในเครื่องหมายคำพูดได้เลย (อย่าลบเครื่องหมาย " , { } [ ])
- เปลี่ยนรูป: อัปโหลดรูปใหม่ทับชื่อไฟล์เดิมในโฟลเดอร์ `assets`
