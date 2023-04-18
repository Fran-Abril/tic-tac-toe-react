# Tutorial: Tic-Tac-Toe
This [tutorial](https://react.dev/learn/tutorial-tic-tac-toe) does not assume any existing React knowledge. The techniques you’ll learn in the tutorial are fundamental to building any React app, and fully understanding it will give you a deep understanding of React. 

## Installation
To install the application, run the following command:
```bash
yarn electron:start
```

## Usage
To launch the application in development mode, run the following command:

```bash
yarn electron:start
```

This will start the application and open it in an Electron window. Any changes you make to the code will automatically reload in the application window.

To build the application for production, run the following command:

```bash
yarn electron:package:{mac | win | linux}
```

This will create a compiled version of the application in the "dist" directory. The application is now ready to be distributed and used by any user.

## Pending Improvements
If you have extra time or want to practice your new React skills, here are some ideas for improvements that you could make to the tic-tac-toe game, listed in order of increasing difficulty:

1. For the current move only, show “You are at move #…” instead of a button.
2. Rewrite Board to use two loops to make the squares instead of hardcoding them.
3. Add a toggle button that lets you sort the moves in either ascending or descending order.
4. When someone wins, highlight the three squares that caused the win (and when no one wins, display a message about the result being a draw).
5. Display the location for each move in the format (row, col) in the move history list.

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.