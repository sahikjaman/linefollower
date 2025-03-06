PRARORO BOT
==
A line follower robot designed to follow any path. This robot uses various mechanical and electrical components to perform its tasks efficiently. The overall operating voltage of this robot is 12 volts, which is obtained from three 18650 batteries arranged in series with each battery having a capacity of 3000mAh.
--
The robot is equipped with two yellow DC gearbox motors, each operating at 3-10V. These motors have a maximum speed of 200 rpm and a torque of 0.5 Nm, enough to move the robot stably and carry a load of about 500 grams. These motors are connected to 65 mm diameter rubber wheels, providing good grip and the stability needed when following a line, with one small caster wheel to provide additional support and stability.

The robot control system uses an Arduino nano microcontroller that implements the if algorithm. This algorithm ensures that the robot can follow the line with precision and smooth movement. To detect the line, the robot uses a qtr-8 analog sensor that has 8 analog input channels. These sensors send data to the microcontroller, which then processes the data to control the speed and direction of the motor through the L298N motor driver. This driver is capable of handling up to 2 Amps per channel, which is sufficient for the yellow DC gearbox motor used.

robot design 

![Picture1](https://github.com/user-attachments/assets/02cf36f1-d2cb-430a-ac17-17eb0015c873)

track 

![Gambar WhatsApp 2024-08-28 pukul 20 09 01_316bd31c](https://github.com/user-attachments/assets/fe16a085-b4d6-4cfb-9972-e34e20b5341a)

robot on track

https://www.youtube.com/shorts/tY2vrc1NZro

