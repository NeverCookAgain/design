# Game script
## Title screen
After booting the game, the player will enter the title screen. Only the following events should be present:
* the game's logo,
* a text indicating how to move to the next section (i.e. "Press Space to start"),
* the team's copyright (i.e. "© 2025 The Never Cook Again Group"),
* and a live background with the game's characters doing menial tasks.

After the player presses the continue button(s), show an option to play the game, change some settings, view the credits, and quit the game. 

## Character Select Screen
After pressing the play button, the player is given the option of selecting one of 4 characters to play as: Rigatoni, Bill Burgers, Cousin Ricky, and Sweaty Todd
* These characters are identical in terms of gameplay, with the only difference being their appearance
* In multiplayer games, the game cannot start until each player has picked their character.

## Players get orders from customers
After the player presses the play button, players start at the front of the restaurant to receive orders from customers. Each order is unique, including dishes with specific five random ingredients and a random [special request](/standards/special-requests/README.md). 
* Customer's orders come in three separate difficulties, signified by their color schemes (Green = 1-star/easy, Blue = 2-stars/medium, Purple = 3-star/hard)
* Orders may involve use of normal or "nasty" ingredients, or the sandwich being cooked or sauced. extra criteria are more present in higher difficulties.
* Special requests may include things like allergies (food items that will tank the player's score if included in the order)

## Players make the food in an intense environment
* At this point, the three-minute timer starts and the player can pause the game at any time. 
* Players go on a mostly linear path to start creating the dish. Regardless of the dish, the players are typically supposed to go to the back of the long restaurant to cook their dish.
* This is done by grabbing ingredients one at a time from the Walk-in fridge, which contains all food items presented in a random configuration. Players then carry the items back to their cooking station. Once all items for a particular food item are gathered, the player may craft their order.
* In the meantime, [events](/standards/events/README.md) may be triggered by the players or automatically by the game, keeping players on their toes. Also, orders are public, so players can strategically sabotage others through various means.
* Additionally, items can spawn in random locations on the map, which can be picked up by players in addition to carrying food items. These items can provide boosts for the player, or give them the ability to sabotage other players more effectively.
* The cooking process should take roughly 30 seconds to a minute, depending on how complex the order is.

## Players give the orders to the customers
* After cooking the dish, the players are off to the front of the restaurant to give their masterpieces to their respective customers. 
* Some players may finish earlier or later than others. Early players should be careful though: anyone can still sabotage their dish while the round is ongoing.
* Events may still happen during this process.
* Orders are judged, and points are awarded based on how accurate they are to the original order, how long they took, and the difficulty of the original order. (More difficult orders give more points.)
* After the order is received, the player may take another one and start the process over.

## End of Round
Once the timer ends, the round is over. Chef Shamsay reviews the orders
* players are judged based on their points from orders, as well as other criteria such as their efficiency, how much they've messed with other players, etc.
* The player with the highest score wins the coveted promotion, while everyone else is fired for their incompetence.

After the results are shown, players can [play again from the start](#players-get-orders-from-customers).
