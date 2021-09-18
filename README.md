# Battle_Ships
Code academy template

board = []
for i in range(5):
 board.append(["O"]*5) 
 # Printing this will create a board with "O" grid which is 5x5 
 
def print_boad(board_in):
  for row in board:
    print " ".join(row)

print_board(board)

# To remove the "" and combine the O's replace print row with print " ".join(row)

def random_row(board_in):
   return radiant(0,len(board_in)-1):
   

def random_col(board_in):
  return radiant(0,len(board_in)-1) 
  
  
print ship_row
print ship_col

# Write your code below!
if guess_row == ship_row and guess_col == ship_col:
  print "Congratulations! You sank my battleship!"
else:
  print "You missed my battleship!"
board[guess_row][guess_col]= "X"
print_board(board)
