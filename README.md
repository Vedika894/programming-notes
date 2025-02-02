# programming-notes
## Arrays 

**Declaring vs initializing an Array**

Declaring 
declaring an array refers to creating a reference to an array without specifying its size or values,

`double[] nums;  // This is a declaration. It does not create or initialize the array yet`

Initializing an Array
Initialization happens when you allocate memory for the array and optionally set its values.

Initialization can happen in **two ways**:

**a. Declaring and Initializing in One Step (Array with predefined values)
You can declare and initialize the array in one line by providing the values directly.**

Example:
`double[] nums = {1.1, 2.2, 3.3, 4.4};  // This is both declaring and initializing the array`

Here, the array nums is declared and initialized with 4 values (1.1, 2.2, 3.3, and 4.4). The size of the array is automatically determined based on the number of values provided.

**b. Declaring First, Then Initializing (Array with a fixed size)
You can declare the array first and then allocate memory and assign values later.**

Example:

`double[] nums;        // Declaration
nums = new double[4]; // Initialization with a size of 4
nums[0] = 1.1;        // Assigning values
nums[1] = 2.2;
nums[2] = 3.3;
nums[3] = 4.4;
`
Here, the array nums is first declared, and then a new array of size 4 is created (initialized), followed by assigning specific values to each index of the array.

