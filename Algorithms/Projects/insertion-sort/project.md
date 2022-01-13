**Questions**

    [22,27,16,2,18,6] -> Insertion Sort

    1. Write the sorting steps of above array.
    2. Write the Big-O notation of above array.
    Info: Time Complexity:
    - Average case: The number of we searched is in the middle of the array.- Worst case: The number of we searched is in the end of the array.
    - Best case: The number of we searched is in the beginning of the array.
    3. Which case is the appropriate case for number 18?

    4. Write the four steps of the array [7,3,5,8,2,9,4,15,6] for Insertion Sort.

**1. Insertion sorting steps for [22,27,16,2,18,6]:**

    1.  Find the smallest number in the array. -> 2
    2.  Put 2 to the beginning of the array. New array: [2,27,16,22,18,6]
    3.  Find the smallest one in the remaining numbers. -> 6
    4.  Put the 6 in the beginning of remaining numbers in the array after 2. New array: [2,6,16,22,18,27]
    5.  Find the smallest one in the remaining numbers. -> 16
    6.  Put the 16 in the beginning of remaining numbers in the array after 6. New array: [2,6,16,22,18,27]
    7.  Find the smallest one in the remaining numbers. -> 18
    8.  Put the 18 in the beginning of remaining numbers in the array after 16. New array: [2,6,16,18,22,27]
    9.  Find the smallest one in the remaining numbers. -> 22
    10. Put the 22 in the beginning of remaining numbers in the array after 18. New array:[2,6,16,18,22,27]
    11. Finish the sorting.

**2. Big-O Notation of [22,27,16,2,18,6]:**

    Each number is processed individually in this algorithm. So implemented total calculation number should be n.(n+1).

    As a result:
    Time complexity: o(n^2)

**3. Appropriate case for the number 18 of [22,27,16,2,18,6]:**

    - Best case: The number of we searched is in the beginning of the array.
    - Average case: The number of we searched is in the middle of the array.- Worst case: The number of we searched is in the end of the array.

    -> Average case is the appropriate case for the number of 18.

**4. First four steps for [7,3,5,8,2,9,4,15,6] array:**

       1. [2,3,5,8,7,9,4,15,6]
       2. [2,3,4,8,7,9,5,15,6]
       3. [2,3,4,5,7,9,8,15,6]
       4. [2,3,4,5,6,9,8,15,7]
