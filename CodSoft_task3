import random

def main():
    user_score = 0
    computer_score = 0
    choices = ['R', 'P', 'S']
    
    print("Welcome to Rock, Paper, Scissors!")

    while True:
        # Prompt the user to choose rock, paper, or scissors
        user_choice = input("\nEnter your choice (R for Rock, P for Paper, S for Scissors): ").upper()

        # Validate user input
        while user_choice not in choices:
            user_choice = input("Invalid choice! Please enter R, P, or S: ").upper()

        # Generate computer's choice
        computer_choice = random.choice(choices)

        # Display the choices
        print(f"You chose: {user_choice}")
        print(f"Computer chose: {computer_choice}")

        # Determine the winner
        if user_choice == computer_choice:
            print("It's a tie!")
        elif (user_choice == 'R' and computer_choice == 'S') or \
             (user_choice == 'P' and computer_choice == 'R') or \
             (user_choice == 'S' and computer_choice == 'P'):
            print("You win!")
            user_score += 1
        else:
            print("Computer wins!")
            computer_score += 1

        # Display scores
        print(f"Scores - You: {user_score}, Computer: {computer_score}")

        # Ask the user if they want to play again
        play_again = input("Do you want to play again? (Y/N): ").upper()
        if play_again != 'Y':
            break

    print(f"Thanks for playing! Final scores - You: {user_score}, Computer: {computer_score}")

if _name_ == "_main_":
    main()
