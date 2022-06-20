# Description:

This fan control circuit was realized with an LM317 voltage regulator. The circuit is suitable for fans that cannot be regulated via PWM (2 or 3-pin).
The maximum operating voltage is 12V. An NTC 10K 3950 (1%) with JST XH cable connector is used for temperature measurement.
The circuit board is equipped with a four-pin fan connector. If a fan with three pins is connected, the signal for the fan speed can be picked off at the free fourth pin (S. out) of the connector plug.


## Temperature setting:
Turn RV1 all the way to the right. Bring NTC to body temperature (hold with your fist), wait a little and then RV1
turn to the left until the fan starts to rotate. From the point three more half turns further.

Turn RV2 until the voltage at VAdjust is 4.7 to 4.8 volts.

With this setting method, the fan starts to run from around 36°C. As the temperature rises, the fan speed increases up to the maximum speed at around 70°C. If the temperature drops to approx. 26°C, the fan is switched off again.

## Pictures

First test setup on a breadboard
![Breadboard setup](https://github.com/DoImant/Stuff/blob/main/Analog_fan_control/lueftersteuerung-analog.jpg?raw=true)

The PCB
![PCB](https://github.com/DoImant/Stuff/blob/main/Analog_fan_control/PCB-3D-2.png?raw=true)

## circuit diagram
[circuit diagram](https://github.com/DoImant/Stuff/blob/main/Analog_fan_control/Luefter-Steuerung-Analog-V2.pdf)