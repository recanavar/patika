**Question**

    Write the binary-search-tree steps for the [7,5,1,8,3,6,0,9,4,2] array.

    Example root is x. y is the right side of root. y bulunur. z is the right side of root.

1. Select any number as root from the array. Let's say, 5 is root.
2. Building the tree.
   1. 5 is root.
   2. Put 7 to the right of the 5.
   3. Put 1 to the left of the 5.
   4. Put 8 to the right of the 5 and right of the 7.
   5. Put 3 to the left of the 5 and right of the 1.
   6. Put 6 to the right of the 5 and left of the 7.
   7. Put 0 to the left of the 5 and left of the 1.
   8. Put 9 to the right of the 5, right of the 7 and right of the 8.
   9. Put 4 to the left of 5, right of the 1 and right of the 4.
   10. Put 2 to the left of the 5, right of the 1 and left of the 3.

**Result:**

<img src="/pics/bst_result.png"/>
