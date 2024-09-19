# cs211-661-project-am-ft-ch-mo ( EventFlow )

## รายชื่อสมาชิก
- 6510405300 กฤษฎิ์พิรัชย์ ชัยวงศ์ ( Github Username : kritpi )
    * 16.A ระบบลงทะเบียนสำหรับผู้ใช้ทั่วไป
    * 17.B หน้าแสดงประวัติรายการอีเวนต์ที่ตนเองเข้าร่วม
    * 18.B หน้าแสดงรายการอีเวนต์ที่ตนเองเป็นผู้จัดอีเวนต์ ซึ่งสามารถแสดงหน้าจัดการอีเวนต์ได้
    * 19.A ต้องเป็น ”ผู้จัดอีเวนต์” นี้เท่านั้นจึงจะจัดการอีเวนต์นี้ได้
    * 19.B มีหน้าแก้ไขข้อมูลอีเวนต์
    * 19.C มีส่วนจัดการ “การเปิดรับผู้เข้าร่วมอีเวนต์”
    * 19.E มีส่วนจัดการ “การเปิดรับทีมผู้ร่วมจัดอีเวนต์”
    * 20.A มีหน้าแสดงรายชื่อผู้เข้าร่วมอีเวนต์ ผู้จัดอีเวนต์สามารถระงับสิทธิ์ผู้เข้าร่วมอีเวนต์ได้
    * 22.A ผู้เข้าทีม เห็นชื่อทีม และตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม และสามารถแสดงความคิดเห็นภายในกิจกรรม

- 6510405512  ณัฐภัทร อิ่นคำ ( Github Username : nattapatink )
    * 15.A โปรแกรมต้องไม่มีระบบการสร้างบัญชีสำหรับผู้ดูแลระบบ
    * 16.B ผู้ใช้ระบบสามารถเปลี่ยนรหัสผ่านของตนเองได้
    * 16.C ผู้ใช้ระบบสามารถเปลี่ยนรูปภาพเพื่อใช้เป็นภาพของผู้ใช้ระบบ
    * 17.C ค้นหาอีเวนต์บางส่วนด้วยชื่ออีเวนต์
    * 17.D แสดงรายละเอียดของอีเวนต์ที่ผู้ใช้งานเลือก
    * 21.A มีหน้าแสดงทีมผู้ร่วมจัดอีเวนต์ และแสดงรายชื่อผู้ร่วมทีมในทีมนั้น ผู้จัดอีเวนต์สามารถระงับสิทธิ์ผู้ร่วมทีมได้
    * 21.B มีหน้าแสดง และหน้าจัดการ ตารางกิจกรรมของอีเวนต์สำหรับผู้ร่วมทีม
    * 21.C ผู้จัดอีเวนต์กำหนดได้ว่า กิจกรรมใดเสร็จสิ้นไปแล้ว

- 6510450356 ณัฐริกา กัมพลานุวงศ์ ( Github Username : Nattarika6510450356 )
    * 10.A ตรวจสอบความถูกต้องของข้อความที่ปรากฏในส่วนต่างๆ
    * 10.B Graphic User Interface
    * 10.C ขนาดหน้าจอของโปรแกรมต้องมีความสูงไม่เกิน 1024 pixel มีความกว้างของหน้าจอโปรแกรมเหมาะสําหรับผู้ใช้โน้ตบุ๊กทั่วไป
    * 11.A ข้อมูลนิสิตผู้จัดทําโปรแกรม
    * 11.B ข้อมูลคําสั่งหรือคําแนะนําในการใช้โปรแกรมที่นิสิตสร้างขึ้นมา
    * 15.C หน้าแสดงรายชื่อของผู้ใช้ระบบ
    * 18.A ส่วนให้ผู้ใช้ทั่วไปสร้างอีเวนต์

- 6510450526 นลินี ศรีหา ( Github Username : xoxochxm )
    * 10.A ตรวจสอบความถูกต้องของข้อความที่ปรากฏในส่วนต่างๆ
    * 10.B Graphic User Interface
    * 10.C ขนาดหน้าจอของโปรแกรมต้องมีความสูงไม่เกิน 1024 pixel มีความกว้างของหน้าจอโปรแกรมเหมาะสําหรับผู้ใช้โน้ตบุ๊กทั่วไป
    * 11.A ข้อมูลนิสิตผู้จัดทําโปรแกรม
    * 15.B ผู้ดูแลระบบสามารถเปลี่ยนรหัสผ่านของตนเองได้
    * 20.C มีหน้าแสดง และหน้าจัดการ (เพิ่มและลบ) “ตารางกิจกรรมของอีเวนต์สำหรับผู้เข้าร่วมอีเวนต์”
    * 17.A หน้าแสดงรายการอีเวนต์ที่อยู่ระหว่างการจัดงานทั้งหมด

