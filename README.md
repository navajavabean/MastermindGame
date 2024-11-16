# Mastermind Game: A Guessing Challenge in Java

## **About the Project**

Welcome to the **Mastermind Game**, where your goal is to guess a **randomly generated array of numbers** within 12 attempts. This project combines logic, interactive menus, and a sprinkle of randomness to create an engaging experience. Think you have what it takes to crack the code? Let’s find out!

---

## **How It Works**

1. **Start the Game:**
   - The program generates a random array of numbers between 0-9. The size of the array is decided by the user (within a range of 2-10).  
   - If *cheat mode* is activated, the random array is displayed to help with debugging or practice.

2. **Make Your Guesses:**
   - The player attempts to guess the computer’s random array. Each guess:
     - Identifies how many numbers are correct **and in the right position.**
     - Identifies how many numbers are correct but **in the wrong position.**

3. **Win or Lose:**
   - **You win:** If you guess the entire array correctly within 12 attempts.  
   - **You lose:** If you fail to guess the array after 12 attempts.

4. **Interactive Menu:**
   - After each guess, decide whether to keep playing or exit the game.

---

## **Key Features**

- **Cheat Mode:** Displays the computer-generated array for testing or practice.
- **Randomized Array:** Generates unique random numbers for the secret array.
- **Feedback System:** Provides specific hints after each guess:
  - Numbers correct and in the right place.
  - Numbers correct but in the wrong place.
- **Input Validation:** Ensures user inputs are integers, unique, and within range.

---

## **How to Play**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/MastermindGame.git
   ```

2. **Compile and Run the Game:**
   ```bash
   javac Mastermind.java
   java Mastermind
   ```

3. **Follow the Prompts:**
   - Choose the size of the random array.
   - Start guessing numbers within the range provided.
   - See your progress and try to guess the array within 12 attempts.

---

## **Significant Java Concepts**

- **Randomization:** The program uses `Math.random()` to generate unique random numbers for the array.
- **Input Validation:** Ensures user guesses are valid using loops and conditions.
- **Linear Search:** Checks for duplicates and validates guesses.
- **Interactive Menu:** Allows users to continue playing or exit at any point.
- **Arrays:** Core functionality revolves around creating, modifying, and comparing arrays.

---

## **Why This Project?**

This game is more than just a fun challenge—it’s a practical application of key programming concepts like loops, conditionals, and arrays. It’s also a great example of how logic and creativity can come together in coding to create something engaging and enjoyable.

---

## **Future Improvements**

- Add a **scoreboard** to track wins and losses.
- Introduce **difficulty levels** to adjust the range of numbers or attempts allowed.
- Create a **graphical user interface (GUI)** for a more interactive experience.

Enjoy the game and happy guessing! 🎉 
