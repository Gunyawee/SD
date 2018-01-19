#I've learned

Git checkout test.txt
Git reset HEAD test.txt 
Git pull 
Git reset —soft “head^”
Gir rm Test.txt ลบไฟล์หลัง commit 

เรียกไฟล์กลับ ในกรณีที่ commit ไปแล้ว  ถ้ายังไม่ commit ก็ checkout อย่างเดียว
Gor reset HEAD test.txt
Git checkout test.txt 

ถ้าทำในคอมแล้วจะให้ขึ้นบนเว็บเหมือนกันในเว็บ
Git add .
Git commit -m “update”
Git push 


ลบในเว็บ แล้วมาทำ 
Git fetch 
Git merge

การซ่อนข้อมูล
Git stash ซ่อน
Git stash pop แสดงที่ซ่อนกลับมา
 และก็อัฟหน้าเว็บตามปกติ

แสดงบรานซ์
Git brach -a

สร้างบรานซ์
Git brach dev

ย้าย * ไปที่ dev (switch branch)
Git checkout dev 

สร้างและย้ายไปเลย
Git checkout -b new

ลบบรานซ์ dev 
Git brach -d dev

Create new.md

Get push -u origin new**

ถ้าตะอัปเดทจาก new บรานมาใส่ใน master
Git checkout master
Git merge dev เอารวมกัน 2 บรานซ์
Git add . Commit push master 
Git checkout new แก้ในไฟล์
Git add. 
Git commit -m “”
Git push origin  new

Git checkout master
Git merge —no-f แก้ไฟล์ที่รวมยุแล้ว
 ก็ add commit push 


สร้างบรานซ์ 2 บรานซ์. ( dev , feature)
Dev : dev.md  ใส่ความรู้ที่ได้ไป
feature : feature.md  เอาข้อมูลของโปรเจค

Switch  to branch master
Git merge —no-f new #merge from new to master
