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
The lower base serves as the foundation of our robot, supporting nearly all essential components: the controller, motors, steering servo, light sensors, buck converter, and differential.  
 
When designing this part, precise measurements were critical to ensure a proper fit for each component. In our robot, we uses a **LEGO TECHNIC** parts like axle, differential, and gear to ensure that those part would not break during our section.

To secure the LEGO axle, we designed support poles at the back of the base to hold it firmly in place. With this design, it allows the robot to reach it's full potential.

### Upper Base.

The upper base is positioned 3 cm above the lower base and is designed to hold the remaining components while providing additional stability to the robot.  

To ensure a clean and seamless build, we applied the **counterbore technique** so that screws do not interfere with the lower section. This approach allowed us to hide the screws neatly, giving the chassis a screwless apperance.  

Additionally, the upper base includes a **battery slot** at the back, ensuring secure placement and easy accessibility during operation.  

### LiDAR Holder

The LiDAR holder is mounted on top of the upper base to keep the LiDAR elevated above other components. This prevents the sensor from mistakenly detecting parts of the robot itself.  

The holder also included a **slot for the gyro sensor**, positioned directly beneath the LiDAR. This compact arrangement minimizes the overall robot size while ensuring that the LiDAR remains within the **10 cm height limit** to avoid detecting over the wall.  

### Camera mount

This component serves as a **stand for the camera** and includes protective covers for both the front and top.  

The design serves two key purposes:  
1. **Protection** – In case of collisions with walls, the front cover acts as a guard to protect the camera lens from damage.  
2. **Vision Control** – The top cover blocks external light and distractions, ensuring the camera only captures the track area.  

This combination enhances both the durability and reliability of the vision system during section.  

### Motor Bracket
It holds the motor with the lower base. This design offer us a small, effective, and strong bracket. With 3 screw holes for attaching it to the base and 2 screw holes for attaching it to motor. This part also uses the Counterbore technique.

### Gear Adapter
The gear we used was from **LEGO Technic**. Meaning that we can't attach it directly to the motor. We designed this part to place it on motor's rotating axle. Then, we added two LEGO pins to attach it to the gear.

### Buck Converter case
The buck converter comes with a lot of pin under it. This was caused by soldering. This case was made to make sure that the bottom stays flat and avoid current leakage.

### Steering Module