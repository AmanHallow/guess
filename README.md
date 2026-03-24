# 🎯 Guess the Number Game (Python)

A simple beginner Python project where the player tries to guess a randomly generated number.

## 📌 About the Project

This is a small Python game that generates a random number between **1 and 10**.
The player must guess the correct number. The program will tell the player if the guess is correct or wrong.

This project is great for beginners learning:

* Python basics
* User input
* Conditional statements
* Random number generation

## 🐍 Code

```python
import random

number = random.randint(1, 10)

print("Guess the number between 1 and 10")

guess = int(input("Enter your guess: "))

if guess == number:
    print("🎉 Correct! You guessed the number.")
else:
    print("❌ Wrong! The number was", number)
```

## ▶️ How to Run

1. Make sure Python is installed on your computer.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run the program:

```
python guess_game.py
```

## 💡 Features

* Random number generation
* Simple user input
* Beginner-friendly code
* Easy to modify and improve

## 🚀 Future Improvements

* Add multiple attempts
* Add difficulty levels
* Keep score
* Add hints for higher or lower guesses

## 👨‍💻 Author

Created by **AmanHallow**

---

⭐ If you like this project, feel free to star the repository!
