## v72.50

- เพิ่มภาพ `uuuxx.png` สำหรับตรวจ popup `TokenAgency ล้มเหลว` บนหน้า Login
- RUN ALL ตรวจพบ popup นี้และส่งจอเข้าสู่โฟลว์ Login เดิม
- ตรวจทั้งก่อนกรอก Login, ระหว่างรอหน้า Login และหลังส่ง Login/กด Enter
- เมื่อพบจะใช้ปุ่มยืนยันที่ตรวจจากภาพเดิม; หากไม่พบปุ่มจะใช้ Enter แล้วจับภาพตรวจผลรอบต่อไป
- หลังปิด popup แล้วจะวน Login ต่อโดยอัตโนมัติ
- ใช้ `CaptureClient` และ exact HWND ตามระบบเดิม ไม่เพิ่มพิกัดตายตัวใหม่
- Build ผ่านและตรวจพบ `RagnarokNativeBot.Templates.uuuxx.png` ใน EXE
- ยังไม่ได้ทดสอบกับ popup จริง

SHA256: `7FDF01958BAC4557CAFC7DB1ECAA75E4FA41ABCFE241331E0323571576D463E8`
