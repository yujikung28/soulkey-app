# Soulkey App 🐍

Prototype แรกของระบบ **Soulkey Master Mode**  
เขียนด้วย **Python (Flask)** + Config JSON

---

## ไฟล์หลัก
- `main.py` → โค้ดหลัก (entry point)  
- `config.json` → การตั้งค่าของโปรแกรม (mode, features, languages)  
- `requirements.txt` → library ที่ต้องติดตั้ง (`pip install -r requirements.txt`)  

---

## วิธีใช้งาน (Development)

```bash
# clone project
git clone https://github.com/yujikung28/soulkey-app.git
cd soulkey-app

# ติดตั้ง dependencies
pip install -r requirements.txt

# รันโปรแกรม
python main.py

เปิดเว็บที่ http://localhost:5000

⸻

Status

⚠️ โปรเจกต์นี้เป็น Prototype/Test
ใช้เพื่อทดลอง logic ของ Soulkey Master Mode เท่านั้น
ยังไม่ใช่ Production


