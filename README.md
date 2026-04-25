# Arduino LED Blinking Project

## 📌 Objective
To control an LED using Arduino UNO and make it blink at regular intervals.

## 🔧 Components Used
- Arduino UNO
- LED
- Resistor (220 ohm)
- Breadboard
- Jumper wires

## 🔌 Circuit Connection
- Connect LED positive leg to digital pin 13 through resistor
- Connect LED negative leg to GND

## 💻 Code
```cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
