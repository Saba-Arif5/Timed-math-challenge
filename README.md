# Timed-math-challenge

This is a simple math quiz game written in Python. It presents the user with a series of arithmetic problems and tracks their progress.

## How to Play

1.  **Run the script:** Save the code as a Python file (e.g., `math_quiz.py`) and run it from your terminal using `python math_quiz.py`.
2.  **Start the game:** Press Enter when prompted to begin the quiz.
3.  **Answer the questions:** The game will present you with 10 math problems.  Enter your answer for each problem and press Enter.
4.  **Results:** After completing all 10 problems, the game will display your total time taken to finish the quiz.  It also counts the number of incorrect answers, though this is not explicitly shown to the user.

## Game Mechanics

*   **Problem Generation:** The game generates random arithmetic problems using addition, subtraction, and multiplication.
*   **Number Range:** The numbers used in the problems are integers between 3 and 12 (inclusive).
*   **Operators:** The game uses the operators `+`, `-`, and `*`.
*   **Number of Problems:** The quiz consists of 10 problems.
*   **Time Tracking:** The game measures the time taken to complete the quiz.
*   **Answer Evaluation:** The game uses Python's `eval()` function to calculate the correct answer and compares it to the user's input.  Answers are rounded to two decimal places.

## Code Explanation

*   **`MIN_NUM` and `MAX_NUM`:** Constants defining the range of numbers used in the problems.
*   **`OPERATORS`:** A list of arithmetic operators used in the problems.
*   **`TOTAL_PROBLEMS`:** The total number of problems in the quiz.
*   **`generate_problem()`:** This function generates a random math problem and its corresponding answer.  It returns the problem as a string (e.g., "5+7") and the answer as a float.
*   **Main Game Loop:** The main part of the script iterates through the specified number of problems, presents them to the user, and checks their answers.  It also tracks the time taken.
*   **Error Handling:** The current code has minimal error handling.  It assumes the user will enter a valid numerical input.

## Future Improvements

*   **Input Validation:** Implement better input validation to handle non-numerical input or invalid expressions.
*   **Difficulty Levels:** Add different difficulty levels by adjusting the number range, operators, or problem complexity.
*   **Score Display:** Display the number of correct and incorrect answers to the user.
*   **User Interface:** Consider using a graphical user interface (GUI) for a more interactive experience.
*   **More Operators:** Include division or other mathematical operations.
*   **Code Comments:** Add more comments to the code for better readability and understanding.

## How to Run

1.  Make sure you have Python installed on your system.
2.  Save the code as a `.py` file (e.g., `math_quiz.py`).
3.  Open a terminal or command prompt.
4.  Navigate to the directory where you saved the file.
5.  Run the script using the command: `python math_quiz.py`

Enjoy the quiz!
