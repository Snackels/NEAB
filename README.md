# Documentation for WRO Future Engineer 2025
by Team *YBR-NEAB*


![]([https://lh3.googleusercontent.com/u/0/drive-viewer/AJc5JmS-gvzix8rqHiP9ptq7tHeZygsObiNOmIOgPZ77TDPFEsBTKvNW-LatH-ngLn_0nhACZ-FHElf1pMwIivX24kCyNMjfTw=w1920-h929](http://www2.yothinburana.ac.th/website/images/logo1.png))


<p align="center">
  <img src="https://ybrobot.club/image/YB%20Robot%20logo.png" width="400"/>
</p>
<p align="center">
<b>By Yothinburana School Robot Club</b>
</p>
<br><br><br><br>

### This Github repository contains:
- [About our team](#about-our-team)
- [Engineering Consideration](#engineering-consideration)
- [Hardware Information](#hardware-information)
- [Raspberry Pi Program](#raspberry-pi-program)
- [Arduino Program](#arduino-program)
- [Collecting Data](#collecting-data)
- [Cleaning Data](#cleaning-data)
- [Machine Learning](machine-learning)
- [Contact Us!](#contact)

# **About our team.**

Our team consists of three members, each assigned a different role:

1. Vichaiwat Koonsap – I am responsible for gathering data for our team members and taking detailed notes, which are then compiled into this documentation.
2. Norapat Kaset – Norapat is responsible for designing and building our robot.
3. Vorawet Narkglom – Vorawet is the programmer who coded the robot.   

# **Engineering Consideration.**

During the design process of our robot, we faced several engineering challenges, particularly in translating real-world measurements into our 3D modeling software. After printing, we frequently encountered issues with small features—for example, a M3 screw thread could not be printed accurately caused by 3d printer's nozzle size, resulting in undersized holes. This showed the importance of accounting for 3D printer limitations during the design stage. Paying close attention to these details helps minimize unnecessary redesigns and reprints.

Another key learning was the importance of incorporating a differential system. At first, we placed gears of equal size next to each other, but this setup proved ineffective. By integrating a differential, the wheels were able to rotate at different speeds—an essential factor for smooth turning and overall robot performance.

The robot chassis was modeled in Fusion 360 and manufactured using FDM 3D printing. This approach provided durability, lightweight construction, and effective protection for the onboard hardware. The design was fully customized by our mechanic to meet the specific needs of our robot.

## Printed Robot Chassis
### Lower Base
This part is the base of our robot. It holds almost all the essential parts; controller, motor, steering servo, light sensors, buck converter, and differential. In designing this part, we need to account for the precise component sizes. In our robot, we uses a LEGO TECHNIC parts like axle, differential, and gear to ensure that those part would not break during our section. And to hold that axle, we used poles on the back to hold the LEGO part in place. With this design, it allows the robot to reach it's full potential.

### Upper Base.
This part was design to stay 3 centimeters on top of the lower base. It holds the remaining components. It also provides more stability for our robot. To make sure that the screw wouldn't interfere with lower part. We utilized the counterbore technic to hide the screw flawlessly giving that seemless look. Additionally, it also included with a battery slot at the back.

### LiDAR Holder
It was placed on top of the upper base. This component ensrure that the LiDAR stays higher than other parts to avoid the LiDAR from detecting the robot. And it also include a slot for our gyro sensor. It sits right underneath the LiDAR. With this design, it minimize our robot size and ensure that the LiDAR doesn't exceed the 10cm limit.

### Camera mount
This component serves as a stand for our camera. It also comes with the cover for the front and top of the camera. This serves two purposes. First, it provides protection. When the robot collides with the wall, it has a guard to protect the lens. Second, it also cover the top so that the camera would see only inside the track.

### Motor Bracket
It holds the motor with the lower base. This design offer us a small, effective, and strong bracket. With 3 screw holes for attaching it to the base and 2 screw holes for attaching it to motor. This part also uses the Counterbore technique.

### Gear Adapter
The gear we used was from a LEGO Technic part. Meaning that we can't attach it directly to the motor. We designed this part to place it on motor's rotating axle. Then, we added two LEGO pins to attach it to the gear.

### Buck Converter case
The buck converter comes with a lot of pin under it. This was caused by soldering. This case was made to make sure that the bottom stays flat and avoid current leakage.

### Steering Module