# pikun-quiz-packs

แพ็กข้อสอบสำหรับแอพ PikunQuiz (เข้ารหัส AES-256-GCM — ถอดได้เฉพาะในแอพ)

- `index.json` — รายการแพ็ก แอพอ่านไฟล์นี้ก่อนเพื่อแสดงให้เลือก
- `packs/<packId>-v<version>.pack` — ไฟล์แพ็กเข้ารหัส

เพิ่มแพ็กใหม่: เข้ารหัสด้วย `tools/pack.py` ในโปรเจกต์แอพ แล้วเพิ่มรายการใน `index.json` (packId, version, file, bytes, sha256)
อัปเดตแพ็ก: เพิ่ม `version` แล้วใส่ไฟล์ใหม่ แอพจะแทนที่ชุดเดิมทั้งชุด
