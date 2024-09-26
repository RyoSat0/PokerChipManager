# Poker Chip Manager
Developed a dynamic poker chip management tool using Python and Tkinter, allowing for seamless game management.

# Vision
I love poker. It’s a game that has taught me many life lessons. Often, when I’m at a friend’s house, we spontaneously decide to play, but we usually have a deck of cards and no chips. In the end, we couldn't play, and before I knew it, a new semester had begun. I don’t want to experience that disappointment again! 

To solve this, I developed a dynamic poker chip management tool. This tool enhances casual poker games by tracking player decisions and chip amounts with automatic updates. Now, people can play poker with just a deck of cards and this code—no heavy box of chips needed, and it weighs absolutely nothing!

<p align="center">
<img width="750" alt="Screenshot 2024-09-26 at 17 53 02" src="https://github.com/user-attachments/assets/a522282e-4251-4ba1-8f84-3c413bdd6917">
</p>

# Getting Started
1. Run the code in any environment that supports the Tkinter Python library.
2. Choose the number of players.
3. Enter their names and how many points they would like to bet (if not entered, the default name and amount of 2000 points will be used).
4. Start the game by simply pressing the "Start a Game" button. Once the game starts, a new screen will pop up.

# Understanding the Game Screen

Once the game starts, you'll see a new screen divided into key sections:

1. **Info Section (Top Right Corner)**
   - **Rounds Played**: This shows how many rounds have occurred in the current game.
   - **Current Stage**: Indicates the current round stage (pre-flop, flop, turn, river, or showdown)
   - **Blind Amounts**: Displays the current values of the small blind and big blind.

2. **Game Controls (Top of the Screen)**
   - **New Round Button**: This button becomes available at the end of a round to start fresh.
   - **Show Down Button**: This button activates when it’s time for the showdown, allowing you to input the winner.

3. **Current Pot Value (Center of the Screen)**
   - **Total Pot**: The current total amount in the pot is displayed prominently, showing how much is up for grabs.

4. **Player List (Below the Pot)**
   - **Player Info**: Lists each player's name along with their current stack size (amount of chips) and bet amount.

5. **Player Actions**
   - **Turn Indicator**: When a player’s name label turns pink, it indicates it’s their turn to act.
   - **Action Buttons**: Players can choose from:
     - **Call/Check**: Match the current bet or stay in without betting.
     - **Fold**: Withdraw from the current round.
     - **Raise**: Increase the bet amount (type the desired amount in the entry next to the Raise button).

6. **Showdown Phase**
   - **End of the Round**: When it’s time for the showdown, players still in the game will have their labels turn pink, and the "Showdown" button will activate.
   - **Selecting Winners**: Users can select who won the pot (multiple selections are allowed for splits) and then click the "New Round" button to refresh the game.
   - **Chip Movement**: The program automatically handles the movement of chips for each player, ensuring a smooth transition between rounds.

## Disclaimer
**Some features, such as the side pot, are still incomplete.  Please refrain from using this tool for real-money games.  I do not accept any responsibility or liability for losses incurred from the use of this tool.**

## License  
This project is licensed under the MIT License.
