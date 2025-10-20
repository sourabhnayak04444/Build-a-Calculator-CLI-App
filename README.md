# Build-a-Calculator-CLI-App

The project is a **Python-based Command-Line Interface (CLI) calculator**.

The application works as follows:

1.  **Persistent Loop:** The calculator operates within a continuous loop, enabling users to perform multiple calculations without restarting the script.
2.  **Input Collection:** The user is first prompted to select the desired arithmetic operation ('+', '-', '*', or '/') or enter 'exit' to terminate the program.
3.  **Core Logic:** Upon selecting a valid operation, the user inputs two numerical operands. The script executes the calculation using a **modular function**     dedicated to that specific operation.
4.  **Error Handling:** The system includes built-in input validation to ensure all operands are numerical and contains logic to explicitly handle and prevent **division by zero** exceptions, providing an error message instead of crashing.
5.  **Output:** The final result of the calculation is displayed to the user before the loop restarts, prompting for the next operation.
