import random

def number_guessing_game():
    target_number = random.randint(1, 100)
    attempts = 0

    while True:
        guess = int(input("Enter your guess (1-100): "))
        attempts += 1

        if guess == target_number:
            print(f"Congratulations! You guessed the number in {attempts} attempts.")
            break
        elif guess < target_number:
            print("Too low. Try again.")
        else:
            print("Too high. Try again.")

number_guessing_game()
