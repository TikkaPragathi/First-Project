This Python code simulates the rolling of multiple dice and displays their visual representation along with the total sum.

**Code Breakdown**

**1. Import:**
   - `import random`: Imports the `random` module for generating random numbers.

**2. Dice Art Dictionary:**
   - `dice_art`: A dictionary that maps each dice roll (1-6) to its ASCII art representation. Each key-value pair consists of a dice roll and a tuple of strings, where each string represents a line of the dice's ASCII art.

**3. `roll_dice` Function:**
   - Takes the number of dice as input.
   - Initializes an empty list `dice` to store the rolls.
   - Initializes a `total` variable to keep track of the sum of the rolls.
   - Iterates `num_dice` times:
     - Generates a random integer between 1 and 6.
     - Appends the random integer to the `dice` list.
     - Adds the random integer to the `total`.
   - Returns the `dice` list and the `total` sum.

**4. Main Execution:**
   - Prompts the user to enter the number of dice to roll.
   - Handles potential `ValueError` exceptions if the input is not an integer.
   - Calls the `roll_dice` function to get the dice rolls and total.
   - Iterates over each line of the dice art for each die and prints it, creating a visual representation of the rolled dice.
   - Prints the total sum of the dice rolls.

**How to Use:**

1. **Run the Code:** Execute the Python script.
2. **Input:** Enter the desired number of dice to roll when prompted.
3. **Output:**
   - The code will display the visual representation of the rolled dice.
   - The total sum of the dice rolls will be printed.

**Example:**

If you input `3` as the number of dice, you might see an output like:

```
┌─────────┐ ┌─────────┐ ┌─────────┐
│         │ │ ●       │ │ ●     ● │
│    ●    │ │         │ │         │
│         │ │       ● │ │ ●     ● │
└─────────┘ └─────────┘ └─────────┘
Total: 11
```

**Additional Notes:**

- The ASCII art for the dice can be customized to create different visual styles.
- The `roll_dice` function can be further enhanced to include features like weighted dice or specific dice types.
- Error handling can be expanded to handle other potential exceptions, such as negative input values.

By following these steps and considering the additional notes, you can effectively use and customize this code to create various dice rolling simulations.
