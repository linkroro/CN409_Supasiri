# การตัดต่อวิดีโอ
  นอกจากการสร้างแบบจำลองและภาพเคลื่อนไหวแล้ว Blender สามารถใช้ในการแก้ไขวิดีโอ เราสามารถใช้เอฟเฟกต์ต่าง ๆ เพื่อสร้างการตัดต่อวิดีโอที่มีประสิทธิภาพโดยเฉพาะอย่างยิ่งเมื่อคุณรวมเข้ากับการเคลื่อนไหวของ Blender
  
  ในการใช้งานนั้นให้เรานำวิดีโอหลาย ๆ คลิปมาวางแบบ end-to-end (บางกรณีวางทับ) การเฟดและการเปลี่ยนผ่านเพื่อเชื่อมโยงส่วนท้ายของคลิปหนุ่ง และสามารถเพิ่มเสียงและซิงโครไนซ์เวลาให้ตรงกับวิดีโอ

### View Types
* Sequencer - ดูคุณสมบัติของไทม์ไลน์และคุณสมบัติของ strip
* Preview - ดูหน้าต่างแสดงตัวอย่างและคุณสมบัติดูตัวอย่าง
* Sequencer/Preview - ดูทั้งสองอย่าง

![image](images/04.png)

### Navigating
* Header

  ![image](images/05.png)

* Markers Menu - ถูกใจเพื่อแสดงถึงเฟรมที่มีประเด็นสำคัญหรือเตุการณ์สำคัญในภาพเคลื่อนไหว

  ![image](images/06.png)

### Strip
  คือ container ที่เก็บเฟรมของ input เช่น vdo ถูกกำหนดโดยเริ่มต้นเฟรม ความยาวจะปรากเป็นสีเหลียมแนวนอน
  
  ![image](images/07.png)

### Image/Sequence Strips
  Single Image - เมื่อคุณเพิ่มภาพนิ่งเดียว (* .jpg, * .png ฯลฯ ) Blender จะสร้างแถบยาว 25 เฟรมซึ่งจะแสดงภาพนี้ตามช่วงของแถบ
### Sound Strips
  สามารถแก้ไขแทร็กเสียงได้เช่นเดียวกับภาพและวิดีโอ โดยเพิ่มรูปแบบคลื่นเสียง WAV, mp3 และไฟล์รูปแบบเสียงอื่น ๆ จากไดรฟ์
  
  ![image](images/08.png)

### Text Strips
  แถบข้อความอนุญาตให้แสดงข้อความโดยตรงในตัวแก้ไขลำดับ แถบจะแสดงข้อความที่แทรกในช่องข้อความในลำดับสุดท้าย
  
  ![image](images/09.png)

### Transform
  การจัดการภาพ มันหมุนและปรับขนาดภาพ
  * Interpolation
    * NONE - ไม่มีการแก้ไข
    * Bilinear - การแก้ไขที่ง่ายระหว่างพิกเซลที่อยู่ติดกัน
    * Bicubic - การแก้ไขคุณภาพสูงสุด
  * Translation Unit - ควบคุมค่าอินพุตเป็นเปอร์เซ็นต์หรือพิกเซล
  * Position - เคลื่อนย้าย input ตามแนวแกน X และ Y
  * Uniform Scale - ขยาย input อย่างสม่ำเสมอตามแนวแกน X และ Y
  * Scale - ปรับขนาดภาพบนแกน X และ Y
  * Rotation - หมุนอินพุตสองมิติตามแนวแกน Z
### Speed Control
  การควบคุมให้วิดีโอมีความเร็วขึ้นหรือช้าลงกว่าปกติ ตาม Global Speed คือถ้าน้อยก่า 1.0 คือช้าลง ถ้ามากกว่า 1.0 จะทำให้เร็วขึ้น การเล่นเร็วขึ้นหมายความว่าเฟรมบางเฟรมถูกข้ามไปและแถบจะขาดเฟรมก่อนเฟรมสิ้นสุด
  
  ![image](images/10.png)

### Editing
  * Move - กด G จะย้ายแถบทั้งหมด เลื่อนเมาส์ในแนวนอน (ซ้าย/ขวา) เพื่อเปลี่ยนตำแหน่งของแถบเวลา ย้ายแนวตั้ง (ขึ้น / ลง) เพื่อเปลี่ยนช่อง
  * Move/Extend from Frame - กด Eจะช่วยให้ขยายแถบได้ คล้ายกับ move ช่วยในการยืดเวลาหรือทำให้สั้นลง รอบ ๆ เฟรมปัจจุบัน
  * Slip Strip Content - เปลี่ยนตำแหน่งของเนื้อหาของแถบโดยไม่ต้องย้ายแถบตัวเอง
  * Duplicate Strips - ทำสำเนา Strips จากนั้นลากไปยังเวลาและช่องที่ต้องการ
  * Delete Strips - Delete / X
  
## คลิปตัดต่อวิดีโอในชั้นเรียน

 [video editing](https://youtu.be/F5TusOM1aI4)
