# Abaka
## Game rules
- Two players compete against each other to score the most points.
- The game has a table with different combinations of dice that can be scored
- Each combination has 5 fields and one bonus field for each player to fill on his side of the board.
- The bonus field is filled when all 5 fields are filled. The value of the bonus field is the maximum value of the 5 fields.
- Only one player can score a bonus field in each row. Once a player scores a bonus field, the other player loses the opportunity to score it.
- At the beggining of every turn, the player rolls 5 dice
- He then can keep any number of dice and can make 2 throws with the other. He may keep all dice after the first roll if he wants.
- Player must action a category to score

The game gives the player a state and the player must return an action
Game includes the following:
- table_state
- mask_state
- dice_state
- player_turn_state
- throws_left_state
- action_return_state
- valid_actions_state

The player must return an action
- dice2keep action (2^5 = 32 possible actions)
- cell2score action (6 possible actions)
In total, the player has 45 possible actions