**Questions**

    [16,21,11,8,12,22] -> Merge Sort

    1. Write the sorting steps of above array.
    2. Write the Big-O notation of above array.

**Merge sorting steps for [16,21,11,8,12,22]:**

    1. Divide the array from the middle of it until remain one element of each part.
       1. [16,21,11] - [8,12,22] ____
            |                       |
       2. [16,21] - [11]___  [8,12]____-[22]__
              |           |      |    |       |
       3. [16] - [21]  [11]   [8] - [12]    [22]

    2. Sort and merge the last elements.
       1. In the left part, compare 16 and 11, put the 11 to the beginning and merge them. Result: [11,16,21]
       2. In the right part, compare 8 and 22, put the 8 to the beginning and merge them.
       Result: [8,12,22]
       3. Compare 8 and 11, put the 8 to the beginning.
       4. Compare 12 and 11, put the 11 after the 8.
       5. Compare 12 and 16, put the 12 after the 11.
       6. Compare 22 and 16, put the 16 after the 12.
       7. Compare 22 and 21, put the 21 after the 16.
       8. Put the 22 as the last element of the array.
    3. Result: [8,11,12,16,21,22]

**2. Big-O Notation of [8,11,12,16,21,22]:**

    It should be o(nlogn) from dividing the array for each part. (2^x = n)
