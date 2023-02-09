# logisim-trafficLights
Reproduction of a road crossing, regulated by traffic lights.
Made with [Logisim evolution software](https://github.com/logisim-evolution/logisim-evolution).
## Description
This project has as its objective, the representation of an intersection 
traffic lights controlled by hypothetical cameras to detect the passage of the car with the 
red light, with the possibility of seeing the vehicle's licence plate number and the time at which the infraction occurred.<br /> 
In the project there is a map representing a four-way intersection, with the 
traffic lights corresponding to the road, below it are the pedestrian traffic lights. <br />
For each traffic light there is a button that if pressed when the light is red, will trigger a fine.<br /> 
When an infringement occurs, the fine counter is incremented and the number plate of the 
vehicle with the time at which it occurred. <br />
To show this, there are three rows of displays showing the latest fined number plates with the relevant
times. <br />
The design also includes a clock with two buttons for setting the hours and 
minutes and a possible reset.
## Premise
The contravention cameras are represented by buttons, so pressing one of them indicates a car passed at that given moment.<br />
Since there was no way to photograph a real plate, the circuit generates a pseudo-random plate consisting of 7 alpha-numeric characters.
## Usage
Open the project and set the desired time using the M+ (minutes) and H+ (hours) buttons, in case of necessary press R (reset).
Start a clock with a frequency of 16HZ via the "Simulation" drop-down menu.<br />
Once this is done, the traffic lights will start up and autonomously start their motion.<br />
Now if you try to press a reference button at a red traffic light you will see the increase of the fine counter, and the filling of the first line of the table indicating the number plates and the times.
