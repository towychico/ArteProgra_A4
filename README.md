# ArteProgra_A4

The code is a game with a ball where the ball describe a parabolic throw and have to hit the blue points. 

The functionality of each function is described below:

- `tap(x, y)`: This function is called when the user taps the screen. If the ball is not within the screen boundaries, it moves it to an initial position and gives it a velocity based on the position where the screen was touched.

- `inside(xy)`: This function checks whether the object represented by the vector `xy` is within the screen boundaries.

- `draw()`: This function draws the ball and targets on the screen.

- `move()`: This function moves the targets to the left and generates new targets randomly. It also moves the ball and checks whether it has collided with any targets. If so, it removes the target and increases the score. If the ball goes out of the screen, the game ends.

- `setup()`: This function configures the game window with a specific width and height, as well as an initial position on the screen.

- `hideturtle()`: This function hides the turtle cursor on the screen.

- `up()`: This function lifts the turtle's pen, meaning it will not draw when moved.

- `tracer()`: This function turns off automatic screen updates to improve performance.

- `onscreenclick()`: This function calls the `tap()` function when the screen is clicked.

- `done()`: This function starts the main event loop and keeps the game running until the window is closed.
