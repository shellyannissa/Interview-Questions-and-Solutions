## Min Manhattan Distance for picking apples

Two set of coordinates are given indicative of the initial positions of persons A and B. An array of coordinates are given which represent the coordinates where apples fall. The cost assosiated with moving from one position (x1,y1) to another (y1,y2) is given by the Manhattan distance given by ( | x2 - x1 | + | y2 - y1 | ) . What is the minimum cost for collecting all the apples. Each apples has to be collected sequentially ( ie 3rd apple should be picked only after picking up the 2nd apple and the 1st before it)

Input 1

[1,1]

[4,2]

[
[5,5], [2,4], [3,4]
]

Output 1

9

Explanation

B moves to ( 5, 5 ) cost = | 5 - 4 | + | 5 - 2 | = 4

A moves to ( 2, 4 ) cost = 4 + | 2 - 4 | + | 4 - 2 | = 8

A moves to ( 3, 4 ) cost = 8 + | 3 - 2 | + | 4 - 4 | = 9

Input 2
