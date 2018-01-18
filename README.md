﻿# ภาษา PHP
![Image](https://www.crispinfox.com/wp-content/uploads/2015/10/php.jpg)


* ในบทเรียนนี้ คุณจะได้เรียนภาษา PHP ในพื้นฐาน เช่น โครงสร้างของภาษา ตัวแปร ตัวดำเนินการ คำสั่งควบคุม อาเรย์ ฟังก์ชัน และการเขียนโปรแกรมภาษา PHP แบบออบเจ็ค คุณจะเข้าใจเกี่ยวกับการสร้างคลาสและออบเจ็ค สำหรับการสอนในบทเรียนนี้จะเป็นแบบ Console และไม่ได้ครอบคลุมถึงการพัฒนาเว็บไซต์ ต่อไปมาทำความรู้จักกับภาษา PHP ก่อนที่คุณจะเริ่มต้นการเขียนโปรแกรม

* PHP คือภาษาสำหรับทำงานด้านฝั่งของเซิร์ฟเวอร์ (server-side scripting) ถูกออกแบบมาสำหรับการพัฒนาเว็บไซต์ แต่มันก็ยังสามารถใช้เขียนโปรแกรมเพื่อวัตถุประสงค์ทั่วไปได้ PHP ถูกสร้างโดย Rasmus Lerdorf ในปี 1994 โดยที่ PHP ในปัจจุบันได้ถูกพัฒนาโดยทีมพัฒนาของภาษา PHP ซึ่งคำว่า PHP นั้นย่อมาจาก Personal Home Page ซึ่งในปัจจุบันนั้นหมายถึง PHP: Hypertext Preprocessor โค้ดของ PHP นั้นสามารถฝังกับโค้ดของ HTML ได้ ซึ่งมันสามารถนำไปร่วมใช้ร่วมกับระบบเว็บเท็มเพลตที่หลากหลาย ระบบจัดการเนื้อหา (CMS) หรือเว็บเฟรมเวิร์ค การทำงานของ PHP นั้นเป็นแบบ Interpreter ที่ถูกพัฒนาเป็นแบบโมดูลในเว็บเซิร์ฟเวอร์ หรือ Common Gateway Interface (CGI) โดยเซิร์ฟเวอร์จะทำการรวมโค้ดที่ผ่านการแปลผล และประมวลผลเป็นหน้าเว็บเพจ และยังสามารถทำงานได้บน Command-line interface (CLI) และนอกจากนี้ PHP ยังถูกนำไปพัฒนาแอพพลิเคชันทางด้านกราฟฟิก



## แนะนำภาษา PHP
### PHP คืออะไร
  ในช่วงแรกภาษาที่นิยมใช้งานบนระบบเครือข่าย คือ ภาษา HTML (Hypertext Markup Language) แต่ภาษา HTML มีลักษณะเป็น Static คือ ภาษาที่มีลักษณะของข้อมูลคงที่ ซึ่งไม่เพียงพอต่อความต้องการในปัจจุบันที่นิยมใช้ระบบเครือข่าย Internet เป็นศูนย์กลางในการติดต่อระหว่างกัน ทำให้ต้องการใช้เว็บไซต์ที่มีลักษณะเป็นแบบ Dynamic คือ เว็บไซต์ที่ข้อมูลสามารถเปลี่ยนแปลงได้โดยอัตโนมัติตามเงื่อนไขต่าง ๆ ที่ผู้เขียนเว็บไซต์เป็นผู้กำหนด และการควบคุมการทำงานเหล่านี้จะกระทำโดยโปรแกรมภาษาสคริปต์ เช่น ภาษา PHP ซึ่งเป็นภาษาหนึ่งที่ได้รับความนิยมเป็นอย่างมากในปัจจุบัน
 PHP ถูกสร้างขึ้นในปี ค.ศ.1994 โดย [Rasmus Lerdorf](http://lerdorf.com/bio.php) ต่อมามีผู้ให้ความสนใจเป็นจำนวนมาก จึงได้ออกเป็นแพ็คเกจ "Personal Home Page" ซึ่งเป็นที่มาของ PHP โดยภาษา PHP เป็นแบบ Server Side Script และเป็น Open Source ที่ผู้ใช้ทั่วไปสามารถดาวน์โหลด Source Code และโปรแกรมไปใช้ฟรี ได้ที่ [http://www.php.net](http://www.php.net)
  
  พอกลางปี ค.ศ.1995 เขาก็ได้พัฒนาตัวแปลภาษา PHP ขึ้นมาใหม่ โดยใช้ชื่อว่า PHP/FI เวอร์ชั่น 2 ซึ่งได้เพิ่มความสามารถในการรับข้อมูลที่ส่งมาจากฟอร์มของ HTML (จึงมีชื่อว่า FI หรือ Form Interpreter) นอกจากนั้นยังเพิ่มความสามารถในการติดต่อกับฐานข้อมูลอีกด้วย จึงทำให้ผู้คนเริ่มหันมาสนใจ PHP กันมากขึ้น 
  
  ในปี 1997 มีผู้ร่วมพัฒนา PHP เพิ่มอีก 2 คน คือ [Zeev Suraski](https://en.wikipedia.org/wiki/Zeev_Suraski) และ [Andi Gutmans](https://en.wikipedia.org/wiki/Andi_Gutmans) (กลุ่มที่เรียกตัวเองว่า Zend ซึ่งย่อมาจาก Zeev และ Andi ) โดยได้แก้ไขข้อบกพร่องต่างๆ และเพิ่มเติมเครื่องมือให้มากขึ้น
## โครงสร้างของภาษา PHP
ภาษา PHP มีลักษณะเป็น embedded script หมายความว่าเราสามารถฝังคำสั่ง PHP ไว้ในเว็บเพจร่วมกับคำสั่ง(Tag) ของ HTML ได้ และสร้างไฟล์ที่มีนามสกุลเป็น .php, .php3 หรือ .php4 ซึ่งไวยากรณ์ที่ใช้ใน PHP เป็นการนำรูปแบบของภาษาต่างๆ มารวมกันได้แก่ C, Perl และ Java ทำให้ผู้ใช้ที่มีพื้นฐานของภาษาเหล่านี้อยู่แล้วสามารถศึกษา และใช้งานภาษานี้ได้ไม่ยาก


```javascript 
1 <html> 
2 <head> 
3 <title>Example 1 </title> 
4 </head> 
5 <body>
6 <? 
7   echo"Hi, I'm a PHP script!"; 
8 ?> 
9 </body> 
10 </html> ```


> ขอบคุณสำหรับที่มา [ภาษา PHP](http://marcuscode.com/lang/php)