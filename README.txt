ห้องปรุงยาแพทย์ (Gemini) — วิธีขึ้นเว็บ

1) สร้าง API key: https://aistudio.google.com/apikey
2) GitHub: สร้าง repository ใหม่ (Public) > Add file > Upload files > ลากทุกไฟล์ในโฟลเดอร์นี้ (index.html, manifest.webmanifest, icon-*.png) > Commit
3) Settings > Pages > Source: Deploy from a branch > main / (root) > Save  รอ 1-2 นาที จะได้ https://<ชื่อผู้ใช้>.github.io/<ชื่อ repo>/
4) ล็อก key ใน Google Cloud Console > APIs & Services > Credentials > เลือก key:
   - Application restrictions: Websites > https://<ชื่อผู้ใช้>.github.io/*
   - API restrictions: Generative Language API
5) เปิดเว็บ > ปุ่ม Gemini มุมขวาล่าง > ใส่ key > โหลดรายชื่อรุ่น > ทดสอบ > บันทึก
6) iPad: Safari > แชร์ > เพิ่มไปยังหน้าจอโฮม แล้วเปิดจากไอคอนนั้นเสมอ
7) ย้ายงานจากเว็บใน Claude: ชั้นยา > สำรองทั้งชั้น (ในเว็บ Claude) แล้วกู้คืนไฟล์นั้นในเว็บนี้
อัปเดตเว็บ: อัปโหลด index.html ใหม่ทับใน repo เดิม ข้อมูลในเครื่องไม่หาย
