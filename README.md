# smart-glasses-visually-impaired
# Smart Glasses for Visually Impaired

A wearable obstacle detection device built with Arduino UNO and ultrasonic sensor to help visually impaired individuals navigate safely.

## How it works
- HC-SR04 ultrasonic sensor measures distance to nearby objects
- Arduino UNO processes the sensor reading
- Buzzer gives audio alert when obstacle is detected within 50 cm
- Beeping frequency increases as obstacle gets closer

## Components used
| Component | Purpose |
|---|---|
| Arduino UNO | Main microcontroller |
| HC-SR04 Ultrasonic Sensor | Obstacle detection |
| Buzzer | Audio alert |
| 9V Battery | Power supply |
| Jumper wires | Connections |

## Circuit connections
- TRIG pin → Digital Pin 9 on Arduino
- ECHO pin → Digital Pin 10 on Arduino  
- Buzzer → Digital Pin 8 on Arduino
- VCC → 5V, GND → GND

## How to run
1. Open `smart_glasses.ino` in Arduino IDE
2. Connect Arduino UNO via USB
3. Select board: Tools → Board → Arduino UNO
4. Upload the code
5. Open Serial Monitor (9600 baud) to see distance readings

## Future improvements
- Add GPS for outdoor navigation
- Text-to-speech using Raspberry Pi
- Mobile app via Bluetooth
- AI-based object recognition

## Project context
Built as part of Project Based Learning (UE24CS2306) — BE Computer Science (Information Security)
