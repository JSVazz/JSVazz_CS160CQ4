Q1: CamelCase
The time complexity of this code is O(n) because we check each element 1 time 
in order to determine if it is uppercase and therefore the beggining of a new word
We navigate each letter by using a singular for loop
The Space complexity of this code is O(1) because hte input is a non chagning string that does not change in any way as the method runs


C2: Correctness & Loop Imvariant
The Time complexity of this code in the best case is O(n) because it uses the first loop to itterate through the array 1 time
In the inner loop we shift an element as needed. In the best case this only requires a small amount of shifts, if this amount of shift is anything less than n
by rules of big O it is negated.
The time complexity of this code in the worst case is O(n^2) because now on top of the first for loop being O(n)
We can see that in the case of a reverse sorted loop, we need to move each element at least n times
Therefore in the worst case the time complexity is O(n^2)
The Space complexity of this code is O(c) because this code always takes in a finite amount of data 
and does not recall itself in any way
