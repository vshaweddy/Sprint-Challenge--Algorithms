#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) It will be linear O(n) because it has while loop 


b) It will be quadratic because there are two loops O(n^2)


c) It will be linear O(n)

## Exercise II


1. get the input of the total number of floor (int)

2. divide the total number of floor by two to get the middle floor and save it to the current floor

3. set the previous floor to zero

3. check if the egg is broken or not if it's thrown from the middle floor which is the current floor

4. if it's not broken, update the current floor to the previous floor, get the middle upper half (range from the max number floor to the current floor), check if the middle floor is the same with the current floor or not, if it's yes, return this current floor, if it's not update the previous floor to the current floor, and assign middle floor to the current floor

5. if it's broken, update the current floor to the previous floor, get the middle lower half (range from the max number floor to the current floor), check if the middle floor is the same with the current floor or not, if it's yes, return this current floor, if it's not update the previous floor to the current floor, and assign middle floor to the current floor

