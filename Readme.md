# Standard Template Library assignment

## Part I: Container exercise
* Create a vector, list, stack, map, and set (the last two can be ordered or unordered)
* Add 10 elements to each one (manually or using a loop)
* Remove the 3rd element from each one
* Print each one. Use each kind of loop (index-based, range-based, iterator-based) at least once. Restore the stack so it is unchanged.

## Part II: Algorithms exercise
* Implement three of the functions in [\<algorithm\>](https://www.cplusplus.com/reference/algorithm/) (not ones that we have implemented in class)
* Make a copy of one of the containers you filled in Part I.
* Call each of the algorithms you implemented on one of the containers. Call the corresponding STL algorithm on the other container. 
Each time, show that your implementation works the same as the STL implementation. The sequence should be
   - call your function f1 on container A
   - call std::f1 on container B
   - show that A and B are the same
   - call your function f2 on container A
   - call std::f2 on container B
   - show that A and B are the same
   - etc.
 * Make sure that your implementation is generic.
