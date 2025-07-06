# 🎲 Number Guessing Game in C

This is a simple **Number Guessing Game** written in the C programming language. The program generates a random number and prompts the user to guess it. Based on the guess, it provides feedback like "Lower number please" or "Higher number please" until the correct number is guessed.

---

## 📌 Features

- Random number generation using `rand()`
- User input via `scanf`
- Feedback hints for better guessing
- Tracks and displays number of attempts
- Loop-based implementation using `while`

---

## 🛠 Technologies Used

- C Language
- Standard libraries: `stdio.h`, `stdlib.h`, `time.h`

---

## ▶️ How It Works

1. The program generates a random number between 1 and 100 using `rand()`.
2. The user is asked to enter a guess.
3. If the guess is too high or too low, a message is printed:
   - **"Lower number please"**
   - **"Higher number please"**
4. The loop continues until the user guesses correctly.
5. When the correct number is guessed, the program displays the number of attempts used.

---

## 💡 Sample Output

```text
Guess the number between 1 and 100:
50
Higher number please
75
Lower number please
65
Higher number please
70
Congratulations! You guessed the number in 4 attempts.
