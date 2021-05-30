# Git-Example

### SETUP

- xxx

      git config --global user.name "Pratya Yeekhaday"
      git config --global user.eamil "Pratya@hotmail"

- xxx

      git config user.name
      git config user.eamil

### SETUP INIT

- เริ่มต้น directory ที่มีอยู่เป็นที่เก็บ Git

      git init 
      
- ดึงข้อมูล repository จาก remote host ผ่าน URL

      git clone [URL]
      
- ดึงข้อมูล repository branch dev จาก remote host ผ่าน URL

      git clone -b dev [URL]

### TRACKING PATH CHANGES

- ดูประวัติการ commit ของแต่ล่ะคน

      git log --oneline

### STAGE & SNAPSHOT

- แสดงไฟล์ที่แก้ไขใน directory

      git status

- commit staged ที่มีการเปลี่ยนแปลง 

      git commit -m “[descriptive message]”
      
### REWRITE HISTORY

### TEMPORARY COMMITS

### REference

- https://www.codeleaks.io/how-to-uncommit-changes-in-git/ (uncommit)
- https://education.github.com/git-cheat-sheet-education.pdf

