# Programacion-Web-20095528-Tarea4
Web Programming

Today's Agenda (2/6/2017)

Exercises

In the previous class, there was

Modify your random.html document. Update the code so it ignores keyboard input (for now).
Add a function called createSnake
Add code to generate a random point within the grid (you should use x, y coordinates for this)
Set the active class to the randomly generated cell within the grid.
Add a function called createTail
It should take the following parameters: head, dir, numCells
The head parameter is a reference to the randomly selected cell (within createSnake)
The direction parameter is a normalized value on the X or Y axis (values can be -1 or 1). Ideally this should be an object (use {} notation), but if you're not comfortable with this notation use an array of two elements were position 0 represents the X component and 1 represents the Y component.
The numCells parameter represents the length of the snake's body. It determines how many cells in a given direction are going to be active besides the head.
Call the createTail function from within the createSnake function.
The expected output should be N amount of active cells within a given direction.
Add a move function.
The move function should move the snake's head and tail at a given velocity. It's value for this excercise should be [0, 1].
Hint: You should store the snake into a data structure and loop around it, on every loop cycle you should calculate the next position for each cell at a given direction.
Add a setInterval callback that moves the snake every 500ms by calling the move function.
