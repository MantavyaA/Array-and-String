# Array-and-String

AIM : Usage of array and string in c++


SOFTWARE USED : VS CODE

THEORY : 

ARRAYS IN C++

Definition:

An array is a data structure that stores multiple values of the same data type in contiguous memory locations.

🔹 Key Points

Stores homogeneous data (all elements of the same type).

Fixed size – must be known at compile time.

Elements are accessed by an index (starting from 0 to size - 1).

Allows random access to any element using its index.

🔹 Types of Arrays

One-Dimensional → Linear data storage.

Two-Dimensional → Matrix-like structure.

Multi-Dimensional → Higher-order structures.

🔹 Advantages

1. Fast access and modification.

2. Simple to use for fixed-size data storage.

🔹 Limitations

1. Fixed size can lead to wasted memory or insufficient space.

2. No bounds checking → Accessing out-of-range elements causes undefined behavior.

🔹 Common Operations

Traversal – Visiting each element.

Insertion – Adding elements at specific positions.

Deletion – Removing elements.

Searching – Finding an element (linear/binary search).

Sorting – Arranging in ascending/descending order.

🔹 Usage in Advanced Structures

Matrices

Vectors

Stacks & Queues



 STRINGS IN C++

Definition:

A string is a sequence of characters used to represent textual data.

🔹 Types of Strings in C++

1️⃣ C-Style Strings (Character Arrays)

Implemented as an array of characters ending with a null character \0.

Functions from the C library handle operations (strlen, strcpy, strcmp, etc.).

Require manual size management.

Less safe compared to modern C++ strings.

2️⃣ string Class (STL)

Part of the Standard Template Library.

Supports dynamic resizing and automatic memory management.

Provides built-in functions for:

Concatenation (+)

Comparison (==)

Substring extraction (substr())

Character access (at() / [])

Supports operator overloading for intuitive usage.

Works easily with cin and cout.

🔹 Advantages of string Class

1. No manual memory management.

2.  Flexible and safer than C-style strings.

3. Improves readability and maintainability.







ALGORITHMS : 

1. Reverse the Array
   
Algorithm:

Step 1: Start

Step 2: Declare arr[50], num, temp

Step 3: Input number of elements → num

Step 4: Input num elements into arr

Step 5: Print the original array

Step 6: Set i = 0, j = num - 1

Step 7: While i < j:

  a. Swap arr[i] and arr[j] using temp
  
  b. Increment i and decrement j
  
Step 8: Print the reversed array

Step 9: Stop



2. Sum and Average of Array
   
Algorithm:

Step 1: Start

Step 2: Declare arr[100], sum = 0, average

Step 3: Input number of elements → n

Step 4: Input n elements into arr

Step 5: For i = 0 to n - 1:

  a. sum = sum + arr[i]
  
Step 6: Calculate average = sum / n

Step 7: Print sum and average

Step 8: Stop



3. Reverse a String
   
Algorithm:

Step 1: Start

Step 2: Declare two string variables: str and reversed

Step 3: Input a string into str

Step 4: Find the length of str → n

Step 5: For i = n - 1 down to 0:

  a. Append str[i] to reversed
  
Step 6: Print reversed

Step 7: End




4. Check Palindrome String
   
Algorithm:

Step 1: Start

Step 2: Declare a string str and integer count = 0

Step 3: Input a string into str

Step 4: Find the length of str → n

Step 5: For i = 0 to n / 2:

  a. If str[i] != str[n - 1 - i]:
  
    i. Set count = 1
    
    ii. Break the loop
    
Step 6: If count == 0:

  a. Print "String is a palindrome"
  
  Else:
  
  b. Print "String is not a palindrome"
  
Step 7: End



