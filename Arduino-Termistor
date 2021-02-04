#include <Thermistor.h>

Thermistor temp(1); // pin analogico donde esta la sonda

void setup() {
  Serial.begin(9600);
  delay(1000);

}

void loop() {
 int temperature = temp.getTemp(); //comando para obtener la medicion de temperatura
 Serial.print("temperatura: ");
 Serial.print(temperature);
 Serial.println(" °C");
 delay(1000);
}