## วิธีการติดตั้งหรือรันโปรแกรม

# วิธีการติดตั้งและรันโปรแกรมบนระบบปฏิบัติการ macOs ผ่าน command line
```
git clone https://github.com/CS211-661/cs211-661-project-am-ft-ch-mo.git

cd cs211-661-project-am-ft-ch-mo

cd documents

java -jar cs211-661-project-am-ft-ch-mo-1.0-shaded.jar 
```

# วิธีการติดตั้งและรันโปรแกรมบนระบบปฏิบัติการ Windows ผ่าน command line
```
git clone https://github.com/CS211-661/cs211-661-project-am-ft-ch-mo.git

cd cs211-661-project-am-ft-ch-mo

cd documents

java -jar cs211-661-project-am-ft-ch-mo-1.0-shaded-window.jar
```
# วิธีการติดตั้งและรันโปรแกรมด้วยวิธีการดับเบิ้ลคลิกที่ executable file
```
git clone https://github.com/CS211-661/cs211-661-project-am-ft-ch-mo.git
```
- เข้าไปที่โฟลเดอร์ "cs211-661-project-am-ft-ch-mo" จากนั้นทำการคัดลอกโฟลเดอร์ "documents" นำออกมาวางข้างนอกโฟลเดอร์ของโปรแกรม
- ดับเบิ้ลคลิกที่ไฟล์ "cs211-661-project-am-ft-ch-mo-1.0-shaded-window.jar" สำหรับระบบปฏิบัติการ Windows
- ดับเบิ้ลคลิกที่ไฟล์ "cs211-661-project-am-ft-ch-mo-1.0-shaded.jar" สำหรับระบบปฏิบัติการ macOs

## การวางโครงสร้างไฟล์

