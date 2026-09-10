## v71.75 - Noon Uan Duplicate-account Recovery

- เพิ่มการตรวจ `disconnect_account_overlap.png` ในโฟว `นอนอ้วน ♡` หลังพบ `bcc_11`
- รองรับ Popup “มีผู้ใช้อื่นเข้าสู่ระบบบัญชีนี้แล้ว” ที่ปรากฏบนจอในเกม
- ใช้ระบบปิด Popup แบบตรวจภาพซ้ำเดิม: คลิกปุ่มยืนยันและใช้ Spacebar สำรอง
- เมื่อ Popup ปิดเกมหรือย้อนกลับหน้า Login จะเปิด/ล็อกอินใหม่ด้วย ID ที่ตั้งไว้ประจำช่องนั้น
- บังคับ `KeepLoginIdForRetry=false` เพื่อวาง ID ประจำช่องใหม่ ไม่เก็บ ID เก่าที่ทำให้ซ้อน
- คงระบบจำช่องและเปิดจอที่ขาดก่อนจาก v71.74
- Build ผ่านด้วย .NET Framework C# compiler

ไฟล์: `RagnarokStorageBot_v71.75_NoonUanOverlap.exe`

SHA256: `EFD460DD0B063873DD4A27F9D091B2208FE31DBE7CD18F9DE8839E3B7CC16A91`
