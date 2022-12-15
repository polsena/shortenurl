# เอกสารประกอบการติดตั้งระบบ Short URL 

## ความต้องการของระบบ

- php codeigniter framework
- ฐานข้อมูล mysql

## ขั้นตอนการติดตั้ง
- ดาวน์โหลดไฟล์ .zip 
- ## สามารถดาวน์โหลดได้โดยการกดปุ่ม Code (สีเขียวมุมบนขวา) => Download ZIP
- unzip และนำโฟลเดอร์ไปวางที่ htdocs folder
- สร้างฐานข้อมูลชื่อ redirect
- import sql ชื่อไฟล์ > redirect.sql เข้าไปยังฐานข้อมูล redirect
- พร้อมใช้งานระบบ Short URL :+1:
- ทดสอบโดยการกรอกข้อมูล url ที่ต้องการ จากนั้นให้ระบบสร้าง Short URL ออกมา 
  จากนั้นทดลอง copy url ที่ได้จากระบบไปลองวางใน address ของเบราเซอร์เพื่อดูว่าไปยังลิงค์ปลายทางถูกต้อง 


![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

This is a small url shortner website based on php codeigniter framework.
Download the zip file,unzip it and place it into your htdocs folder.
Create a new database and name it 'redirect'.
Import the sql file into the database you created.
Now you are ready to run the website.


