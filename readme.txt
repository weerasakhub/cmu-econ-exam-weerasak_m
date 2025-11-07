Database
name : blogs_econ_db

Table
Filed : blogs

Connect Xampp
host : "localhost";
username : "root";
password : " ";
dbname : "blogs_econ_db";

Folder
-blogs //เก็บไฟล์เกี่ยวกับบทความ
	- blogs.php : หน้าแรก, หน้า Dashboard
	- create.php : ฟอร์มสำหรับกรอกบทความ
	-  edit.php : หน้าสำหรับการแก้ไข
	- insert.php : การบันทึกข้อมูล ลงฐานข้อมูล
	- search.php : หน้าสำหรับการค้นหาบทความ
	- view.php : หน้าสำหรับแสดงบทความที่สนใจ
-config  //เก็บไฟล์ Connect กับ Databast
	- การตั้งค่าเชื่อมต่อกับ Database
-database //ไฟล์ ฐานข้อมูล .sql สำหรับ Import Database to Xampp
	- blogs_econ_db.sql ไฟล์ฐานข้อมูล
-uploads //โฟรเดอร์เก็บรูปภาพของ Blogs แต่ละ Blogs 
-readme //รายละเอียดไฟล์ต่างๆในโปรเจค