# Rock, Paper, Scissors Game

In this game, the user gets the first chance to pick the option among Rock, paper and scissors. After that computer select from the remaining two choices(randomly), the winner is decided as per the rules.

## How to Play

In this game, the user gets the first chance to pick the option among Rock, paper and scissors. After that computer select from the remaining two choices(randomly), the winner is decided as per the rules.

### Rules
- Rock vs paper-> paper wins
- Rock vs scissor-> Rock wins
- paper vs scissor-> scissor wins.

## How to Run the Game

The game is implemented in the `Rock_Paper_Scissor_game.ipynb` Jupyter Notebook.

1.  **Open the Notebook**: Open `Rock_Paper_Scissor_game.ipynb` in a Jupyter Notebook environment (e.g., Jupyter Lab, Jupyter Notebook, Google Colab, VS Code with Python extension).
2.  **Run the Cells**: Execute the cells in the notebook. The last cell contains the call to `rock_paper_scissors_game()` which will start the game.

Alternatively, you can copy the `rock_paper_scissors_game()` function from the notebook into a Python (`.py`) file (e.g., `game.py`) and run it as follows:

```python
import random # Make sure to include imports if copying the function

def rock_paper_scissors_game():
    # ... (copy the function definition here) ...
    pass # Placeholder for the copied function

# To play the game, call the function:
if __name__ == '__main__':
    rock_paper_scissors_game()
```

## Contributing

Contributions are welcome! If you have ideas for improvements or find any issues, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes and commit them (`git commit -m 'Add some feature'`).
4.  Push to the branch (`git push origin feature/your-feature-name`).
5.  Open a Pull Request.

Please make sure your code adheres to good coding practices and includes comments where necessary.

## License

This project is licensed under the MIT License.

Copyright (c) 2024 the Project Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
