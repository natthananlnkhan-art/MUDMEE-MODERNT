MUDMEE MODERN — GitHub Pages Upload Guide (ภาษาไทย)

ใน ZIP นี้มี index.html อยู่ที่ระดับแรก และฝังรูปภาพไว้ในไฟล์ HTML แล้ว

วิธีอัปโหลด
1) แตกไฟล์ ZIP ในมือถือ/คอมพิวเตอร์ก่อน
2) เปิด GitHub แล้วเข้า Repository ที่ต้องการใช้
3) กด Add file > Upload files
4) อัปโหลด index.html และ .nojekyll จากโฟลเดอร์ที่แตกไฟล์ (ห้ามอัปโหลด ZIP ทั้งก้อน)
5) ถ้ามี index.html อยู่แล้ว ให้แทนที่ไฟล์เดิม แล้วกด Commit changes
6) ไปที่ Settings > Pages
7) ใน Build and deployment เลือก Deploy from a branch
8) เลือก Branch: main และ Folder: /(root) แล้วกด Save
9) รอ 1–5 นาที แล้วกลับไป Settings > Pages เพื่อกดลิงก์ Visit site ที่ GitHub แสดงให้

สำคัญ: 404 มักเกิดจาก Pages ยังไม่เปิด/ยังไม่ deploy หรือเปิด URL ผิด ไม่ได้แปลว่าภาพในเว็บเสียเสมอไป
- ถ้า Repository ชื่อ username.github.io: URL จะเป็น https://USERNAME.github.io/
- ถ้าเป็น Repository ชื่ออื่น เช่น mudmee-modern: URL จะเป็น https://USERNAME.github.io/mudmee-modern/
ใช้ URL ที่หน้า Settings > Pages แสดงให้เป็นหลัก
