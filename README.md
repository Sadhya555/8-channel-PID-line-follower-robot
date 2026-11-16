# 8-channel-PID-line-follower-robot
## Components
* Arduino Nano
* 8 Channel TCRT5000 IR Array
* TB6612FNG Motor Driver
* N20 12V 300 RPM
* LM2596 Buck Converter
* 1100mah 11.1v li-po battery
* 3x 5 mm LEDs (Red, Yellow, Green)
* 3x 220Ω resistors
* Tactile Switch
* On / Off Switch (Mini) Red
* Perfboard
* Wheels
* Jumper Wires

## Wiring

| Arduino Nano Pin | IR Array | TB6612FNG | Other Components | Description |
| :--- | :--- | :--- | :--- | :--- |
| **5V** | VCC | VCC + STBY | - | Logic Power |
| **A0** | A0 | - | - | IR Sensor 1 |
| **A1** | A1 | - | - | IR Sensor 2 |
| **A2** | A2 | - | - | IR Sensor 3 |
| **A3** | A3 | - | - | IR Sensor 4 |
| **A4** | A4 | - | - | IR Sensor 5 |
| **A5** | A5 | - | - | IR Sensor 6 |
| **A6** | A6 | - | - | IR Sensor 7 |
| **A7** | A7 | - | - | IR Sensor 8 |
| **D3** | - | - | Tactile Switch | Run/Calibrate |
| **D5** | - | PWMA | - | Left Motor Speed (PWM) |
| **D6** | - | PWMB | - | Right Motor Speed (PWM) |
| **D7** | - | AIN1 | - | Left Motor Direction 1 |
| **D8** | - | AIN2 | - | Left Motor Direction 2 |
| **D9** | - | BIN1 | - | Right Motor Direction 1 |
| **D10** | - | BIN2 | - | Right Motor Direction 2 |
| **D11** | - | - | Red LED | Status Indicator |
| **D12** | - | - | Yellow LED | Status Indicator |
| **D13** | - | - | Green LED | Status Indicator |
| **N/A** | - | A01 + A02 | Left Motor | Motor Output Connection |
| **N/A** | - | B01 + B02 | Right Motor | Motor Output Connection |
| **N/A** | - | VM | Battery Positive | Motor Power Supply |
