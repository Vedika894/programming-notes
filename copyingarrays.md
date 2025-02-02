## Copying Arrays

To copy an array, we can not simply assign one array to another 
- this will just point your reference variable to the same array object in memory
- we , however have 2 choice :
- 1. use the Array clone() method
  2. illiterate through one array , and copy each element in another array
  3. if don't use the method and directly copy using the name, it will just give us a duplicate reference to the same array

     copyOf() method returns an array

**CopyOfRange() method**
> public static int[] copyOfRange(int[] original, int from, int to)

**Key Points**:
The from index is inclusive, meaning the element at index from is copied.
The to index is exclusive, meaning the element at index to is not copied.
If to is greater than the length of the original array, the returned array will be padded with the default values of the array’s element type (like 0 for int[], null for object arrays, etc.).
If from is greater than to, it will throw an IllegalArgumentException.
If from or to is out of bounds, it will also throw an ArrayIndexOutOfBoundsException.



  
