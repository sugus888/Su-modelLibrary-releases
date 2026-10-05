# SU Model Library — Releases

ไฟล์ release ที่เซ็นแล้วของปลั๊กอิน **SU Model Library** สำหรับ SketchUp 2024+
ปลั๊กอินใช้ repo นี้เป็นแหล่ง **อัปเดตอัตโนมัติ** ส่วน source code อยู่ใน repo private แยกต่างหาก

## ติดตั้งบนเครื่องใหม่

1. ดาวน์โหลด [**su_model_library-installer.zip**](https://github.com/sugus888/Su-modelLibrary-releases/raw/main/su_model_library-installer.zip) (เวอร์ชันล่าสุดเสมอ)
2. แตกไฟล์ แล้ว**ปิด SketchUp**
3. Windows: ดับเบิลคลิก `install.cmd` · macOS: ดับเบิลคลิก `install.command`

หลังจากนั้นปลั๊กอินจะอัปเดตตัวเองจาก repo นี้

## ไฟล์ใน repo

| ไฟล์ | หน้าที่ |
|---|---|
| `latest.json` | ข้อมูลเวอร์ชันล่าสุด + ลายเซ็นดิจิทัล (ปลั๊กอินอ่านไฟล์นี้) |
| `su_model_library-<version>.rbz` | แพ็กเกจปลั๊กอิน |
| `su_model_library-installer.zip` | ตัวติดตั้งแบบดับเบิลคลิก (เวอร์ชันล่าสุด) |

ปลั๊กอินติดตั้งเฉพาะแพ็กเกจที่ลายเซ็นใน `latest.json` ตรงกับกุญแจที่ฝังอยู่ในปลั๊กอิน และขนาดไฟล์กับ SHA-256 ตรงกันเท่านั้น
ไฟล์ใน repo นี้สร้างและเซ็นโดยระบบ release อัตโนมัติ **ห้ามแก้ไขด้วยมือ**
