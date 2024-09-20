# Unity Robot Simulator

## Code Path
C:\Users\great\Documents\robot_sim\Assets\Scripts

## Google Drive Path
https://drive.google.com/drive/folders/18z7QR8nYxGLI1d0tfybX3XjvngwCus4i?usp=drive_link

## Purpose

The purpose of this program is to simulate a virtual environment for an agricultural robot, who's data in the simulation can be used for training in machine learning.

## How to Use

After starting the simulation, enter the longitude and latitude of the place you would like to simulate. A 3D terrain will be generated. After the rover has settled, you can press p to enter plot mode to place plants. Once the plants are placed, the rover will automatically move to the plant waypoints, and attempt to kill the weeds with its UV light along the plot.

### Plot Mode

You can use the arrow keys to move the camera around. Before placing any plots, set the row density, column density, and weed density to desired values (row and column density must be more than zero for any plants to be placed). You can also select soybean or strawberries. Once these settings are set, left click and drag across an area to place a plot. You can place multiple plots. Once finished, press enter and the plants will be placed in those plots.

### Camera

While there is always a mini-view of the rover's camera in the upper right corner, pressing NUMPAD 0 will switch the view to be larger.

### Recording

Once you have the rover set up and working, press NUMPAD 5 to start recording. This will record a snapshot of the rover's camera, as well as information about the rover (forward movement, turn movement, lat, lng, heading, etc.). The recording is saved in Assets/Recordings/<date of recording>

## Code/Programming

Read "code documentation.md"
