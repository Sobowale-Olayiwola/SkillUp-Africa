## Given an array with integers of length 6. Write a bubble sort algorithm to arrange the integers from smallest to largest.
Step 1: Start Bubble Sort
Step 2: Set a variable to the last index of the array and call it unsorted partition(p) set p=5
Step 3: Set i=0 which serves as starting index of the array
Step 4: Compare integers at position i and i+1
Step 5: If i > i+1 swap position and set i=i+1 then go to step 7
Step 6: If i < i+1 don't swap and set i = i+1 then go to step 7
Step 7: If i = p set i = 0 and set p = p - 1 then go to step 4
Step 8: If i != p then go to step 4
Step 8: if p = 0 then all integers are sorted 
Step 9: End Bubble sort
