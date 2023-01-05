

<h2>

 Introduction 

</h2>



Finding their way on the streets is one of the many difficulties that blind people face in life. There are a lot of vehicles and obstacles on the street that could get in their way and hurt them. So, keeping this issue in mind, we created a Smart blind stick that uses an ultrasonic sensor to look for obstacles in front of it. We make use of a NodeMCU board and an ultrasonic sensor called the HC-SR04. Complete the circuit then, at that point, transfer the given code to the NodeMCU.







# Hardware Specification

1. NodeMCU<br>

3. HC-SR04 Ultrasonic Sensor<br>

4. Buzzer<br>

5. Jumper Wires<br> 

6. Power Supply<br>





# Software Specification

1.	Arduino IDE<br>



# Block Diagram:



![blind stick](https://raw.githubusercontent.com/SaiHari-N/Ultrasonic-based-Blind-Stick-using-NodeMCU-/main/Project%20files/Ultrasonic%20based%20Blind%20Stick%20using%20NodeMCU.jpg)







# Working Principle:

Using an HC-SR04 ultrasonic sensor, the Smart Blind Stick scans the path in front of it. Whenever the sensor identifies any item in its way the ringer begins blaring and furthermore simultaneously the Drove turns on. The blind person is able to change the direction after hearing the buzzer beep. The individual will be able to find his way around without getting hurt in this manner. The Ultrasonic range finder’s functions are identical to those of this smart stick. On the Arduino serial monitor, we can also see the distance’s real-time values in cm. Use zip ties to secure the entire setup to a stick.





# Connectivity Configuration:

Connect the ultrasonic sensor’s TRIG and ECHO pins to the NodeMCU’s digital-3 and digital-4 pins. Connect the buzzer’s positive and negative wires to the NodeMCU’s digital-5 and GND pins as well as LED is connected to 3.3V and GND. Presently open the chronic screen to peruse the sensor esteem.



# Prototype:

 ![Prototype]( https://raw.githubusercontent.com/SaiHari-N/Ultrasonic-based-Blind-Stick-using-NodeMCU-/main/Project%20files/Top%20and%20front%20view.jpg)


