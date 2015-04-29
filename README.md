# TheHumanTape
This project aims at making a wearable device that measures dimentions using ultrasonic sensor. I have also used piezoelectric pressure sensors to trigger 2D or 3D modes which are used to identify the shape of the object and help in calculating the survace area and volume.
The final sourcecode is an arduino code that has to be uploaded on an arduino with attached lcd, ultrasonic and piezoelectric sensor that work as pressure triggers.
->One piezoelectric sensor will trigger the 2D mode. This mode takes at max 2 dimentions. To give only one input we exit after giving one dimention by pressing the 2D trigger again.The display will show the shape and its area.
    i)1 dimention: Circle
    ii)2 dimentions: Square or rectangle
->The other sensor will trigger the 3D mode. This mode takes at max 3 dimentions. We exit by pressing the 3D trigger again. The display will show the shape name and its total surface area and volume.
    i)1 dimention: Sphere
    ii)2 dimentions: Cylinder
    iii)3 dimentions: Cube, Cuboid
Arduino board connections:
a)PiezoElectric sensor(2D):Arduino pin A2, Gnd
b)PiezoElectric sensor(3D):Arduino pin A1, Gnd
c)Ultrasonic sensor:
      1)Trigger: Arduino pin 7
      2)Echo: Arduino pin 8
