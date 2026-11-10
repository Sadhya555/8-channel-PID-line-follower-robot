# 8-channel-PID-line-follower-robot
## Components
* Arduino Nano
* 8 Channel TCRT5000 IR Array
* TB6612FNG Motor Driver
* N20 12V 300 RPM
* LM2596 Buck Converter
* 2x 18650 3.7V NCR18650BD Batteries
* 2 Cell Battery Holder
* 3x 5 mm LEDs (Red, Yellow, Blue)
* 3x 220Ω resistors
* 2x Tactile Switches
* On / Off Switch (Mini) Red
* Perfboard
* Wheels
* Jumper Wires

## Wiring
<table>
<tr><th> Nano - Array </th><th>Nano - TB6612FNG</th></tr>
<tr><td>

| Arduino Nano Pin | IR Array |
| :--- | :--- | 
| **5V** | VCC |
| **A0** | 1 |
| **A1** | 2 |
| **A2** | 3 |
| **A3** | 4 |
| **A4** | 5 |
| **A5** | 6 |
| **A6** | 7 |
| **A7** | 8 |

</td><td>

| Arduino Nano Pin | TB6612FNG |
| :--- | :--- | 
| **5V** | VCC + STBY |
| **D5** | PWMA |
| **D6** | PWMB |
| **D7** | AIN1 |
| **D8** | AIN2 |
| **D9** | BIN1 |
| **D10** | BIN2 |

</td></tr> </table>
