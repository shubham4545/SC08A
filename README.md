# SC08A
 
                         SC08A
                                                        
SC08A is designed to control 8 independent standard RC (Remote Control) servo motors simultaneously in a single board. Each servo signal pin is able to generate servo pulses from 0.5 ms to 2.5 ms, which is greater than the range of most servos, further allows for servos to operate 180 degrees. SC08A comes with small size and different protocol compare to SC16A.Through serial communication, SC08A can be daisy chain in 2 boards to offer independent control over 16 RC servo motors simultaneously. The host of SC08A can either be a PC desktop/Laptop with USB to serial(UART) converter, or microcontroller with UART interface. 
 SPECIFICATIONS:  
• 8 channels: Servo driven independently 
 • Extendable to 16 Channels: Two controller linked together to drive 16 servos  
• Optional Position Reporting: User may request position of an individual servo. 
 • Servo Activation for each channel: User may deactivate or activate any channel of servo. 
 • Independent Starting Position Command for each channel: User may set the initial position of any channel at the next start-up. 
 • Optional Servo Ramping: Choose one of 100 ramp rate for each servo.  
• Resolution: 8000 steps = 0.25us. • UART: 9600 baud rate  
• Servo pulse range: 0.5ms to 2.5ms. 
 
 
Connecting SC08A to Microcontroller 
Another concern of user is for embedded system to control servo motors. For microcontroller 
to interface with SC08A, the minimum requirement will be TTL UART (Universal 
Asynchronous Receiver and Transmitter) and 5V supply. 5V will not be an issue since most 
of embedded or microcontroller system is 5V powered, tapping the 5V from host system will 
be reasonably easy. As for UART, a minimum of Transmit pin is required to send command 
to SC08A. 
 
 
 
 
 
 
 
 
