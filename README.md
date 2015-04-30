# Wearable Measurement Device
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
d)LCD connections:
      1)LCD pin 1: Gnd
      2)LCD pin 2:VCC
      3)LCD pin 3:Gnd
      4)LCD pin 4:Gnd
      5)LCD pin 5:Arduino pin 12
      6)LCD pin 6:Arduino pin 11
      7)LCD pin 11:Arduino pin 5
      8)LCD pin 12:Arduino pin 4
      9)LCD pin 13:Arduino pin 3
      10)LCD pin 14:Arduino pin 2
      11)LCD pin 15:Vcc
      12)LCD pin 16:Gnd
