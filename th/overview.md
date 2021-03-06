# 1. ทำความรู้จักกับโกโกบอร์ด

![](https://lh5.googleusercontent.com/17tsV9kfvhpPcAZYZ_wOjowRKrjiFHYJkLYbz5q8XhHpOLyCaOSUJTkyBfY7Jux8MWOk1wCI1MklfAnxjKHtrtGyqcBm5m8SFYZRWERY7vHG1WxAGzPYy90QgFRjqszl3tPWWqSa)

**โกโกบอร์ด** เป็นบอร์ดที่สามารถเขียนโปรแกรมได้ สามารถต่อกับเซ็นเซอร์ และมีเอาต์พุตที่สามารถควบคุมมอเตอร์และตัวขับต่างๆ ตัวบอร์ดได้ถูกออกแบบมาสำหรับเยาวชนอายุระหว่าง 10 ถึง 18 ปีและบุคคลทั่วไป หลักการออกแบบนั้นเป็นการส่งเสริมให้ผู้เรียนได้ใช้เวลาไปกับความคิด ความสร้างสรรค์ของตัวผู้เรียนโดยลดขั้นตอน รายละเอียดเชิงเทคนิคทางอิเล็กทรอนิกส์ ผู้เรียนสามารถค้นหาตัวตนได้รวดเร็วผ่านการเรียนรู้ไอเดียตนเองในการคิดในเชิงคอมพิวเตอร์และในหัวข้อที่เกี่ยวข้องอย่างเช่น เสต็ม \(**STEM**\) ตัวบอร์ดถูกออกแบบให้แตกต่างจากบอร์ดชนิดอื่นๆเช่น Arduino ยกตัวอย่าง การเริ่มต้นเขียนโปรแกรมควบคุม LED โดยผู้เรียนสามารถเริ่มต้นด้วยการเชื่อมต่อโมดูล LED และเริ่มคิดและออกแบบจังหวะการเปิดปิด LED ในลักษณะต่างๆได้ทันที แทนที่จะเริ่มต้นด้วยการปัก LED ลงโปรโตบอร์ดและต่อวงจรอิเล็กทรอนิกส์ต่างๆ ขณะเดียวกันการเขียนโปรแกรมก็ใช้หลักการนี้เช่นเดียวกัน ตัวบอร์ดสามารถใช้เซนเซอร์และตัวขับต่างๆ ได้หลากหลายชนิด

**โกโกบอร์ด**สามารถต่อเซนเซอร์ได้ทั้งหมด 8 พอร์ต เอาท์พุตจำนวน 4 พอร์ต และเขียนโปรแกรมด้วยภาษาโลโก้ หรือเขียนโปรแกรมในลักษณะลาก-วาง \(เรียกว่า Tinker\) **หน้าจอแสดงผลบนตัวบอร์ด**สามารถเขียนโปรแกรมควมคุมและสามารถแสดงค่าเซนเซอร์ที่ต่ออยู่ และยังสามารถต่อส่วนเสริมได้ 3 ประเภท คือ I2C และ UART \(Serial\) สำหรับต่อกับเซนเซอร์ชนิดดิจิตอลและโมดูลเสริมต่างๆ รวมไปถึงส่วนที่เป็นขา \(40 ขา\) สำหรับต่อกับ [Raspberry Pi](https://www.raspberrypi.org/)

## โปรแกรม GoGo Widget

![](https://lh4.googleusercontent.com/Mxys-VQMLJqW6mBLcSebEakfLMHW002dg4DMhHJZ5xW_sSUbpOYpeFMp2caEWUuWPB6DkIQ-Npwx195sJOk_di0SAMXh6LhkTpureebBtgsZetDWBK6pKgxkWJuz-twfmKaIN6kJ)

การเรียกใช้งานโกโกบอร์ด จะต้องใช้โปรแกรม **GoGo Widget** ซึ่งเป็นโปรแกรมที่ใช้สื่อสารระหว่างตัวบอร์ดกับคอมพิวเตอร์ มีความสามารถต่างๆดังนี้

* แสดงค่าเซ็นเซอร์พอร์ตต่างๆ
* ควบคุม DC มอเตอร์และเซอร์โว
* ตั้งค่าและทดสอบโมดูลเสริมต่างๆ
* อัพเดทเฟิร์มแวร์ให้กับตัวบอร์ด
* เขียนโปรแกรมโกโกบอร์ดโดยใช้ภาษาโลโก

## Tinker

## ![](https://lh4.googleusercontent.com/yvlV67xNU8ij-9H5N4pclZCeRfDzY_XQp7WfH3eTBNxatXTWl0dZCDhfaq9YLa5TGGxptiPwG0fvgoZWyJGVToBAXTkvnr7v_RyRyjloVuFx53IfD9iqOwhfTHXBGsvy9-_6Zvb8)

**Tinker** เป็นการเขียนโปรแกรมแบบลาก-วางสำหรับโกโกบอร์ดที่ทำงานอยู่บนเว็บบราวเซอร์ เหมาะสำหรับผู้เริ่มต้นที่ยังไม่คุ้นเคยกับภาษาโลโก้ ตัว Tinker จะแปลงบลอกคําสั่งต่างๆให้กลายเป็นภาษาโลโก้และสื่อสารไปยังโปรแกรม **GoGo Widget** ดังนั้นจะต้องเปิดโปรแกรม GoGo Widget ไว้เสมอขณะที่ใช้ Tinker นี้

