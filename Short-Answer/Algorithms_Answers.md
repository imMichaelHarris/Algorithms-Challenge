#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This algorithm is o(n), originally it looks like it shoud be O(n*3) but as you go through the loop it shouldn't loop more than the given n number


b) This algorithm is O(n log n). The for loop makes in at least O(n) but inside of that for loop there is a while loop and in the while loop it multiples j by 2 which makes 
the j variable more larger than n quicker and will exit the loop and continue with the for loop 


c) I would say this algorithm is O(n) becuasee the recursion is on calling itself for n number of times and simply just adding 2 to that current number of bunnies.

## Exercise II
 n is number of floors
 f if the floor that the egg will break if thrown

 Need to drop eggs on every floor and track if they break or not
 
thrown = 0
broken = 0
for i in range(1, n):
    if i >= f:
        broken += 1
    else:
        thrown += 1

This algorithm is o(n)
