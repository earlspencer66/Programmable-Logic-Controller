## Conveyor Belt With Lamps Example



There are two push buttons I0 and I1 (both NO type) for start and stop.
There is one proximity sensor I2. There are three lamps/ indicators Q0/ RED,
Q1/ Yellow and Q2/ Green. There is a conveyor which can run in forward and
reverse direction. For forward direction Q3 should get on and for reverse Q4
should get on. When I0 is pressed, red should get on for 3 seconds. After 3
seconds red should get off and yellow should get on for 5 seconds. After 5
seconds yellow should get off and forward should get on for 6 seconds. After
6 seconds forward will be off and reverse should get on for seven seconds.
After seven seconds, repeat the process. I2 sensor must be on to run the
machine. If I2 is off and I0 is pressed then machine won’t start. When
machine runs and in between the process i2 sensor gets off then machine
will stop. Whenever conveyor runs either in forward or in reverse direction,
green should be on. I1 is for emergency stop.


## **List of My Inputs and Outputs based on the LOGO! Software**

### **Inputs**

I1 - Start

I2 - Stop/Emergency

I3 - Proximity Sensor

### ***Outputs**

Q1 - RED

Q2 - YELLOW

Q3 - GREEN

Q4 - CONVCEYOR FORWARD

Q5 - CONVEYOR BACKWARD
