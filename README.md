# Maze Generation with Matter.js

This project demonstrates a maze generation algorithm using Matter.js, a 2D physics engine for the web. The generated maze consists of a grid of cells, and walls are removed to create paths through the maze.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/maze-generation.git
   ```

2. Open the `index.html` file in your web browser.

3. You should now see the generated maze on the web page.

## How It Works

The maze generation algorithm works as follows:

1. Create a grid of cells. The `cells` variable determines the number of cells in each row and column.

2. Start the generation process from a random cell in the grid.

3. Randomly choose a neighbor cell that has not been visited yet.

4. Remove the wall between the current cell and the chosen neighbor cell to create a path.

5. Mark the chosen neighbor cell as visited and make it the current cell.

6. Repeat steps 3 to 5 until all cells have been visited.

7. Add walls around the edges of the grid to form the outer boundary of the maze.

## Controls

You can move the ball through the maze using the following keyboard controls:

- W: Move the ball upward.
- D: Move the ball rightward.
- S: Move the ball downward.
- A: Move the ball leftward.

## Built With

- [Matter.js](https://brm.io/matter-js/): A 2D physics engine for the web.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The maze generation algorithm is based on recursive backtracking.
- Inspired by [Maze Generation: Recursive Backtracking](https://weblog.jamisbuck.org/2010/12/27/maze-generation-recursive-backtracking) by Jamis Buck.

Feel free to customize this README file based on your project's specific details and additional information you want to provide to users. Make sure to include any prerequisites or setup instructions needed to run the project successfully.
