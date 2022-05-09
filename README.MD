# AC Programming with Micro-controllers

# Smart-AC-System
A smart Air Conditioner system able to adjust the power based on the enviornment's temperature and air pressure.

The project is an intelligient Air Conditioner adjuster using Arduino as its hardward base.
It makes the AC adjust the power of its motors according to the environment's temperature and atmosphere pressure.

## Sensor types:

Temperature ----------- DS18B20 <br />
Atmosphere pressure --- analog sensor <br />

## Output types: <br />
### Digital Potentiometer-- X9C102P, X9C104P <br />
### Capacitive Touchable Screen - RA8875(800 x 480) from Buydisplay.com <br />
### State Machine fields: <br />
### STATE: STDB --- to turn off the power <br />
       AUTO --- to run automatically <br />
       MANM --- to allow manual adjust of SP and DP3 <br />
       VENT --- to allow manual adjust of DP3 <br />
       TEST --- to allow manual adjust of all sensors and outputs, meanwhile suspend the auto update function <br />
### SP: a set_point as the formula's coefficient <br />
 <br />
 
### Display System <br />
One button for each state. Press the button to swtitch to the state.
Several groups of toggles for certain states. One group of toggles show only when the state they belong to is on. <br />
Input Field at the left bottom corner keeps showing the update sensor value. <br />
Warning Field at the right bottom corner shows the abnormal evaluation only when there is such a condition. <br />
It saves the data to SD card every second. <br />

TODOs: <br />
1.More OOP about the STATE system? <br />

P.S. It takes two months and 6 versions to get the project to this stage, althoug I know the code stilllooks redundant. <br />
Please don't hesitate to let me know how I could optimize it. Thank you! <br />
 <br />

