# BatNAV-Project
Navigation device made for the visually impaired.
Idea: Our friend Moksh who has 100% visual impairment always needs someone to be there to guide him around wherever he walks. He also finds it awkward to use his walking cane in public spaces, hence we decided to work on a smart and less apparent solution to walking cane to help with his problem. 

Problem statement: To come up with a smart, inconspicuous device that helps people with visual impairment navigate their surroundings by themselves. 

SDG in focus: Reduced inequalities (10) 


Constraints: 
Should be inconspicuous 
Lightweight and portable
He should be able to use the device himself 
Should be as accurate as possible and avoid misleading him

Idea Brainstorm: 





Final Solution:
This device is intended to be a replacement for the white cane used by the blind. It uses an ultrasonic sensor, a pair of vibrational motors, an arduino nano, a gyroscope, and a custom designed PCB, encased in a box-like housing, which has an elastic strap and is to be worn on the shoes. When an obstacle or person lies within the field of view of the ultrasonic sensor, the motors vibrate with different pre-programmed intensities to notify the user how close he/she is to that obstacle. The logo of a bat was used on this product to make it more user-friendly and more of an accessory rather than a product that highlights the disability of the user. 


Name:  Bat NAV


Final Sketch:





Prototype Images: 




Final Product:





Design Process: 
1st we decided who to make the product for
We then brainstormed what are the possible solutions for the problem 
We then paper prototyped one possible prototype
After this we spoke to our user to better understand his problem 
Next we changed our problem statement to better suit the issue our friend had. 
We figured out which components to use 
Furthermore, we began to design prototypes out of sunboard and cardboard and then acrylic
After doing so, we worked on the code and tested it out
We made the circuit diagram and soldered all the different components onto a zero PCB board 



Source Files:

Google Drive Link for Source Files: https://drive.google.com/drive/u/0/folders/1KdH22gnNis6PnZ0HNDW6FM2nzU6maH6L

Screenshots:

Programming:





CAD and  3D Model for housing:




Components used:
1 Arduino Nano 
1 Ultrasonic Sensor HC-SR04
1 MPU6050 Gyroscope/Accelerometer
Header Pins
Zero PCB Board 
1 9V connector 
2 Vibration motors KG-160

Materials used: 
Acrylic Sheets
Sunboard (for prototyping)
Cardboard (for prototyping) 

Tools used:
 Laser Cutter
X-acto blade
Zero PCB Board 
Skills Used:
CAD
Electronics 
Design Thinking 
Prototyping 
Circuit Design 
Soldering
Programming 

Challenges Faced and Solutions:
The first challenge we faced was that we were unsure about whether or not our user would find the initial product useful, we overcame this by speaking to our user and understanding from him what he wants there to be in the product

Our second challenge was that the ultrasonic sensor was placed too high on the foot to give an accurate detection result. We then changed our design to fit the product in a better position on the foot. We achieved this by having a show strap design.

Our Third Challenge was that the ultrasonic sensor would detect the ground in the ankle bending phase of the walking motion, this caused the motor to vibrate and mislead the user. To combat this challenge we decided to include a Gyroscope in the circuit so it could cut off supply to the motor if the foot bends beyond a certain angle 

Our fourth challenge came up when we had connected a 3V power source to the circuit but soon realized that it wasn’t enough to power the circuit. We overcame this by replacing the 3V socket with a 9V one. 
