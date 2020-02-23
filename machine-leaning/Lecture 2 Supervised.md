# ศึกษา Machine Learning by Stanford University ใน Coursera
# 18 Feb 2020
## Lecture 3 Supervised ( การเรียนรู้ภายใต้การควบคุม )

### Supervised ( การเรียนรู้ภายใต้การควบคุม )
Supervised หมายถึงการที่เรามีข้อมูลที่ประกอบด้วย Input และ Output นำไปบอกเครื่องจักร ( Machine ) 
ว่านี่คือส่วนของ Input และนี่คือผลลัพธ์ Output เมื่อผ่านกระบวนการบางอย่าง เครื่องจักรจะเรียนรู้จากข้อมูลที่เรามีให้ และหาความสัมพันธ์กันระหว่าง Input กับ Output จนได้รูปแบบการคำนวณแบบนึงขึ้นมา ( เป็นสมการูปแบบนึง )

ซึ่งรูปแบบของ Supervised ก็จะถูกแบ่งออกเป็น 2 รูปแบบใหญ่ ๆ คือแบบ Regression และ Classification 

โดยรูปแบบ Regression จะมีไว้สำหรับการทำนายค่าที่เป็นแบบต่อเนื่อง ( Continuous Output ) เช่น ทำนายราคาจาก กราฟเส้น ราคาต่อขนาดที่ดิน

![Regression](https://firebasestorage.googleapis.com/v0/b/selfblog-fcc59.appspot.com/o/image%2Fmachine-learning-stanford%2Fno-of-bed-room.png?alt=media&token=0d3c0fc4-dacd-415f-903f-b88639dcc380)

แต่รูปแบบ Classification จะมีไว้สำหรับการทำนายในรูปแบบไม่ต่อเนื่อง ( Discrete Output ) เช่น การจำแนกว่าเป็นรูปสัตว์หรือรูปต้นไม้

![Classification](https://firebasestorage.googleapis.com/v0/b/selfblog-fcc59.appspot.com/o/image%2Fmachine-learning-stanford%2Fanimal-or-tree.png?alt=media&token=ff13219e-1579-4247-84bc-d63d50e96dd9)


---
### กลับไปเรียนเรื่องพวกนี้ด้วยนะ
https://www.khanacademy.org/math/cc-eighth-grade-math