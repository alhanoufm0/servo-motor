# servo-motor

#include <Servo.h>
Servo moto; //any name should do void setup(){
moto .attach(7);
}
void loop(){
moto .write(0); delay(1000); moto .write(120);
delay(2000); }
