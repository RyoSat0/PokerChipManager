# Poker Chip Manager

Developed a dynamic poker chip management tool using Python and Tkinter, allowing for seamless game management.

## Purpose

I love poker. It's a game that has taught me many life lessons. Often, when I'm at a friend's house, we decide to play poker spontaneously. While we usually have a deck of cards, we often find ourselves without chips. To solve this, I developed a dynamic poker chip management tool using Python and Tkinter. This tool is designed to enhance casual poker games by tracking player decisions and chip amounts. The application allows users to input their names and initial buy-in amounts, make strategic choices like call, raise, or fold, and automatically updates each player's chip count after determining the round's winner. This project simplifies game management, ensuring a seamless and engaging poker experience. People can now play poker with a deck of cards and this code.

## Instructions on How to Play Poker Using This Tool

1. Run the code in any environment that supports the Tkinter Python library.
2. Choose the number of players.
3. Enter their names and the amount of points they would like to bet (if not entered, the default name and amount will be used, which is 2000 points).
4. Start the game by simply pressing the "Start a Game" button.

Once the game starts, a new screen pops up:

- In the top right corner, there is an info section that tells you how many rounds you have played, the current situation of the round (Is it pre-flop? Flop? Turn? River? Showdown?), and the current amount of small blind and big blind.
- At the top of the screen, there are two buttons: "New Round" and "Show Down," which are initially unavailable until it's time to do so.
- In the middle of the screen, the current total value in the pot is shown with a large number. Underneath, there's a list of players with their current stack size and current bet amount.

Whenever the user's name label has a pink background color, they get to make an action with three buttons at the bottom of the screen: Call/Check, Fold, and Raise. When raising the bet amount, the user can simply type the amount in the entry next to the raise button. When all players agree to bet the same amount or go all-in, the game proceeds to the next step of the round.

Once it is time for the showdown, all players still in the game will have their name label color changed to pink, and the "Showdown" button becomes available. The user can click on the players who won the pot (multiple selections are allowed when splitting occurs) and then click the "New Round" button. The program automatically refreshes the screen and manages the movement of chips for each player. Users can repeat this process until one player wins all the chips.
