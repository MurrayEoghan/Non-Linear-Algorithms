# Non-Linear-Algorithms 

rod_cutting

The idea behind this algorithm is it accepts an array of doubles and an integer. The integer represents the size of the rod with each 
unit being a piece of the rod. i.e if the int is 4, the rod is 4 units in length. The algorithm takes the size of the rod input and it 
takes an array of prices. The first element of the array in this case is 1.2 so an individual slice of the rod is worth 1.2. The second
element of the array is 3 which meens 2 chunks together is worth 6 etc. The 4th space is left as 0 because at the time, we were told to 
build the algorithm whereby chunks of 4 cant be prices, it must be blocks of 1, 2, 3 or 5. So for example, a rod of size 14 would be 
cut into 2x 5's and 1x 1 and 1x 3 which would give a price of 29 if the prices were {1.2, 3, 5.8, 0, 11} because two chunks of 5 is 22 and 1
chunk is worth 1.2 and 3 chunks is worth 5.8.
