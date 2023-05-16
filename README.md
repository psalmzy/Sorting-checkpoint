# Sorting-checkpoint

Steps Procedure

Step 1 --> Start with the second element in the array since the first element (arr[0]) is considered already sorted.
Step 2 -->  Iterate over the remaining elements of the array, starting from the second element.
Step 3 -->  For each iteration, set the current element as the "key" value.
Step 4 --> Initialize a counter variable, let's call it "j", to keep track of the sorted portion of the array.
Step 5 --> While j is greater than or equal to 0 and the element at index j is greater than the key:
 Move the element at index j one position ahead (to the right) to make space for the key.
 Decrement j by 1.
Step 6 --> Place the key value in its correct position, which is j + 1.
Step 7 --> Repeat steps 3-6 until all elements are processed.
