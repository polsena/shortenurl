# เอกสารประกอบการติดตั้งระบบ Short URL 

## ความต้องการของระบบ

- php codeigniter framework
- ฐานข้อมูล mysql

## ขั้นตอนการติดตั้ง
- ดาวน์โหลดไฟล์ .zip 
- #### สามารถดาวน์โหลดได้โดยการกดปุ่ม Code (สีเขียวมุมบนขวา) => Download ZIP
- unzip และนำโฟลเดอร์ไปวางที่ htdocs folder
- สร้างฐานข้อมูลชื่อ redirect
- import sql ชื่อไฟล์ > redirect.sql เข้าไปยังฐานข้อมูล redirect
- พร้อมใช้งานระบบ Short URL :+1:
- ทดสอบโดยการกรอกข้อมูล url ที่ต้องการ คลิกเพื่อให้ระบบสร้าง Short URL ออกมา 
  จากนั้นทดลอง copy url ที่ได้จากระบบไปลองวางใน address ของเบราเซอร์เพื่อตรวจสอบความถูกต้องของลิงค์ปลายทาง

## ตัวอย่างหน้าตาการใช้งาน

![This is an image](https://caffeinelism.com/upload/screenshot/Screenshot%202022-12-16%20005925.jpg)

![This is an image](https://caffeinelism.com/upload/screenshot/03.jpg)

## ระบบจะเก็บช้อมูลของ url ต้นทางและ short url ลงในฐานข้อมูล

![This is an image](https://caffeinelism.com/upload/screenshot/04.jpg)
