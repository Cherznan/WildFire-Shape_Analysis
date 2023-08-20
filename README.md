# WildFire-Shape_Analysis
การศึกษา และ วิเคราะห์รูปร่างการเกิดของไฟป่า โดยผ่านกระบวกการคิดวิเคราะห์โดยใช้ library Python ประกอบกับ โปรแกรม Gis ช่วยในการศึกษา
# แนวคิด
เชื่อว่าจากข้อมูลเบื้องต้นที่ได้ทำการศึกษามานั้น มีสมมติฐานว่า ไฟป่าที่เกิดขึ้นเองตามธรรมชาตินั้น จะมีลักษณะเกาะกลุ่มกันเป็นก้อน หรือมีการเคลื่อนที่กระจายตัวเป็นลักษณะกลุ่ม
และ ยังมีสมมติฐานที่คาดว่าไฟป่าที่มีลักษณะการเกิดรูปร่างเป็นแนวเส้นนั้น อาจจะเกิดขึ้นจากมนุษย์
# Step 0 : Started
# ![S__5316618](https://github.com/Cherznan/WildFire-Shape_Analysis/assets/104462961/5bc0638f-59e5-4280-9b47-68b92ebebe73)
## Planning เบื้องต้น
1. การศึกษาและตั้งสมมติฐานการเกิดของไฟป่า
2. เลือกบริเวณที่จะใช้เป็นพื้นที่ทดลองที่เกิดเหตุการ์ไฟป่าขึ้นจริง ร่วมถึงช่วงระยะที่เกิดเหตุกาณ์นั้น เพื่อนำมาเป็นข้อมูลังเกตุเบื้องต้น
# !
3. ศึกษาเกี่ยวกับ sensor VIIRS 375 m ซื้อเป็นภาพดาวเทียมแบบ Infrared ที่นำมาใช้เป็นข้อมูลประกอบการวิเคราะห์ในครั้งนี้ ร่วมถึงการสังเกตุ cleaning data และความถูกต้องน่วมถึงระดับ error ของข้อมูล