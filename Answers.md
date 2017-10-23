## COMP 271 002 F17 Lab 6 (Week 8)

####  1. Why does FixedArrayQueue require an explicit constructor?

We need an explicit constructor to initialize the queue with a fixed capacity, a size of 0, and a front index of 0. With a fixed capacity, we can also determine what the rear index is.

####  2. What happens when you offer an item to a full FixedArrayQueue?

You will be returned false because there is no space for a new item.

####  3. What happens when you poll an empty FixedArrayQueue?

Since there are no items in the queue to remove, the return will be null.

####  4. What is the time and (extra) space complexity of each of the FixedArrayQueue methods?

offer(): Time & Space complexity is O(1)

peek(): Time & Space complexity is  O(1)

poll(): Time & Space complexity is  O(1)

isEmpty(): Time & Space complexity is  O(1)

size(): Time & Space complexity is  O(1)

asList(): Time & Space complexity is O(n)
