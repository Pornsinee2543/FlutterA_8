# Assignment-8

## เชื่อมต่อ Flutter กับ ฐานข้อมูล NoSQL (Firebase) ##

### UI
หน้าตาและการทำงานของแอปพลิเคชัน Firebase Meetup 
เป็นแอปพลิเคชันที่สามารถสมัครบัญชีหรือลงชื่อเข้าใช้ เพื่อเข้ามาพิมพ์ข้อความพูดคุยกันร่วมกันได้

**1. หน้าแรก Sign In**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243231.png" width="300">
<br>

**2. เมื่อกดปุ่ม SIGN IN RSVP จะแสดงช่องกรอกอีเมลขื้นมา**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243287.png" width="300">
<br>

**3. กรอกอีเมลเพื่อ Sign In**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243311.png" width="300">
<br>

**4. หากยังไม่ได้สมัครบัญชี จะมีช่องให้กรอกข้อมูลชื่อและพาสเวิร์ด**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243318.png" width="300">
<br>

**5. หลังจากกรอกเรียบร้อยแล้ว ก็สามารถกดปุ่ม SAVE เพื่อบันทึก หรือ จะกดปุ่ม CANCEL เพื่อยกเลิกก็ได้**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243346.png" width="300">
<br>

**6. เมื่อสมัครสมาชิกหรือลงชื่อเข้าใช้เรียบร้อย ก็จะพบข้อความแชตที่ผู้ใช้ก่อนหน้าพิมพ์ไว้ และมีปุ่ม LOGOUT ขึ้นมาเพื่อลงชื่อออก**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243357.png" width="300">
<br>

**7. สามารถพิมพ์ข้อความลงไปได้ในช่องข้อความ จากนั้นกดปุ่ม SEND เพื่อส่งข้อความ**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243375.png" width="300">
<br>

**8. หลังจากที่กดส่งข้อความ ชื่อและข้อความก็จะขึ้นไปอยู่ในตำแหน่งล่าสุด**

<img src="https://github.com/OhmMiee/Assignment-8/blob/15a2ea9ff5518e3f8036b02ed9b71694bea29c66/app-screenshot/Screenshot_1634243444.png" width="300">
<br>

### CODE
ในการใช้ Flutter ร่วมกับฐานข้อมูลแบบ NoSQL ซึ่งในแอปพลิเคชันนี้ เลือกใช้ Firebase เพื่อสร้างระบบยืนยันตน (Authentication) ในการสมัครบัญชีและลงชื่อเข้าใช้ เก็บและดึงข้อมูลมาแสดงในส่วนของแชตข้อความ
ซึ่งมีการนำโค้ดมาศึกษา ทดลองตามคู่มือ จากแหล่ง
```
https://firebase.google.com/codelabs/firebase-get-to-know-flutter#0
```
สามารถดูรายละเอียดขั้นตอนการพัฒนาเพิ่มเติมได้ตามลิงค์ที่ได้ให้ไว้

<br>
***นายจีระพันธ์ บุญสิน 61020593***
