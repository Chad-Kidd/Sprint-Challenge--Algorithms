#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
#O(n)
#a is constant input/runtime increase linear 

b)
#O(n2)
#get rid of constant - nested loop depends on for loop (n) to execute

c)
#O(n)
#input/runtime increase linear 

#originally thought Constant O(1) but that would mean
#The algorithm does a constant number of operations independent on the input
#and this isn't the case

## Exercise II

#start at e floor
#if floor > e floor egg breaks
#if floor < e floor egg doesn't break 

#But I guess things aren't that easy & you have to do a BINARY SORT
#MY ANSWER
#pivot at middle
#evaluate high - pivot < floor
#if egg doesn't break - loop through till egg breaks
#else egg is safe no more bad egg breaking floors
