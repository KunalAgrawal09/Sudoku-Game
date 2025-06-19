# Sudoku-Game

A Sudoku game has specific rules and properties that define its structure and gameplay. Here are the key properties of a standard Sudoku puzzle:

# 1. Grid Structure

A 9×9 grid divided into 9 smaller 3×3 subgrids (boxes/regions).

Some cells are pre-filled with numbers (clues), while others are empty for the player to fill.

# 2. Rules of Sudoku

Row Constraint: Each row must contain all digits from 1 to 9 without repetition.

Column Constraint: Each column must contain all digits from 1 to 9 without repetition.

Box Constraint: Each 3×3 subgrid must contain all digits from 1 to 9 without repetition.

# 3. Uniqueness

A valid Sudoku puzzle must have only one possible solution.

# 4. Difficulty Levels

Puzzles can vary in difficulty (Easy, Medium, Hard) based on the number of pre-filled clues (fewer clues = harder).

# 5. Validation Logic (for Digital Sudoku Games)

Input Validation: Ensures only numbers (1-9) are entered.

Conflict Detection: Highlights duplicate numbers in rows, columns, or boxes.

Completion Check: Verifies if the entire grid is filled correctly.

# 6. Solvability

A well-designed Sudoku should be solvable without guessing, using pure logic. 

# If it satisfies all property then it runs otherwise it displays Invalid board!
