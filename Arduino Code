#include <Servo.h> 
Servo myservo1;
Servo myservo2;
Servo myservo3;
Servo myservo4;
Servo myservo5;
const int threshValue = 250;
void setup() 
{ 
  myservo1.attach(3);
  myservo2.attach(5);
  myservo3.attach(6);
  myservo4.attach(9);
  myservo5.attach(10);
} 

void loop() 
{ 
  int value = analogRead(A3);

  if(value < threshValue)        
  { 
            myservo1.writeMicroseconds(700);
            myservo2.writeMicroseconds(700);
            myservo3.writeMicroseconds(700);
            myservo4.writeMicroseconds(700);
            myservo5.writeMicroseconds(700);  
  }
  else 
  { 
            myservo1.writeMicroseconds(2000);
            myservo2.writeMicroseconds(2000);
            myservo3.writeMicroseconds(2000);
            myservo4.writeMicroseconds(2000);
            myservo5.writeMicroseconds(2000);
  } 
}
