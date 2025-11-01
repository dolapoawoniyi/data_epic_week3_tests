# PROJECT DETAILS

## PROJECT AUTHOR
- *Author*: ***Awoniyi Dolapo***
  
## PROJECT TITLE
🎯 **Guess the Number Game**

## PEER REVIEWER
- *Peer Reviewer*: ***Ajala Timilehin***

### 🧩 **Overview**
This is a simple number guessing game where the computer randomly selects a number, and the user tries to guess it. If the user’s guess matches the computer’s number, they win otherwise, they are prompted to try again.

### 🎯 **Objectives**
- Prompt the user for a guess within a specified range.
- Generate a random number in that same range.
- Compare both numbers using conditional logic.
- Display appropriate messages for each outcome.

### 🔢 **Inputs & Outputs**
Input: A single integer (e.g., between 1 and 10). Output:
- ✅ Correct Guess: “YES! You beat the matrix.”
-  ❌ Incorrect Guess: Feedback such as “Too high,” “Too low,” or “Invalid input.”

### ⚙️ **Algorithm Steps**
1. Import the random module.
2. Generate a random number within the defined range and store it (e.g., computerNumber).
3. Begin a loop that continues until the user guesses correctly.
4. Prompt the user to input a number (e.g., “Guess a number between 1 and 10”).
5. Validate the input:
    - If it’s not a number or out of range, show: “Invalid input. Please guess between 1–10.”
6. Compare guesses:
    - If the guess is greater → “Too high, try again.”
    - If the guess is lower → “Too low, try again.”
    - If the guess matches → “YES! You beat the matrix.”
7. End the loop once the correct number is guessed.


### 🧪 **Example Output**
Guess a number between 1 and 10: 5
Too low! Try again.
Guess a number between 1 and 10: 9
Correct! You got it!
