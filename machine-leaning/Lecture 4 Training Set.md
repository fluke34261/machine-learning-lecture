# ศึกษา Machine Learning by Stanford University ใน Coursera
# 18 Feb 2020
## Lecture 3 Training Set ชุดข้อมูลสำหรับการเรียนรู้ของ Supervised

### Training Set ( ชุดข้อมูลสำหรับการเรียนรู้ของ Supervised )

![Training Set](https://firebasestorage.googleapis.com/v0/b/selfblog-fcc59.appspot.com/o/image%2Fmachine-learning-stanford%2Ftraining-set-one-feature.png?alt=media&token=0eb5c70d-d110-44d3-ae39-3cf86be4caf3)


จากรูปด้านบน เป็นตัวอย่างของ Training Set โดยสามารถบ่งบอกคุณลักษณะได้ดังนี้

1. มีจำนวนตัวอย่าง ( __m__ ) = 5
2. ให้ จำนวนห้องเป็น Input (x)
3. ให้ ราคาเป็น Output (y)

และสามารถระบุตำแหน่งของค่าต่าง ๆ ใน Training Set ได้ดังต่อไปนี้

<div>x<sup>( 3 )</sup> = 2</div>
<div>y<sup>( 4 )</sup> = 2.25</div>

จึงทำให้รูปแบบการเรียนรู้ของ Supervised มีรูปแบบดังต่อไปนี้

![Hypothesis](https://firebasestorage.googleapis.com/v0/b/selfblog-fcc59.appspot.com/o/image%2Fmachine-learning-stanford%2Fhypothesis.png?alt=media&token=42235869-6980-4362-9167-6c99c920f969)

และสมการที่ Hypothesis จะอยู่ในรูปแบบของ สมการเชิงเส้น <div><strong>h<sub>θ</sub>(x) = θ<sub>0<sub> + θ<sub>1</sub>x</strong></div> หรือเรียกสั้น ๆ ได้ว่า <div><strong>h(x)</div>

> ซึ่งแนะนำให้ทำความเข้าใจเสียก่อน [ลิ้งสอนสมการเชิงเส้น](https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:linear-equations-graphs) 
