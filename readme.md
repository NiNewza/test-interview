## Basic HTML, JavaScript, SASS and Gulp Interview

Dear candidate, please follow this readme and solve all questions.

**This test requires:**
- access to the internet
- an HTML, SASS and JS capable IDE (we suggest vscode)
- nodejs 8.0+
- npm or yarn

**Good luck!**

--------

#### 1. Gulp

แก้ไข gulpfile ให้รองรับการทำงานตามด้านล่างนี้

1. สร้าง task สำหรับการ compile ไฟล์ scss เป็น css 

2. สร้าง task สำหรับการ compile ไฟล์ es6 js เป็น browser-compatible js

3. สร้างฟีเจอร์ live reload ข้อ 1 และ 2

4. สร้าง task สำหรับ dev โดยให้ทำการ compile ข้อ 1 และ 2 
อัตโนมัติเมื่อมี code การเปลี่ยนแปลง

5. สร้าง task สำหรับ build ทำการสร้างไฟล์ผลลัพท์ทั้งหมด
โดยให้ผลลัพท์ทั้งหมดอยู่ในโฟลเดอร์ dist

------

##### 2. HTML, JavaScript, SASS

1. แก้ไขไฟล์ index.html ตามข้างล่างนี้
  * ใส่ ชื่อ อายุ อีเมล์ ประวัติส่วนตัว
  * รูปภาพสัตว์ต่างๆ จำนวน 20 รูป

2. แก้ไขไฟล์ css/index.scss ทำให้ชื่อเป็นตัวหนาและมีสีแดง
และทำจัดให้รูปภาพสัตว์ต่างๆ แสดงผล ตามเงื่อนไขข้างล่างนี้
  * มือถือ แถวละ 1 รูป
  * แท็บเล็ต แถวละ 2 รูป
  * คอมพิวเตอร์ แถวละ 3 รูป

3. แก้ไขไฟล์ js/index.js โดยให้สร้างคลาสชื่อว่า ImageLazyLoad จุดประสงค์การทำงานคือ จะบังคับให้ tag img ดาวโหลดรูปภาพเฉพาะที่แสดงผลในจอเท่านั้น รูปภาพที่อยู่นอกจอจะไม่ถูกดาวโหลด

4. ใช้งานคลาสในข้อ 3 กับทุกรุปภาพ

------

##### 3. JS, JQUERY, CSS

![guide](src/img/guide.png)

1. แก้ไขไฟล์ forest.html สร้างสไลด์เต็มจอ ตามรูปภาพข้างบน (ภาพ 2) มีภาพจำนวน 5-10 ภาพ กำหนดให้แต่ละภาพต่อกันตามตัวอย่าง

2. การเปลี่ยนภาพ จะเป็นการเลื่อนจากซ้ายไปขวาหรือจากขวาไปซ้าย โดยให้ใช้คีบอร์ดปุ่มลูกศรซ้ายขวาในการบังคับเลื่อนไปภาพต่อไปด้านซ้าย หรือภาพต่อไปด้านขวา

3. ภาพจะเลื่อนมาหยุดที่ตรงกลางเสมอ ตามตัวอย่างภาพที่ 3 และ 4

4. เมื่อคลิกที่ภาพตรง (ตรงกลางเท่านั้น) ให้แสดงปุ่มขึ้นมาสองปุ่ม คือ
  * SAVE สำหรับดาวโหลดภาพเก็บไว้
  * REMOVE สำหรับลบภาพออกไป

5. เมื่อลบภาพแล้ว ภาพที่เหลือจะถูกจัดเรียงต่อกันและทำงานได้เช่นเดิม

  * **อนุญาติให้ใช้ jQuery core หรือ Standard JS (ECMAScript 5.1+) เท่านั้น ไม่อนุญาติให้ใช้ Plugin ใดๆ เพิ่มเติม**  
  * **สามารถใช้งาน Preprocessor ได้ตามถนัด**