## Arrays Methods 
# sort 
- by default, it sorts in ascending order

# fill method 
 Filling all elements in an array with a new specific value

 ```java
int[] nums = {0, 0, 0};
// Arrays.fill() directly modifies the original array
Arrays.fill(nums, 1);   	// {1, 1, 1}

// Arrays.fill() can also indicates where to start and end
Arrays.fill(nums, 1, 2, 9)  // {1, 9, 1}
```
`Arrays.fill(array, fromIndex, toIndex, value) works like this:`

array: The array you want to fill.
fromIndex: The inclusive starting index (the first index to be filled).
toIndex: The exclusive ending index (the index up to which elements are filled, but not including it).
value: The value you want to fill into the array between fromIndex and toIndex - 1.
