# Example นี้ มีชื่อว่า Sigma Delta Modulation LED Example หรือ sdm_led
ตัวอย่างนี้ใช้ไดรเวอร์ sigma-delta เพื่อสร้างสัญญาณที่ปรับได้บน GPIO หากเชื่อมต่อ LED หรือการควบคุมแบ็คไลท์ของ LCD เข้ากับขา output GPIO จะเห็นว่าไฟค่อย ๆ สว่างขึ้นและหรี่ลงอย่างต่อเนื่อง 
# ![image](https://github.com/user-attachments/assets/9e63e7f1-a0ee-43a3-9efd-1f54676118f9)
 เลือก Example sdm_led จากนั้นเข้าไปที่ไฟล์ sdm_led_example_main.c แล้วให้แก้ไข EXAMPLE_SIGMA_DELTA_GPIO_NUM ให้เป็น GPIO ที่เราต้องการ

![image](https://github.com/user-attachments/assets/09e8797f-4797-4702-8997-2d2831e108a4)

ทำการ Build และ Flash ลงบอร์ด

![image](https://github.com/user-attachments/assets/fcdb1474-87cd-4e1d-91c9-d94f98d5cbb7)

ใน Moniter จะแสดงการเชื่อมต่อของ GPIO ขาที่เราเลือกใช้รวมถึงสถานะของ LED 

![image](https://github.com/user-attachments/assets/7206d0b0-ea12-4770-8f76-7d226efb7257)

จะสังเกตได้ว่า LED จะมีความสว่างที่ไม่เท่ากันตลอดเวลาโดยจะเห็นว่าไฟค่อย ๆ สว่างขึ้นและหรี่ลงอย่างต่อเนื่อง 
