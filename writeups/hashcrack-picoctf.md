# hashcrack (Write-up)
Easy picoctf Write up (Crypto)

![hashcrack](../images/hashcrack-picoctf/_question.png)

### Description
A company stored a secret message on a server which got breached due to the admin using weakly hashed passwords. Can you gain access to the secret stored within the server? Additional details will be available after launching your challenge instance.

**คำแปล** 
> `บริษัทเก็บข้อความลับไว้บนเซิร์ฟเวอร์ แต่ระบบดันถูกเจาะเพราะแอดมินใช้รหัสผ่านที่มีการแฮชแบบอ่อนแอเกินไป คุณช่วยหาทางเข้าถึงความลับที่เก็บไว้ในเซิร์ฟเวอร์นี้ได้ไหม? รายละเอียดเพิ่มเติมจะแสดงขึ้นหลังจากที่คุณกดเปิด Instance ของโจทย์`

---
1. ทำการเชื่อมต่อเข้าไปที่เซิร์ฟเวอร์ที่ได้มาจากการ start instance ก่อน จะเจอกับค่า hash เสร็จแล้วให้เอาค่านั้นไปเข้าเว็บ https://hashes.com/en/decrypt/hash พอได้รหัสผ่านก็ให้กรอกได้เลยแต่โจทย์จะบอกว่าเราต้องทำการถอดรหัสค่าแฮชอีก เพราะยังไม่จบ
   
![1_hash](../images/hashcrack-picoctf/1_hash.png)

![1_pass](../images/hashcrack-picoctf/1_pass.png)
   
![1_solve](../images/hashcrack-picoctf/1_solve.png)

---
2.  คราวนี้ได้แฮชมาอีกก็ทำเหมือนเดิมกับข้อที่ 1 แต่ flag ก็ยังไม่โผล่มาเช่นเดิม

![2_hash](../images/hashcrack-picoctf/2_hash.png)

![2_pass](../images/hashcrack-picoctf/2_pass.png)
   
![2_solve](../images/hashcrack-picoctf/2_solve.png)

---
3. ทำเช่นเดียวกับข้อ1,2 คราวนี้จะได้ flag โผล่มาเป็นอันจบ

![3_hash](../images/hashcrack-picoctf/3_hash.png)

![3_pass](../images/hashcrack-picoctf/3_pass.png)
   
![3_solve](../images/hashcrack-picoctf/3_solve.png)

---

*For Educational Purpose Only*
