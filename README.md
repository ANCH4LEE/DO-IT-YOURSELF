# 📍 DO-IT-YOURSELF
# 🔗 เกี่ยวกับโปรเจกต์
โปรเจกต์นี้เป็น เว็บไซต์ E-commerce ในรายวิชาการเขียนโปรแกรมแบบเว็บฝั่งเซิร์ฟเวอร์และรายวิชาการเขียนโปรแกรมแบบเว็บฝั่งไคลเอนต์ วัตถุประสงค์เพื่อให้เข้าใจการพัฒนาเว็บไซต์ของฝั่ง Frontend และ Backend สำหรับฝั่ง Backend เขียนโปรแกรมด้วยภาษา Golang และสำหรับฝั่ง Frontend เขียนโปรแกรมด้วยภาษา JavaScript โดยโปรเจกต์นี้ทางทีมพัฒนาได้ทำเกี่ยวกับเว็บไซต์ E-commerce ร้านสินค้าแฮนด์เมด ที่นำเอาความรู้มาพัฒนาให้เว็บไซต์นี้สำเร็จ

พัฒนาโดยทีมงานทั้งหมด ***5*** คน ซึ่งมีหน้าที่ดังนี้:
 
# 🏡 ทีมพัฒนา
| ชื่อ | บทบาท | รายละเอียด |
|------|------|----------|
| อารดา แว่นวงษ์ | Backend Developer | พัฒนาและออกแบบฝั่ง Backend รวมถึงจัดการฐานข้อมูล |
| สมัญญา กี่สุข | Backend Developer | พัฒนาและออกแบบฝั่ง Frontend |
| สุพิพัฒน์ แสงสอน | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend |
| อัญชลี สกุลฑิฆัมพร | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend รวมถึงออกแบบ UI/UX |
| จารุพร ศิลารัตน์ | Frontend Developer | พัฒนาและออกแบบฝั่ง Frontend |

# 🖥️ เทคโนโลยีที่ใช้
- Frontend: React
- Backend: Rest Api with Golang
- Database: PostgreSQL
- อื่น ๆ: Docker

# 🔌 วิธีติดตั้งและใช้งาน
- ทำการเปิดโฟลเดอร์ storedatabase จาก [store database](storedatabase)
- Run Folder ด้วย Docker ใช้คำสั่ง 
```bash 
docker-compose up -d 
```
- จากนั้นเปิดโฟลเดอร์ ecommercestore จาก [ecommerce](ecommercestore)
```bash 
docker-compose up -d 
```
- เปิด localhost:5050 สำหรับ PostgreSQL
- จะเปิด localhost:8080 สำหรับ Rest API
- ทำการเปิดโฟลเดอร์ Page_DIY จาก [Page_DIY](Page_DIY/diy)
- Run Server
```bash 
npm start
```
- เปิด localhost:3000 สำหรับ React
