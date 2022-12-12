#include <ESP8266WiFi.h>

const int trigPin = D3;

const int echoPin = D4;

long duration;

int distanceCm,distanceInch;

void setup()

{ 



 Serial.begin(9600); 

 pinMode(trigPin, OUTPUT);

 pinMode(echoPin, INPUT);



 pinMode(D5, OUTPUT); // Connect LED Pin D0

 pinMode(D0, OUTPUT); // Connect Buzzer Pin D2



}

void loop()

{

digitalWrite(trigPin, LOW);

delayMicroseconds(2);

digitalWrite(trigPin, HIGH);

delayMicroseconds(10);

digitalWrite(trigPin, LOW);

duration = pulseIn(echoPin, HIGH);

distanceCm = duration*0.034/2;

Serial.println("Distance: ");

Serial.println(distanceCm);

delay (1000);

// See the Ultrasonic Sensor Value in Serial Monitor



if(distanceCm < 70) // You can Change the value 

{



  digitalWrite(D5, HIGH); // Buzzer ON

  digitalWrite(D0, HIGH); // LED ON



}



else

{

    digitalWrite(D5,LOW); // Buzzer OFF

    digitalWrite(D0,LOW); // LED OFF 

}

}

