Things I have left to write

Turn handling (calling the Clash class)
Creating Turn summary (and inputting into history)
Resolving Turn summary into altering the game state
Turn output - all the messaging that says who did what
Output State - to set the message for each turn
Game state instantiating a turn
The large runner that interacts with game state
Enemy AI

Then the debugging starts

Things I have to test:
Game State
  open_game - X
  new enemy
User
  initialize
  change stats
  regroup
Clash
  resolve
  maybe generating a turn summary happens in clash?
Turn
  evaluate move
  action list
  get_input


  Places I'd like to go in the future

  Saving characters - and keeping records of wins/losses
  Different monsters
  Levels of difficulty based around an expanded AI and different monster_names
  Player V Player - which requires LAN or internet based connections between clients (much more advanced)

  
