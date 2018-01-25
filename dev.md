### คำสั่งที่ใช้งาน

> ทำการดึงข้อมูลจาก repository ที่อยู่บนเครื่องของเรา ด้วยคำสั่ง 
* git clone <url ที่ได้>

> คุณสามารถเเพิ่มไฟล์ด้วยคำสั่ง
* git add <ชื่อไฟล์> หรือคำสั่ง git add .
* git commit -m "ข้อความอธิบายการเปลี่ยนแปลง"
* git push

> หากคุณต้องการวางใน brach ที่ต่างกัน
* git push origin <ชื่อ branch>

> คำสั่งสร้าง branch ชื่อว่า "feature_x" และเปลี่ยนไปยัง branch ที่สร้างทันที
* git checkout -b feature_x

> คำสั่งย้ายกลับมายัง master branch
* git checkout master

> คำสั่งลบ branch
* git branch -d feature_x

> คุณสามารถดึงการเปลี่ยนแปลงล่าสุดจาก remote repository มายัง local repository ด้วยคำสั่ง 
* git pull

> ถ้าต้องการ merge การเปลี่ยนแปลงจาก branch อื่น มายัง branch ปัจจุบัน (เช่น master) ด้วยคำสั่ง
* git merge <branch>
* git add <ชื่อไฟล์> หรือคำสั่ง git add .
* git commit -m "ข้อความอธิบายการเปลี่ยนแปลง"
* git push

