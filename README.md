Skateboarduino
==============
This code is for my speedometer on my skateboard controlled by my Arduino. It reads the speed using a reedswitch and then uses the speed to change the color of the 16 common anode RGB leds underneath the board.
The RGB leds are multiplexed by having each color's cathode wired togehter and controlled by 3 separate PWM pins. The common anodes are each seaprately controlled by transistors which are controlled by 2 shift registers.
