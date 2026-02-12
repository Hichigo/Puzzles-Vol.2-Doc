# BP\_Puzzle\_5

## Settings

### Cylinders

* **SizeX (integer):** number of cells in X
* **SizeY (integer):** number of cells in Y
* **SizeCell (float):** cell size (can be seen in **SM\_CrossPipe**)
* **CurrentShapeCells (S\_PathCell):** the structure contains information about which cell the figure is in and what is its rotation angle (for setting up [**Editor Utility Widget**](editor-widget-utility.md)**)**
* **WinStateCells (S\_PathCell):** the structure contains information on how to change **CurrentShapeCells** to solve the puzzle (for setting up [**Editor Utility Widget**](editor-widget-utility.md))
* **bRandomizeAllCells (bool):** set random shapes with random state in each cell
* **bRandomizeStateCells (bool):** randomly rotates all shapes except the empty, start, end and cross _(to update the state of the cells in the viewport, you need to move the puzzle)_

### Sound

* **WinSound (Base Sound):** puzzle solving sound

### Debug

* **bDebug (bool):** shows cell indices



