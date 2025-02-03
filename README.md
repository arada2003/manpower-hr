# 📌 Manpower

## 🔍 เกี่ยวกับโปรเจกต์
โปรเจกต์นี้เป็น ระบบวางแผนกำลังคน ของรายวิชาการบริหารจัดการระบบฐานข้อมูลและวิชาระบบสารสนเทศเพื่อธุรกิจ มีวัตถุประสงค์เพื่อให้สร้างระบบวางแผนกำลังคนจากระบบ Human Resource(HR)

พัฒนาโดยทีมงานทั้งหมด **5 คน** ซึ่งมีหน้าที่ดังนี้:

## 👥 ทีมพัฒนา  
| ชื่อ | บทบาท | รายละเอียด |
|------|------|----------|
| **อารดา แว่นวงษ์** | Backend Developer | พัฒนาและออกแบบฝั่ง Backend รวมถึงจัดการฐานข้อมูล |
| **สมัญญา กี่สุข** | Backend Developer | พัฒนาและออกแบบฝั่ง Backend |
| **สุพิพัฒน์ แสงสอน** | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend |
| **อัญชลี สกุลฑิฆัมพร** | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend รวมถึงออกแบบ UI/UX |
| **อภิญญา แซ่อึ้ง** | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend |

## 🛠 เทคโนโลยีที่ใช้  
- **Frontend:** React  
- **Backend:** FastAPI
- **Database:** MySQL  
- **อื่น ๆ:** Docker

## 🚀 วิธีติดตั้งและใช้งาน
- ทำการ Get manpower_database ก่อน จาก [Database Manpower](https://github.com/arada2003/manpower_database)
- Run Folder ด้วย Docker ใช้คำสั่ง
```bash
docker-compose build
```
- จากนั้นทำการ Get manpower_frontend จาก [Manpower React](https://github.com/arada2003/manpower_frontend)
```bash
# ติดตั้ง dependencies
npm install

# รันเซิร์ฟเวอร์
npm run serve
```
- จะเปิด localhost:8001 สำหรับ fastApi
- จะเปิด localhost:8080 สำหรับ react
