# FCND - Backyard Flyer Project

<p align="center">
 <a href="https://www.youtube.com/watch?v=qXo-M5-zZlY"><img src="./asset/backyardflyer.gif" alt="demo" width="50%" height="50%"></a>
 <br>Click for full video
</p>

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
