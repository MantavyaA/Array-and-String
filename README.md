# Array-and-String

AIM : Usage of array and string in c++

SOFTWARE USED : VS CODE

THEORY : 

Arrays in C++

An array is a data structure used to store multiple values of the same data type in contiguous memory locations. Arrays are useful for managing large amounts of data efficiently under a single variable name. The size of an array is fixed and must be known at compile time. Each element in an array is identified by its index, which starts from zero and goes up to size minus one.

Arrays allow random access to any element using its index. They are suitable for storing homogeneous data like numbers, characters, or any user-defined data types. Arrays can be one-dimensional (linear data), two-dimensional (matrix-like structure), or multi-dimensional.

Although arrays offer fast access and modification, their fixed size can lead to wasted memory or lack of flexibility. To overcome this, dynamic memory allocation can be used with pointers. Arrays in C++ do not perform bounds checking, so accessing out-of-range elements can lead to undefined behavior.

Operations on arrays include traversal, insertion, deletion, searching, and sorting. These operations often require looping structures like for or while. Arrays are also used in more complex data structures like matrices, vectors, stacks, and queues.

Strings in C++

Strings are sequences of characters used to represent textual data. In C++, strings can be implemented either as character arrays (C-style strings) or using the string class from the Standard Template Library.

C-style strings are arrays of characters ending with a null character (\0). These strings are handled using functions from the C library like strlen, strcpy, strcmp, etc. They are less safe and require manual management of size and termination.

The string class in C++ provides a more convenient and safe way to handle strings. It allows dynamic resizing, automatic memory management, and built-in functions for common operations such as concatenation, comparison, substring extraction, and character access.

C++ strings support operator overloading, allowing intuitive usage like using + for concatenation or == for comparison. They also support input and output operations using cin and cout.

Strings in C++ are mutable, meaning their contents can be modified after creation. The string class hides low-level memory management, making it suitable for modern C++ programming. It improves readability, maintainability, and reduces the chances of errors compared to C-style strings.


ALGORITHMS : 

1. Reverse the Array
Algorithm:

1. Start
2. Declare arr[50], num, temp
3. Input number of elements (num)
4. Input num elements into arr
5. Print original array
6. Set i = 0, j = num - 1
7. While i < j:
      a. Swap arr[i] and arr[j] using temp
      b. Increment i and decrement j
8. Print reversed array
9. Stop

    
2. Sum and Average of Array
Algorithm:

1. Start
2. Declare arr[100], sum = 0, average
3. Input number of elements (n)
4. Input n elements into arr
5. For i = 0 to n-1:
      a. sum = sum + arr[i]
6. average = sum / n
7. Print sum and average
8. Stop


3. Algorithm to Reverse a String
   
Step 1: Start
Step 2: Declare two string variables: str and reversed
Step 3: Input a string from the user and store it in str
Step 4: Find the length of the string and store it in variable n
Step 5: Run a loop from i = n - 1 down to 0
Step 6: In each iteration, append str[i] to the reversed string
Step 7: After the loop ends, print the reversed string
Step 8: End


5. Algorithm to Check Palindrome String
   
Step 1: Start
Step 2: Declare a string variable str and an integer variable count
Step 3: Input a string from the user and store it in str
Step 4: Find the length of the string and store it in variable n
Step 5: Run a loop from i = 0 to n / 2
Step 6: In each iteration, compare str[i] with str[n - 1 - i]
Step 7: If both characters are not equal, set count = 1 and break the loop
Step 8: After the loop, check the value of count
If count == 0, print that the string is a palindrome
Else, print that it is not a palindrome
Step 9: End


