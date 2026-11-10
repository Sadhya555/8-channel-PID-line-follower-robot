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
  <tr>
    <th>Nano - Array</th>
    <th>Nano - TB6612FNG</th>
    <th>Other</th>
  </tr>
  <tr>
    <td valign="top">
      <table>
        <tr><th>Arduino Nano Pin</th><th>IR Array</th></tr>
        <tr><td><b>5V</b></td><td>VCC</td></tr>
        <tr><td><b>A0</b></td><td>1</td></tr>
        <tr><td><b>A1</b></td><td>2</td></tr>
        <tr><td><b>A2</b></td><td>3</td></tr>
        <tr><td><b>A3</b></td><td>4</td></tr>
        <tr><td><b>A4</b></td><td>5</td></tr>
        <tr><td><b>A5</b></td><td>6</td></tr>
        <tr><td><b>A6</b></td><td>7</td></tr>
        <tr><td><b>A7</b></td><td>8</td></tr>
      </table>
    </td>
    <td valign="top">
      <table>
        <tr><th>Arduino Nano Pin</th><th>TB6612FNG</th></tr>
        <tr><td><b>5V</b></td><td>VCC + STBY</td></tr>
        <tr><td><b>D5</b></td><td>PWMA</td></tr>
        <tr><td><b>D6</b></td><td>PWMB</td></tr>
        <tr><td><b>D7</b></td><td>AIN1</td></tr>
        <tr><td><b>D8</b></td><td>AIN2</td></tr>
        <tr><td><b>D9</b></td><td>BIN1</td></tr>
        <tr><td><b>D10</b></td><td>BIN2</td></tr>
      </table>
    </td>
    <td valign="top">
      <table>
        <tr><th>TB6612FNG</th><th>N20 Motors</th><th>Battery</th></tr>
        <tr><td><b>A01 + A02</b></td><td>Left Motor</td><td></td></tr>
        <tr><td><b>B01 + B02</b></td><td>Right Motor</td><td></td></tr>
        <tr><td><b>VM</b></td><td></td><td>Positive</td></tr>
      </table>
      <br>
      <table>
        <tr><th>Arduino Nano</th><th>LED</th></tr>
        <tr><td><b>D11</b></td><td>Red LED</td></tr>
        <tr><td><b>D12</b></td><td>Yellow LED</td></tr>
        <tr><td><b>D13</b></td><td>Blue LED</td></tr>
      </table>
    </td>
  </tr>
</table>
