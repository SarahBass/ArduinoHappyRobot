# ArduinoHappyRobot
An Arduino Robot hooked up to a Raspberry Pi that interacts with environment

'''Python, C, and C++. 

'''Raspberry Pi 4 and Arduino Mega 


Physical Design
-------------------------------------------------------------------------------------------------------------------------------

Robot base purchased on Amazon at this link: [Wooden Robot Puzzle](https://www.amazon.com/ROKR-Machinarium-Figures-Christmas-Birthday/dp/B0797K1Q9D/ref=asc_df_B0797K1Q9D/?tag=hyprod-20&linkCode=df0&hvadid=241997379068&hvpos=&hvnetw=g&hvrand=17699836542645489671&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031523&hvtargid=pla-427826511810&psc=1)

Instead of using a 3d printer, I used this lazer cut wood puzzle as the base of my robot body. I saved the original music box, led light, and other gears and used it as an empty shell to hide my wires, breadboard, and other components inside. I wrapped the claw hand fingers with wires like a puppet and attached the wire strings to servos inside the box shaped robot body which pull the claw, forearm, and shoulder. I did the same with the foot , leg, and hip. Additionally , I added an ultrasonic sensor for "eyes" , an RGB LED light, and a DC motor to spin the gears.

-------------------------------------------------------------------------------------------------------------------------------

COMPONENTS | USAGE
----------- | ------------
1* LED RGB  | Light shown from heart
3* Servo Motor | Two for arms, one for legs
1* DC Motor | Spin gears and head fan
1* HC-SR04 UltraSonic Sensor | Motion sensing distance
1* PIR Motion Sensor | Motion sensing target
1* Mini Breadboard | Efficieny and testing without solder
1* Mega Arduino Board and USB | Run multiple components 
1* Complete Canakit Raspberry Pi 4 | Powersource and Linux Computer

Code Design
-------------------------------------------------------------------------------------------------------------------------------

Arduino (c/c++) to Raspberry Pi (python) communication through USB

Arduino Robot lights up when hashtags are trending on Instagram or Twitter:

#christmas - red and green
#halloween - orange and purple
#usa - red, white, blue
#stpatricksday - green
#hannukah - blue, white, and yellow
#easter - pink, cyan and yellow
#cincodemayo - Crayola, green, white, and red
#newyear - white and blue
#chinesenewyear - red, yellow, and white
#thanksgiving - red, yellow, brown
#pride - full spectrum
((And more)) 

Waves hello when object is detected moving

Kicks feet when object gets closer, increases feet kicking speed

Tries to grab item with claws when item is closest in range

Spins gears on top 












