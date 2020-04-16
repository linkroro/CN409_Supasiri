# การทำอนิเมชั่น

  ในบทเรียนนี้ จะทำการขยับ object ง่าย ๆ โดยใช้ Blender ที่เป็นโปรแกรมสำหรับการทำงานด้านแอนิเมชันอีกโปรแกรมหนึ่งที่ได้รับความนิยมไม่น้อย เรียกว่าเป็นโปรแกรมที่นักทำแอนิเมชันทั้งหลายรู้จักกันดีเลยก็ว่าได้

สิ่งที่ได้เรียนใน course จะมี

*keyframes and channels
  keyframes เป็นเครื่องหมายที่บอกว่า ณ frame ที่เท่านี้มี object ขยับอย่างไรบ้าง
  เช่น Keyframe อาจจะกำหนดการเคลื่อนย้ายของ cube ใน 3 frame
  
*Visualization มีคุณสมบัติการสร้างภาพข้อมูลที่สำคัญในมุมมอง 3 มิติที่สามารถช่วยในการเคลื่อนไหว

*ประเภทของ keyframes 
  *Keyframe (สีขาว / สีเหลือง เป็นรูปเพชร)- keyframe ปกติ
  *Breakdown (เพชรสีฟ้าขนาดเล็ก) - สำหรับการเปลี่ยนระหว่างตำแหน่งที่สำคัญ
  *Moving Hold (สีเทาเข้ม/สีส้ม รูปเพชร) - แสดงระหว่างการเพิ่มการเคลื่อนไหวเล็กน้อยที่ object ที่กำหนด
  *Extreme (สีชมพูอันใหญ่รูปเพชร)
  *Jitter (เพชรสีเขียวอันเล็ก ๆ) 
  !()[images/01.png]
  
 ### Editing
 ## Insert Keyframes
  *ในมุมมอง 3 D การกด I จะแสดง menu ที่สามารถเพิ่ม keyframe ได้
  *เลือก object แล้วกด I แล้วเลือก Insert Keyframe จากเมนู
## Auto Keyframe
!()[images/02.png]
  เป็นปุ่มบันทึก timeline โดยเมื่อเราปรับเปลี่ยน object หรือ move ก็จะเพิ่ม keyframe ในอัตโนมัต
## Delete Keyframes
  *กด Alt-I เพื่อลบคีย์ออกจากวัตถุที่เลือกในเฟรมปัจจุบัน
## Clear Keyframes
  Object ‣ Animation ‣ Clear Keyframes…
  Removes all keyframes from the selected object.
