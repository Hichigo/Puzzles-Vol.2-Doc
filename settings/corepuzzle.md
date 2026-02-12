# BP\_CorePuzzle

It creates a puzzle interface, sets up the cursor control through the gamepad, and functions for starting control and ending control of the puzzle.

Also, an **OnWin\_Disp** puzzle solving event has been created for which you can subscribe from outside (for example, to achieve an achievement, open a secret door, or any other action).

## Settings

* **SpeedCursorGamepad** (float): cursor movement speed when controlling a gamepad

### **Camera**

* **LengthSpringArm** (float): distance from camera to puzzle
* **SpringArmRotation** (Rotator): camera rotation around the puzzle

### **UI**

* **UIClass** (User Widget Class): interface with tips
