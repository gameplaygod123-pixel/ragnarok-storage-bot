## v71.76 - Launcher Focus Recovery

- แก้ปุ่ม `นอนอ้วน ♡` ค้างที่ `GAME START` ใน Hyper-V หลังเปิดเกมจอแรกแล้ว
- เมื่อ native click พบ `code 12` จะยก Patch Client ขึ้นด้านบนและกู้โฟกัส Launcher ทันที
- ถ้า Windows ยังไม่ยอมเปลี่ยน foreground จะใช้ physical activation click กับปุ่ม `GAME START`
- รองรับ `code 63` หลังคลิกสำเร็จ เพราะ Launcher อาจปิดและส่งโฟกัสไป `Ragexe` ก่อน worker ตรวจจบ
- หลังใช้ fallback จะตรวจหา `Ragexe` ตัวใหม่ภายใน 2 วินาที และกดซ้ำได้หากเกมยังไม่เปิด
- คงโฟวใหม่จาก v71.74: เปิดจอที่ขาดให้ครบตาม ID 1–3 ก่อนเริ่มล็อกอิน
- ไม่เปลี่ยนโฟวล็อกอิน Popup เก็บของ ขายของ หรือไปธนู
- ทดสอบปุ่ม `นอนอ้วน ♡` จากไม่มีเกมบนเครื่องจริง: เปิด `GAME START` ครั้งแรกครบ 3 จอ
- ทดสอบ fallback แยก: Launcher ไม่ถือ foreground แต่สร้าง `Ragexe` ตัวใหม่สำเร็จ
- Build ผ่านด้วย .NET Framework C# compiler

ไฟล์: `RagnarokStorageBot_v71.76_LauncherFocusRecovery.exe`

SHA256: `AABE0AEF8854F0E5D6D8FA26165E6123487C14CE1EDD4DC0F328144283B072CB`
