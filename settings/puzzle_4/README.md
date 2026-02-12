# BP\_Puzzle\_4

## Settings

* **bDefaultColors (bool):** set default colors, each color in its own column (red, green, blue, cyan)
* **bRandomizeColors (bool):** shuffle colors

### Cylinders

* **AmountCylinders (integer):** the number of cylinders in the puzzle, the topmost one does not count
* **Cylinders (S\_Cylinders):** structure with data for the puzzle, contains the current positions of colors, references to ShpereMeshComponent, references to cylinders and the state that needs to be collected to solve the puzzle (for setting [**Editor Utility Widget**](editor-widget-utility.md))

### Mesh

* **TopCylinder (Static Mesh):** static mesh of the top cylinder
* **MiddleCylinder (Static Mesh):** static grid of middle cylinders
* **BottomCylinder (Static Mesh):** bottom cylinder static mesh

### Sound

* **RotateCylinderSound (Base Sound):** cylinder rotation sound
* **MoveSpheresSound (Base Sound):** sound of moving spheres
* **WinSound (Base Sound):** puzzle solving sound

