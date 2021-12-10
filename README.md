# FRA502
# ทำโดย
นาย พชรพล ทวีปัญญายศ 62340500037
# ลิงค์วิดีโอ
https://drive.google.com/file/d/1XCsM1OT2OUW6FlU47BZirr7GMhMldnCN/view?usp=sharing

# คู่มือการใช้งาน
1.เปิดเทอร์มินอล เเล้วพิมพ์ roscore
2.เปิดเทอร์มินอลอันใหม่ขึ้นมาเล้วพิมพ์ source catkin_ws/devel/setup.bash
3.ในเทอร์มินอลข้อ 2 พิมพ์ roslaunch robot car_spawn.launch
4.เปิดเทอร์มินอลอันใหม่ขึ้นมาเล้วพิมพ์ roslaunch robot car_navigation.launch
5.เปิดเทอร์มินอลอันใหม่ขึ้นมาเล้วพิมพ์ roslaunch robot goal.launch
6.ถ้าติดปัญหารันไฟล์ python ให้เข้าไปที่ directory ของไฟล์ goal.py เเล้วพิมพ์ chmod +x goal.py
7.การสั่งงานด้วยเสียง 
![image](https://user-images.githubusercontent.com/78725909/145529558-6d311113-1603-4ad5-b56d-e9f86492c6f7.png)
ขึ้นข้อความนี้คือให้พูดอะไรก็ได้เพื่อตรวจเสียง
8.ต่อไปหุ่นจะเดินไปยังตำเเหน่งเริ่มต้นที่กำหนดไว้
![image](https://user-images.githubusercontent.com/78725909/145529914-52173a48-e5cf-485d-9e69-7c8c8bc561cc.png)
9.เเล้วจะให้พูดว่าจะไปหยิบอะไร มีเนื้อ ปลา ถั่ว ผัก ![image](https://user-images.githubusercontent.com/78725909/145531645-8ff1ba9e-e832-48a7-8c78-b35e3c55895d.png)
10.พอไปถึงหุ่นยนจะเดินกลับมาที่ตำเเหน่งเเรกอัติโนมัติ

# ปัญหาที่พบเจอ
1.ในตอนทำ navigation หุ่นที่ผมใช้ทำเเผนที่มีการสั่นผมเลยเปลี่ยนหุ่นตอนทำ navigation(หุ่นคนละตัวกับที่ใช้ทำ map)
2.navigation ไม่เเม่นยำมากบางที่ยังมีการชนวัตถุเเละทำงานช้า
3.ตอนใช้คำสั่งเสียงบางทีต้องพูดย้ำหลายครั้ง


