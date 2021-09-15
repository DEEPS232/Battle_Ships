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
def random_col(board_in):
