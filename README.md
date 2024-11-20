### README.md  

# Rock, Paper, Scissors Game  

This project is a console-based implementation of the classic "Rock, Paper, Scissors" game. Players compete against the computer, which randomly selects an option. The game allows players to continue playing until they decide to quit.  

## Features  
- **Interactive Gameplay**: Players select between "rock," "paper," or "scissors," while the computer makes a random choice.  
- **Game Logic**: Determines the winner based on standard rules:  
  - Rock beats Scissors  
  - Paper beats Rock  
  - Scissors beats Paper  
- **Replay Option**: After each round, players can choose to play again or exit.  

## How It Works  
1. The program prompts the player to input their choice (rock, paper, or scissors).  
2. The computer randomly selects one of the three options.  
3. The game compares the choices and declares the winner or a tie.  
4. Players can decide whether to play another round or quit.  

## Example Usage  
```
Enter your choice (rock, paper, scissors): rock  
player: rock  
computer: scissors  
You win!  

Play again? (yes/no): yes  

Enter your choice (rock, paper, scissors): paper  
player: paper  
computer: rock  
You win!  

Play again? (yes/no): no  
Thanks for playing!  
```  

## Prerequisites  
- Python 3.x installed on your system.  

## Running the Program  
1. Clone or download this repository.  
2. Navigate to the directory containing the script.  
3. Run the program using the following command:  
   ```
   python rock_paper_scissors.py  
   ```  

## Notes  
- Input is case-sensitive; ensure to enter "rock," "paper," or "scissors" in lowercase.  
- Enter "yes" to play again or "no" to exit.  

