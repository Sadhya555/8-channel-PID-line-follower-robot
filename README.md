# 8-channel-PID-line-follower-robot
## Components
* Arduino Nano
* 8 Channel TCRT5000 IR Array
* TB6612FNG Motor Driver
* N20 12V 300 RPM
* LM2596 Buck Converter
* 1100mah 11.1v li-po battery
* 3x 5 mm LEDs (Red, Yellow, Blue)
* 3x 220Ω resistors
* 2x Tactile Switches
* On / Off Switch (Mini) Red
* Perfboard
* Wheels
* Jumper Wires

## Wiring

| Arduino Nano Pin | IR Array | TB6612FNG | Other Components | Description |
| :--- | :--- | :--- | :--- | :--- |
| **5V** | VCC | VCC + STBY | - | Logic Power |
| **A0** | 1 | - | - | IR Sensor 1 |
| **A1** | 2 | - | - | IR Sensor 2 |
| **A2** | 3 | - | - | IR Sensor 3 |
| **A3** | 4 | - | - | IR Sensor 4 |
| **A4** | 5 | - | - | IR Sensor 5 |
| **A5** | 6 | - | - | IR Sensor 6 |
| **A6** | 7 | - | - | IR Sensor 7 |
| **A7** | 8 | - | - | IR Sensor 8 |
| **D5** | - | PWMA | - | Left Motor Speed (PWM) |
| **D6** | - | PWMB | - | Right Motor Speed (PWM) |
| **D7** | - | AIN1 | - | Left Motor Direction 1 |
| **D8** | - | AIN2 | - | Left Motor Direction 2 |
| **D9** | - | BIN1 | - | Right Motor Direction 1 |
| **D10** | - | BIN2 | - | Right Motor Direction 2 |
| **D11** | - | - | Red LED | Status Indicator |
| **D12** | - | - | Yellow LED | Status Indicator |
| **D13** | - | - | Blue LED | Status Indicator |
| **N/A** | - | A01 + A02 | Left Motor | Motor Output Connection |
| **N/A** | - | B01 + B02 | Right Motor | Motor Output Connection |
| **N/A** | - | VM | Battery Positive | Motor Power Supply |