```
    ┣ 📂data  --> เป็นโฟลเดอร์สำหรับไฟล์ csv เก็บข้อมูลต่างๆที่จำเป็นของโปรแกรม
    ┃ ┣ 📜comment-list.csv
    ┃ ┣ 📜event-user-list.csv
    ┃ ┣ 📜events-list.csv
    ┃ ┣ 📜schedule-list.csv
    ┃ ┣ 📜team-list.csv
    ┃ ┣ 📜team-user-list.csv
    ┃ ┗ 📜user-list.csv
    ┣ 📂document --> เป็นโฟลเดอร์สำหรับเก็บ Jar file, โฟลเดอร์ data, UML Diagram และไฟล์ pdf ที่ระบุข้อมูลและวิธีใช้โปรแกรม
    ┣ 📂images  --> เป็นโฟลเดอร์ที่เก็บรูปภาพที่ถูกนำเข้ามาในโปรแกรม
    ┃ ┣ 📂event  --> เป็นโฟลเดอร์ที่เก็บรูปภาพของ Events เมื่อถูกสร้างหรือถูกแก้ไข
    ┃ ┗ 📂user --> เป็นโฟลเดอร์สำหรับเก็บรูปโปรไฟล์ของผู้ใข้แต่ละคน
    ┣ 📂src
    ┃ ┗ 📂main
    ┃ ┃ ┣ 📂java
    ┃ ┃ ┃ ┣ 📂cs211
    ┃ ┃ ┃ ┃ ┗ 📂project
    ┃ ┃ ┃ ┃ ┃ ┣ 📂controllers   --> เป็นโฟลเดอร์ที่จะเก็บไฟล์ Controllers ซึ่งไฟล์ Controller มีหน้าที่เป็นตัวกลางที่จะเชื่อมต่อระหว่าง Model และ View โดนที่ Controller ทำหน้าที่จัดการ Logic ทั้งหมดของระบบ
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AdminChangePasswordController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AdminViewUserListController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CreateEventController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CreateEventScheduleController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CreateTeamController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜CreateTeamScheduleController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜DataContainer.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EditEventController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EditEventScheduleController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EditProfileController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EditTeamController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventManageUserController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventSchedule2Controller.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventScheduleController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜InstructionController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜JoinedEventController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜LoginPageController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜OngoingEventsController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜OrganizerController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜RegistrationPageController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamSchedule2Controller.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamScheduleController.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UserProfileController.java
    ┃ ┃ ┃ ┃ ┃ ┣ 📂cs211661project
    ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜HelloApplication.java
    ┃ ┃ ┃ ┃ ┃ ┣ 📂models  --> เป็นโฟลเดอร์ที่จะเก็บไฟล์ Model ซึ่งไฟล์ Model มีหน้าที่จัดการข้อมูลต่างๆของโปรแกรม
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂collection
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventUserList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventsList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamCommentList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamUserList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TimeScheduleList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UserList.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventUser.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Events.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Team.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamComment.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamUser.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TimeSchedule.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜User.java
    ┃ ┃ ┃ ┃ ┃ ┗ 📂services  --> เป็นโฟลเดอร์ที่จะเก็บไฟล์ Services ซึ่งไฟล์ Service จะเป็นไฟล์ที่จะลดความซ้ำซ้อนของการอ่าน/เขียนไฟล์ของ Model นั้นๆ
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜AdminViewUserListComparator.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜Datasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventUserFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜EventsListFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜FXRouter.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamCommentListFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamListFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TeamUserListFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜TimeScheduleListFileDatasource.java
    ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜UserListFileDatasource.java
    ┃ ┃ ┃ ┗ 📜module-info.java
    ┃ ┃ ┗ 📂resources
    ┃ ┃ ┃ ┣ 📂cs211
    ┃ ┃ ┃ ┃ ┗ 📂project
    ┃ ┃ ┃ ┃ ┃ ┗ 📂views   --> เป็นโฟลเดอร์ที่จะเก็บไฟล์ View ซึ่งไฟล์ View มีหน้าที่จัดการในส่วนของหน้าตาทั้งหมด
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜admin-change-password-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜admin-view-user-list-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜create-event-schedule-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜create-event.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜create-team-schedule-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜create-team-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜edit-event-schedule-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜edit-event-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜edit-profile-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜edit-team-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜event-manage-user-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜event-schedule-2-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜event-schedule-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜event-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜instruction-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜joined-event-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜login-page-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜ongoing-events-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜organizer-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜registration-page-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜team-schedule-2-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜team-schedule-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📜team-view.fxml
    ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📜userprofile-view.fxml
    ┃ ┃ ┃ ┗ 📂images  --> เป็นโฟลเดอร์สำหรับเก็บรูปภาพที่ถูกใช้ในโปรแกรม
    ┃ ┃ ┃ ┃ ┣ 📂events
    ┃ ┃ ┃ ┃ ┃ ┗ 📜samplePic.png
    ┃ ┃ ┃ ┃ ┣ 📜banned.png
    ┃ ┃ ┃ ┃ ┣ 📜default.png
    ┃ ┃ ┃ ┃ ┣ 📜falcontech.png
    ┃ ┃ ┃ ┃ ┣ 📜lock.png
    ┃ ┃ ┃ ┃ ┗ 📜star.jpg
 
```

## ตัวอย่างข้อมูลผู้ใช้ระบบ
    - Admin
    - User --> ผู้จัดอีเวนท์
    - User --> ผู้เข้าร่วมอีเวนท์
    - User --> ผู้เข้าร่วมทีม

## สรุปสิ่งที่พัฒนาในแต่ละครั้งที่ส่งความก้าวหน้าของระบบ
- ครั้งที่ 1 ( 11 สิงหาคม 2566 )
    * ออกแบบและวางแผนการพัฒนาองค์ประกอบของโปรแกรม
    * สร้างไฟล์ fxml สำหรับ controller หน้าหลักของโปรแกรม ( สมาชิกทุกคน )

