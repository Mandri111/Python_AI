import random

choices = ["rock", "paper", "scissors"]

while True:
    computer = random.choice(choices)
    player = input("Type rock, paper or scissors: ").strip().lower()

    if player not in choices:
        print("That was not a valid choice. Choose rock, paper or scissors.")
        continue

    print("You chose:", player)
    print("Computer chose:", computer)

    if player == computer:
        print("It's a tie. Play again!\n")
        continue

    if player == "rock" and computer == "scissors":
        print("You win!")
    elif player == "paper" and computer == "rock":
        print("You win!")
    elif player == "scissors" and computer == "paper":
        print("You win!")
    else:
        print("You lose.")
    break
