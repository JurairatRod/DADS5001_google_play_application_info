## Dataset 
  Google Play Store Apps: https://www.kaggle.com/datasets/lava18/google-play-store-apps

<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137283700/51e12a45-3693-4735-b8a9-eadc84a28f72"/>
</p>

# Google Play Store Application Installation
  ในยุคที่เทคโนโลยีมีบทบาทสำคัญในชีวิตประจำวันของมนุษย์ สมาร์ทโฟนเป็นอุปกรณ์ที่ได้รับความนิยมและใช้งานกันอย่างแพร่หลาย
  เป็นส่วนสำคัญที่สร้างประสบการณ์และการใช้ชีวิตที่สะดวกสบายขึ้น อีกทั้งยังเป็นช่องทางการหารายได้สำหรับผู้ที่ผลิตแอปพลิเคชัน
  ทั้งในช่องทางการขายแอปพลิเคชัน การรับโฆษณาในแอป หรือการขายของในแอป ทำให้ปัจจุบันมี Application เกิดขึ้นมากมาย
  Google Play Store เป็นหนึ่งในแพลตฟอร์มสำหรับดาวน์โหลดแอปพลิเคชันที่มีผู้ใช้งานมากที่สุดในโลก 
  แอปพลิเคชันที่มีให้เลือกใน Google Play Store มีหลายประเภทเช่น เกมส์ แอปพลิเคชันสำหรับสื่อบันเทิง โซเชียลมีเดีย และเครื่องมือที่มีประโยชน์ต่างๆ 
  
  จากฐานข้อมูลที่เลือกไว้ เราสามารถวิเคราะห์จำนวนและมูลค่าของแอปพลิเคชันทั้งหมดใน Google Play Store ในปัจจุบัน 
  ซึ่งประกอบด้วยแอปพลิเคชันที่ฟรีและแอปพลิเคชันที่เสียเงิน การศึกษาจำนวนและมูลค่าของแอปพลิเคชันใน Google Play Store 
  จะช่วยให้เรารู้ว่ามีแอปพลิเคชันประเภทใดที่ได้รับความนิยมมากที่สุดและมีมูลค่าสูงที่สุด
  โดยข้อมูลที่เราได้รวบรวมจะถูกนำเสนอในรูปแบบของกราฟ แผนภูมิและสถิติเพื่อให้มองเห็นภาพรวมของปริมาณแอปพลิเคชัน ตามหัวข้อต่าง ๆ ดังนี้

  ### แอปพลิเคชันแบ่งตาม Category ต่าง ๆ และจำนวนการดาวน์โหลด
ข้อมูล แอปพลิเคชัน มากกว่า 10,000 แอปพลิเคชัน สามารถจัดกลุ่มได้ด้วยประเภท (Category) ของแอปพลิเคชันที่ผู้ผลิตแอปพลิเคชันได้ระบุไว้ 
จากกราฟที่ 1 เราจะเห็นได้ว่า Category ที่มีจำนวนแอปพลิเคชันเยอะที่สุดคือ Family ซึ่งมีจำนวนสูงถึง 1,972 แอปพลิเคชัน ซึ่งนับเป็นสัดส่วน 18% ของจำนวนแอปพลิเคชันทั้งหมด
 

![graph_1](https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/1b213687-bb08-474f-9b9d-20323fe4b546)
<p align="center">
  กราฟที่ 1 A number of Applications in each category
</p>

จากนั้นเรามาดูกันว่าจำนวนการดาวน์โหลดของแอปพลิเคชันในแต่ละ Category มีแนวโน้มเป็นอย่างไร (โดยจำนวนการดาวน์โหลดนั้นมากจากการประมาณการจำนวนการดาวน์โหลดของแต่ละแอปพลิเคชัน)

จากกราฟที่ 2 จะเห็นว่า แอปพลิเคชันที่มียอดรวมการดาวน์โหลดมากที่สุดจะเป็น Category เกมส์ (35,000 M) ในขณะที่ แอปพลิเคชัน ใน Category Family ที่มีจำนวน แอปพลิเคชันมากที่สุดกลับมียอดรวมดาวน์โหลดอยู่ในลำดับที่ 5 (10,000 M)


![graph_2.0](https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/6b5a27aa-f440-4d03-85e2-6f84269e0f32)
<p align="center">
  กราฟที่ 2 Installation of each category
</p>

ตารางที่ 1 แสดง 10 ประเภทแอปพลิเคชันที่มียอดการดาว์นโหลดสูงที่สุดโดยเรียงจากมากไปน้อย
<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/bfe42279-c96f-4bf9-be28-6891cfb71536"/>
</p>
<p align="center">
  ตารางที่ 1 Top 10 installation categories
</p>

