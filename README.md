# loops_excersie 1
for i in range(-5,5):
    print(i)
# loops_excersie 2
squares = ['red', 'yellow','green','purple','blue']
print(len(squares))
for x in range(len(squares)): print(squares[x])
# loops_excersise 3
squares = ['orange', 'orange','orange', 'purple', 'blue ', 'orange']
new_squares = []
i = 0
while(i < len(squares) and squares[i] == 'orange'):
    new_squares.append(squares[i])
    i = i + 1
print (new_squares)
