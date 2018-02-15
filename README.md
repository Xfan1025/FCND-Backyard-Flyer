# FCND - Backyard Flyer Project
In this project, you'll set up a state machine using event-driven programming to autonomously flying a drone. You will be using flying a quadcopter in Unity simulator. After completing this assignment, you'll be familiar with sending commands and receiving incoming data from the drone.

The python code you write is similar to how the drone would be controlled from a ground station computer or an onboard flight computer. Since communication with the drone is done using MAVLink, you will be able to use your code to control an PX4 quadcopter autopilot with very little modification!

# Usage
After starting the simulator, cd into the project directory.

```sh
python backyard_flyer.py [--plan s] [--size 10] [--height 3]
```
Optional Arguments:
  * plan: s for square, t for triangle. (Default s)
  * size: integer for size of the flying plan edge. (Default 10)
  * height: integer for how high the drone should fly to. (Default 3)

Example:
```sh
python backyard_flyer.py --plan t --size 10 --height 5
```
