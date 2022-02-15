# อธิบายโปรแกรม
## Lab1-การเขียนโปรแกรมเพื่อรันบน Microcontroller

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาทีฃ

-void loop()

ใช้คำสั่ง cnt ทำให้แสดงค่าตัว 0.3 วินาที บวกทุกๆ 1 วินาทีไปเรื่อยๆ

## Lab2-การเขียนโปรแกรมค้นหา WIFI

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาที

set up ให้พร้อมใช้งานได้ในทุกๆ 0.1 วินาที

-void loop() 

สแกนหา WIFI บริเวณรอบๆ

## Lab3-การเขียนโปรแกรม output สัญญาณ Digital

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาที

set ให้ port0 เป็น output 

-void loop() 

ใช้คำสั่ง cnt เมื่อเป็นเลขคู่จะส่งค่าเป็นoff(HIGH)

ใช้คำสั่ง cnt เมื่อเป็นเลขคี่จะส่งค่าเป็นon(LOW)

แสดงผล 0.5 วินาที บวกทุกๆ 1 วินาที

## Lab4-การเขียนโปรแกรม input สัญญาณ Digital

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาที

ให้port0เป็นinput port2เป็นoutput

-void loop()

ให้การอ่านport0เป็นinput นำเข้า0และ1

ถ้าแสดง1เป็นค่าLOW ไฟจะOFF  แสดงค่าเป็น0เป็นHIGH ไฟจะON

## Lab5-การเขียนโปรแกรมเชื่อมต่อ WIFI และ Webserver

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาที

สั่งคำสั่ง connect WIFI กับตัวที่ต้องการ เพื่อใช้กับ Web server

-void loop()

มีคำสั่ง cnt ไปเรื่อยๆ

## Lab6-การเขียนโปรแกรมสร้าง WIFI และ Webserver

-void setup()

serial.begin(115200)ใช้ความเร็วส่งข้อมูล 115200 ครั้งต่อวินาที

สั่งคำสั่งสร้าง WIFI access point 

กำหนด IP Address


