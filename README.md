# Array Filler

This C program fills an array of length 40 with specific values in different sections and then prints the array.

## How it Works

1. The program defines a constant `ARR_LEN` to specify the length of the array.
2. It includes function prototypes for functions responsible for filling different sections of the array and printing the array.
3. In the `main()` function, an array of length `ARR_LEN` is declared.
4. Separate functions are defined to fill different sections of the array:
   - `fillSection0to9`: Fills elements 0-9 with consecutive integers from 0 to 9.
   - `fillSection10to19`: Fills elements 10-19 with values starting from 100 and increasing by 10 for each subsequent element.
   - `fillSection20to25`: Fills elements 20-25 with predefined values.
   - `fillSection26to39`: Fills elements 26-39 with values generated using the Collatz sequence.
5. The `nextCollatz` function calculates the next value in the Collatz sequence.
6. The `printArray` function prints the elements of the array.


## Functions

- `void fillSection0to9(int *arr)`: Fills elements 0-9 with consecutive integers.
  
- `void fillSection10to19(int *arr)`: Fills elements 10-19 with values starting from 100 and increasing by 10.
  
- `void fillSection20to25(int *arr)`: Fills elements 20-25 with predefined values.
  
- `void fillSection26to39(int *arr)`: Fills elements 26-39 with values generated using the Collatz sequence.

- `int nextCollatz(int n)`: Calculates the next value in the Collatz sequence.

- `void printArray(int *arr)`: Prints the elements of the array.

## Notes

- The program demonstrates different ways to fill an array with specific values using loops and predefined sequences.
- It showcases the use of pointers for array manipulation and function passing.

