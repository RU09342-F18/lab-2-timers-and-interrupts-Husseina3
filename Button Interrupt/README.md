# Button Interrupt
For this part of the lab the MSP430G22553 and MSP430FR2311 microprocessors were used. 
On the previous project a Polling method was used to detect a button press, where the 
processor constantly checks if a button is pressed or not every time. Since our objective is 
to run the microprosessor on Low Power Mode, we want the processor to go to sleep unless 
there is an event to be executed. 

# A little bit about Interrupts
Interrupts play a major role in making our computer systems fast, efficient and less power consuming. 
Instead of the processor checking for events, interrupts alarm and interrupt the processor from its idle state
or whatever state.

|Term|Description|
|----|------------|
