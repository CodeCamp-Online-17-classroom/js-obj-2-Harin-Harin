# js-lab-48
### Lab48 Object: Guess Result
บรรทัดที่มี * ให้ผลลัพธ์เป็นอะไร เพราะอะไร  
หริณ มาเบ้า  
ได้ผลลัพท์เป็น {email: 'cc@gmail.com', isActive: false} 
แสดง email: 'cc@gmail.com' เพราะ console.log(user); แสดงค่าก่อน user = {}; ที่จะ error  
แสดง isActive: false เพราะมีการเปลี่ยนค่าก่อนแสดง console.log

```JavaScript
const user = {
  email: 'cc@gmail.com',
  isActive: true
};

user.isActive = false;
console.log(user); // *
user = {};
console.log(user); // **
```