และเมื่อเราโฟกัสไปที่แอปพลิเคชันที่มีจำนวนการดาวน์โหลดมากกว่า 1 ล้านครั้งขึ้นไป 

จากตารางที่ 2 จะเห็นว่าถึงแม้ใน Google Playstore จะมี แอปพลิเคชัน ที่อยู่ใน Category Family มากที่สุด แต่ แอปพลิเคชัน ที่มีจำนวนการดาวน์โหลดที่มากกว่า 1 ล้านครั้งขึ้นไปเป็น Category Games ที่มีจำนวนมากที่สุด โดยหากโฟกัสที่ แอปพลิเคชัน ที่มีจำนวนการดาวน์โหลด 1,000,000,000 ขึ้นไป Category Game มีมากถึง 6 แอปพลิเคชัน โดย Category Family มีเพียง 1 แอปพลิเคชัน

<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/39a39ae8-6769-4197-a55c-43ce2bad368a"/>
</p>
<p align="center">
  ตารางที่ 2 Installation of each category
</p>

  ### แอปพลิเคชันที่ฟรีและ แอปพลิเคชันที่เสียเงิน
แอปพลิเคชันที่เปิดให้ดาวน์โหลดใน Google Play Store นั้น มีทั้งแอปพลิเคชันที่ฟรี และ แอปพลิเคชันที่เสียเงิน 
จากข้อมูลเราสามารถเห็นจำนวนที่แตกต่างระหว่างแอปพลิเคชันที่ฟรีและ แอปพลิเคชันที่เสียเงิน หากแบ่งตามจำนวนครั้งที่ดาวน์โหลด จะเห็นได้ว่าจำนวน แอปพลิเคชัน ที่มีการดาวน์โหลดมากกว่า 50 ล้านครั้ง ล้วนเป็น แอปพลิเคชัน ที่ฟรีทั้งหมด
<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137284926/bbabdd6b-9c2c-479e-872f-e80d34329352"/>
</p>
<p align="center">
  ตารางที่ 3 Number of applications categorized by installation and type (Free or Paid)
</p>

![download](https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137284926/236e9a07-927b-459c-94b0-d61db99b74ac)
<p align="center">
  กราฟที่ 3 Number of applications categorized by installation and type (Free or Paid)
</p>

   ### มูลค่าของแอปพลิเคชันที่เสียเงิน
ในส่วนของแอปพลิเคชันที่เสียเงิน (Paid Application) เราสามารถเห็นจำนวน Paid แอปพลิเคชัน ทั้งหมด 800 แอปพลิเคชัน 
จากกราฟที่ 4 จะเห็นได้ว่า Category Family มีจำนวนแอปพลิเคชันที่เสียเงินสูงสุดถึง 191 แอปพลิเคชัน แต่จากกราฟที่ 5 มูลค่าโดยรวมของ Category Family นั้น เป็นจำนวน $2,087,113 ซึ่งน้อยกว่า Category Lifestyle ที่มีเพียง 19 แอปพลิเคชัน แต่มูลค่าโดยรวมของ Category นั้นสูงถึง $7,711,150 เนื่องจากราคาเฉลี่ยของ แอปพลิเคชัน สูงถึง $124.26 ซึ่งมากกว่าราคาเฉลี่ยของ แอปพลิเคชัน ใน Category family ($12.75) ถึง 89.7% โดยประมาณ
<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137283700/c0c973dd-5407-4cc9-8e24-57adc8821238"/>
</p>
<p align="center">
  กราฟที่ 4 Amount of paid application per category
</p>  

![graph_5](https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/77e0312b-a245-47b5-bc23-e6177b2a2161)
<p align="center">
  กราฟที่ 5 Paid application with average net value, Price, and installation
</p>

ทั้งนี้จากตารางที่ 4 และกราฟที่ 6 Category ของ Application ที่มีมูลค่าเฉลี่ยโดยรวมมากกว่า $500,000 มีเพียง 6 Category คือ Category LIFESTYLE ($7,711,150) , FAMILY ($2,087,113) , FINANCE ($1,862,975) , PHOTOGRAPHY ($1,103,278) , GAME ($879,956) และ EDUCATION ($675,745) ตามลำดับจากมูลค่าเฉลี่ยโดยรวมจากมากไปน้อย
<p align="center">
  <img src="https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/f26e08cb-f2d9-4d3c-94d0-de0f27348bbc"/>
</p>
<p align="center">
  ตารางที่ 4 Paid applications with an average 500K net value and up
</p>

![graph_6](https://github.com/JurairatRod/DADS5001_google_play_store_application_info/assets/137280369/7a373763-ac56-481b-8235-414d2e5aed0e)
<p align="center">
  กราฟที่ 6 Paid applications with an average 500K net value and up
</p>
