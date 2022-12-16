# DIY-muscle-EMG-sensor

This is the enhanced version of the previous sensor design. This design suppresses the unwanted DC offset coming from the body and amplifies only the desired AC muscle signals without the opamp saturation at the beginning of the circuit. 

In general it consists of 4 stages: pre-amplification, highpass, lowpass filtering, and final amplification, as shown in figure below:
![image](https://user-images.githubusercontent.com/111345810/208087817-2128adbb-f505-4066-86ea-71def9da0cba.png)

The inputed to the circuit differential muscle signals look like this:
![image](https://user-images.githubusercontent.com/111345810/208087904-44811cfe-e894-4426-992d-3f0ac58a744b.png)

The output from the circuit directed to the Arduino board looks like this:
![image](https://user-images.githubusercontent.com/111345810/208087998-ba622e51-3941-417a-a79f-e43ae79bde29.png)

Please, see the presentation to get a better idea.

Good luck in assembling this circuit for your projects!
