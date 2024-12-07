# Blackjack Game

This is a Python implementation of the classic card game Blackjack. The game is played between a player and a dealer, where the objective is to get a hand value as close to 21 as possible without exceeding it.

## ✨Features<br><br>

•	🎴 Fully functional gameplay, including dealing cards, hitting, and standing.<br>
•	🤖 Dealer automatically plays according to Blackjack rules (must hit if hand value is under 17).<br>
•	🔁 Supports multiple rounds of play in one session.<br>
•	🃏 Handles special Blackjack rules, like treating aces as either 1 or 11 based on the hand value.<br>
•	🏆 Automatically checks for winning conditions, including busts, blackjack, and ties.<br><br>

## 🎮 How to Play<br><br>

1.	▶️ Run the game in a Python environment.<br>
2.	📝 Enter the number of games you’d like to play.<br>
3.	During your turn:<br>
&nbsp;&nbsp;•	🖐️ Choose Hit to draw another card.<br>
&nbsp;&nbsp;•	🖐️ Choose Stand to keep your current hand and let the dealer play.<br>
4.🃏 The dealer plays according to the rules of Blackjack.<br>
5.	At the end of the round, the winner is determined based on the hand values.<br><br>

## 🏅 Winning Conditions:<br><br>

•	🎉 Your hand value is closer to 21 than the dealer’s without exceeding 21.<br>
•	❌ The dealer’s hand value exceeds 21 (dealer busts).<br>
•	🃏 You get a Blackjack (Ace + 10-value card) and the dealer does not.<br><br>

## 🛠️ Installation<br><br>

Ensure you have Python installed on your computer. Clone or download this repository and save the blackjack.py file.<br><br>

## ▶️ How to Run<br><br>

1.	Open your terminal or command prompt.<br>
2.	Navigate to the directory where the script is saved.<br>
3.	Run the game using:<br>

 ```
python blackjack.py
```
<br>

## 📜 Code Overview<br><br>

### 🂠 Card Class<br><br>

Represents an individual card in the deck with a suit and rank.<br>

### 🃏 Deck Class<br><br>

Manages the deck of cards:<br>
	•	🎴 Initializes a full 52-card deck.<br>
	•	🔄 Shuffles the deck.<br>
	•	🎁 Deals cards to players.<br><br>

### Hand Class<br><br>

Manages a player’s hand:<br>
	•	🃏 Tracks the cards in the hand.<br>
	•	🧮 Calculates the hand’s value.<br>
	•	👑 Handles special rules for Aces.<br>
	•	👀 Displays the hand to the player.<br><br>

### 🎮 Game Class<br><br>

Controls the flow of the game:<br>
	•	🔄 Manages multiple rounds.<br>
	•	🎮 Handles user input and gameplay.<br>
	•	🏆 Checks for winners and displays results.<br><br>


 ## 📜 Rules Implemented<br><br>

•	🤖 The dealer must hit if their hand value is less than 17.<br>
•	🃏 Aces count as 1 or 11 depending on which value keeps the hand closer to 21 without exceeding it.<br>
•	🏆 Blackjack (Ace + 10-value card) automatically wins unless both player and dealer have Blackjack.<br><br>

## 🚧 Known Limitations<br><br>

•	🖥️ This is a console-based implementation, so it lacks a graphical interface.<br>
•	👥 Multiplayer functionality is not supported; it’s a single-player game against the dealer.<br><br>

## 🚀 Future Enhancements<br>

•	🖼️ Add a graphical user interface (GUI) for better user interaction.<br>
•	🤝 Implement multiplayer mode.<br>
•	💵 Include betting mechanics with virtual chips.<br><br>
