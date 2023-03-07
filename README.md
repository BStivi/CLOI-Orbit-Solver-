# CLOI-Orbit-Solver-
This Python script utilizes Rebound to predict the orbits of Cis-Lunar Objects of Interest (CLOI).
The Script takes in the TLE of a particular Object and gets Epoch time, orbital positions, etc. 
Using this data, the initial conditions of the simulation (position of Sun, Moon, Earth, and CLOI) are established.
From here, the orbit of the CLOI is simulated for a set amount of time, with semi major axis, eccentricity, and inclination tracked and plotted.

The following libraries are required to run the code. (Satelite Orbits)
1) rebound
2) numpy 
3) matplotlib.pyplot

This code was run on an Intel-Based Macbook. I have not tested it on other formats 