- ครั้งที่ 2 ( 1 กันยายน 2566 )
    * หน้าสำหรับ Admin ดูเวลาเข้าใช้งานของ User ( นลินี ) 
    * หน้าสำหรับดูรายละเอียดต่างๆของ Event ( ณัฐภัทร, ณัฐริกา ) 
    * หน้าสำหรับสร้าง Event ( ณัฐริกา, กฤษฎิ์พิรัชย์ ) 
    * หน้าสำหรับ Register ( กฤษฎิ์พิรัชย์ ) 
    * หน้าสำหรับ Login ( ณัฐภัทร, ณัฐริกา ) 
    * หน้าสำหรับดูลิสต์ของ Events ทั้งหมด ( สมาชิกทุกคน ) 
    * หน้าสำหรับดูโปรไฟล์ของ User ( กฤษฎิ์พิรัชย์, ณัฐภัทร ) 
    * สร้าง Models และ Collection ของ User ( ณัฐภัทร )
    * สร้าง Models และ Collection ของ Event ( กฤษฎิ์พิรัชย์ )
    * สร้าง Models และ Collection ของ User ที่เข้าร่วม Event ( ณัฐภัทร )
    * สร้าง Datasource ของ User ( ณัฐภัทร )
    * สร้าง Datasource ของ Event ( ณัฐริกา )
    * สร้าง Datasource ของ User ที่เข้าร่วม Event ( ณัฐภัทร )

- ครั้งที่ 3 ( 22 กันยายน 2566 )
    * หน้าเปลี่ยนรหัสผ่านของ Admin ( นลินี ) 
    * หน้าแก้ไขข้อมูลของ User ( ณัฐภัทร ) 
    * หน้าสำหรับสร้าง Team ( กฤษฎิ์พิรัชย์ ) 
    * หน้าสำหรับเพิ่มกิจกรรมของ Team ( ณัฐภัทร, ณัฐริกา ) 
    * หน้าสำหรับเพิ่มกิจกรรมของ Event ( กฤษฎิ์พิรัชย์ ) 
    * หน้าสำหรับแก้ไขข้อมูลของ Event ( กฤษฎิ์พิรัชย์, ณัฐภัทร ) 
    * หน้าแก้ไขข้อมูลกิจกรรมของ Event  ( กฤษฎิ์พิรัชย์, ณัฐภัทร, นลินี) 
    * Data Container สำหรับการส่งข้อมูลหลายๆอย่างข้าม Controller ( กฤษฎิ์พิรัชย์, ณัฐภัทร )
    * หน้าสำหรับจัดการ User ที่เข้าร่วม Event ( กฤษฎิ์พิรัชย์ ) 
    * หน้าตารางกิจกรรมสำหรับ User ที่เข้าร่วม Event ( ณัฐภัทร ) 
    * หน้าสำหรับแสดงประวัติ Team และ Event ที่ User เข้าร่วม ( กฤษฎิ์พิรัชย์, นลินี ) 
    * หน้าสำหรับดูรายละเอียดของ Team ก่อนที่จะเข้าร่วม ( ณัฐภัทร, ณัฐริกา ) 
    * สร้าง Models และ Collection ของ Team ( กฤษฎิ์พิรัชย์ )
    * สร้าง Models และ Collection ของ User ที่เข้าร่วม Team ( กฤษฎิ์พิรัชย์ )
    * สร้าง Models และ Collection ของกิจกรรมใน Event ( ณัฐริกา )
    * สร้าง Datasource ของ Team ( กฤษฎิ์พิรัชย์ )
    * สร้าง Datasource ของ User ที่เข้าร่วม Team ( กฤษฎิ์พิรัชย์ )
    * สร้าง Datasource ของกิจกรรมใน Event ( กฤษฎิ์พิรัชย์ )

- ครั้งที่ 4 ( 13 ตุลาคม 2566)
    * หน้าสำหรับตารางกิจกรรมของ Team ( กฤษฎิ์พิรัชย์, ณัฐภัทร ) 
    * หน้าสำหรับแก้ไขข้อมูลและ เพิ่มบทสนทนาภายในกิจกรรม ( กฤษฎิ์พิรัชย์, ณัฐภัทร ) 
    * หน้าแสดงวิธีการใช้โปรแกรม ( ณัฐริกา ) 
    * เรียงเวลาเข้าใช้งานของ User ในหน้าของ Admin ( ณัฐริกา )
    * สร้าง Models และ Collection ของ TeamComment ( กฤษฎิ์พิรัชย์ )
    * สร้าง Datasource ของระบบเรียงเวลา User ที่เข้าใช้งาน ( ณัฐริกา )
    * Graphic User Interface ของโปรแกรม ( ณัฐริกา, นลินี )





    