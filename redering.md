# การเรนเดอร์

1. วางโดนัทบน plane object กด 0 เพื่อปรับมุมกล้อง เมื่อ render ออกมาโดนัทที่ได้จะเหมือนกับภาพในตามมุมกล้องที่เราปรับ

![](images/donut5.png)

2. ปรับ Render Engine เป็น Cycles จากนั้นเปลี่ยนสี plane icing และตัว donut และปรับ subsurface 

![](images/donut6.png)

3. ปรับ lignt โดยเลือกแบบ point และปรับ power ตามต้องการ

![](images/donut7.png)

4. ลบ noise ออกจากโดนัท โดยเข้าที่ Compositing mode คลิกขวาที่พื้นที่ว่าง ๆ หาคำว่า denoise เชื่อมระหว่าง Render layers กับ Composite ปรับ UV editing 

![](images/donut8.png)

5. กด F12 เพื่อ Render ตัว Donut ออกมา

![](images/donut_part7.png)
