Rabbits
=======

C++ for CS homewrk


A pair of newly born rabbits (one male, one female) is put in a field. Rabbits are able to mate at the age of one month so that at the end of the second month each pair produces two new pairs of rabbits and then dies.
Note: In month 0, there are 0 pairs of rabbits. In month 1, there is 1 pair of rabbits.

1. Write a program – using a while loop – that takes the number of months from the user and prints the number of pairs of rabbits at the end of that month.
2. In the same cpp file, write a recursive function rabbits() that takes the number of months as input and returns the number of pairs of rabbits at the end of that month.
3. In the main program, call the function rabbits() with the number that the user entered. Output both calculations (i.e. the one you obtained with the loop and the one that the recursive function returns) and see if they are equal.


Month 0: 0 pairs of rabbits
Month 1: 1 pair of rabbits (The newly born pair is put in the field. Let's call the pair A.)
Month 2: 1 pair of rabbits. (The pair A is now 1 month-old. The pair has mated but not produced new pairs yet.)
Month 3: 2 pairs of rabbits (The initial pair (A) produced 2 new pairs (B and C), and died. So at the end of month 3, we have B and C.)
Month 4: 2 pairs of rabbits (B and C are now 1 month old. They have not yet produced new pairs. So at the end of month 4, we have 2 pairs: B and C.)
Month 5: 4 pairs of rabbits (Pair B produced two new pairs: D and E. Pair C produced two new pairs: F and G. B and C died. So at the end of month 5, we have 4 pairs: D, E, F, G.)
Month 6: 4 pairs of rabbits...


An example of the running program:
Please enter the month:
5
According to the while loop, there are 4 pairs of rabbits at the end of month 5. According to the recursive function, there are 4 pairs of rabbits at the end of month 5.
