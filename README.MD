# ECE 534 Electric Drives

UW ECE 534 Electric Drives Project
schematics and layout.

## Description

* A boost converter boosts a 24V input voltage to 48V. 
* An inverter receives this filtered 48V from the boost converter to generate three sinusoidal voltage waveforms.
* The output currents feed a BLDC motor.
* With C2000 piccolo launchpad 4 PI controllers are implemented to control the entire system:
* Current control and voltage control for the boost converter and current and speed control for the BLDC motor. 

## Authors

* Nakseung Choi (UW ECE Graduate Research Assistant) https://www.linkedin.com/in/nakseung-choi-090a1b69/
* Cody Birkland (UW ECE MS student, Ultropia)

## Release Notes

<pre>Final release                     06-25-2022</pre>

## License

This project is licensed under Nakseung Choi and Cody Birkland - see the LICENSE.md file for details
