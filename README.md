#include <iostream>
int pin;
int val;
void setup(){
Serial.begin(9600); // вывод данных
};

void loop(){
     pin = pin;
     val = digitalRead(pin);
     Serial.print("Data | ");
     Serial.println(val);
     Serial.print("Pin | ");
     Serial.println(pin);
}
