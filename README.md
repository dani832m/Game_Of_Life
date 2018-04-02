##Game of Life

Game of Life is played on a grid of square cells - like a chess board but extending infinitely in every direction. A cell can be _**live**_ or _**dead**_.

* A live cell is shown by putting a marker on its square.
* A dead cell is shown by leaving the square empty.
* Each cell in the grid has a neighbourhood consisting of the eight cells in every direction including diagonals.
* To apply one step of the rules, we count the number of live neighbours for each cell. What happens next depends on this number.
* A dead cell with exactly three live neighbours becomes a live cell (birth).
* A live cell with two or three live neighbours stays alive (survival).
* In all other cases, a cell dies or remains dead (overcrowding or loneliness). 

**Note:** The number of live neighbours is always based on the cells _before_ the rule was applied. In other words, we must first find all of the cells that change before changing any of them.