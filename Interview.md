
###

1. **C**
2. **CPP**
3. **OOPS**
4. **STL**
5. **Data Structure**
6. **DBMS**
7. **SQL**
8. **CN**
9. **OS**
10. **Linux**
11. **Basic Cloud**
12. **Azure**
13. **React**
14. **JS**
15. **HTML/CSS**
16. **Git**
17. **ML/AI**
18. **Cybersecurity**
19. **Internship**
20. **Project 1**
21. **Project 2**
22. **HR questions**
23. **miscellaneous quesions**

###



### Basic C Concepts

1. **Why is C called a mid-level programming language?**
2. **What are the features of the C language?**
3. **What is a token?**
4. **What is the use of printf() and scanf() functions? Also explain format specifiers.**
5. **What's the value of the expression 5["abxdef"]?**
6. **What is a built-in function in C?**
7. **What is a Preprocessor?**
8. **In C, What is the #line used for?**
9. **How can a string be converted to a number?**
10. **How can a number be converted to a string?**
11. **What is recursion in C?**
12. **Why doesn’t C support function overloading?**
13. **What is the difference between global int and static int declaration?**
14. **What is a pointer in C?**
15. **Difference between const char* p and char const* p?**
16. **What is pointer to pointer in C?**
17. **Why n++ executes faster than n+1?**
18. **What is typecasting in C?**
19. **What are the advantages of Macro over function?**
20. **What are Enumerations?**
21. **When should we use the register storage specifier?**

### Intermediate C Concepts

22. **Specify different types of decision control statements?**
23. **What is an r-value and l-value?**
24. **What is the difference between malloc() and calloc()?**
25. **What is the difference between struct and union in C?**
26. **What is call by reference in functions?**
27. **What is pass by reference in functions?**
28. **What is a memory leak? How to avoid it?**
29. **What is Dynamic memory allocation in C? Name the dynamic allocation functions.**
30. **What is typedef?**
31. **Why is it usually a bad idea to use gets()? Suggest a workaround.**
32. **What is the difference between #include "..." and #include <...>?**
33. **What are dangling pointers? How are dangling pointers different from memory leaks?**
34. **What is the difference between ‘g’ and “g” in C?**
35. **What is a near pointer and a far pointer in C?**
36. **Which structure is used to link the program and the operating system?**
37. **Suppose a global variable and local variable have the same name. Is it possible to access a global variable from a block where local variables are defined?**
38. **Which is better #define or enum?**

### Advanced C Concepts

39. **How can you remove duplicates in an array?**
40. **Can we compile a program without a main() function?**
41. **Write a program to get the higher and lower nibble of a byte without using shift operator?**
42. **How do you override a defined macro?**
43. **Write a C program to check if it is a palindrome number or not using a recursive method.**
44. **C program to check the given number format is in binary or not.**
45. **C Program to find a sum of digits of a number using recursion.**
46. **Can you tell me how to check whether a linked list is circular?**
47. **What is the use of a semicolon (;) at the end of every program statement?**
48. **How to call a function before main()?**
49. **Differentiate between the macros and the functions.**
50. **Differentiate Source Codes from Object Codes**
51. **What are header files and what are its uses in C programming?**
52. **When is the "void" keyword used in a function**
53. **What is dynamic data structure?**
54. **Add Two Numbers Without Using the Addition Operator**
55. **Subtract Two Numbers Without Using Subtraction Operator**
56. **Multiply an Integer Number by 2 Without Using Multiplication Operator**
57. **Check whether the number is EVEN or ODD, without using any arithmetic or relational operators**
58. **Reverse the Linked List. Input: 1->2->3->4->5->NULL Output: 5->4->3->2->1->NULL**
59. **Check for Balanced Parentheses using Stack**
60. **Program to find nth Fibonacci number**
61. **Write a program to find the node at which the intersection of two singly linked lists begins.**
62. **Merge Two sorted Linked List**

### Memory Management

63. **Explain the difference between memory allocation on the stack and heap.**
64. **How do you handle memory allocation errors (e.g., malloc failure)?**
65. **Describe techniques for preventing memory leaks.**
66. **What are some best practices for memory management in C?**

### Advanced Data Structures

67. **Explain the concept of self-balancing binary search trees (e.g., AVL trees, red-black trees).**
68. **How would you implement a hash table in C?**
69. **Discuss common operations on graphs (e.g., depth-first search, breadth-first search) and their time/space complexity.**
70. **Describe scenarios where using a custom data structure might be beneficial over standard library options.**

### Open Ended/Problem Solving

71. **Design a function to reverse a string in-place (without allocating additional memory).**
72. **Write a C program to find the longest common subsequence of two strings.**
73. **Implement a simple LRU (Least Recently Used) cache eviction policy.**
74. **Describe an approach for compressing a large text file in C.**

### Additional Questions for TCS Interviews

75. **Explain the concept of "volatile" keyword in C.**
76. **How can you achieve polymorphism in C?**
77. **What are bitwise operators and how are they used in C?**
78. **Explain the difference between struct and typedef struct.**
79. **What is the significance of static keyword in C?**
80. **Write a C program to sort an array using bubble sort.**
81. **Explain the difference between break and continue statements in C.**
82. **How can you dynamically allocate a 2D array in C?**
83. **Write a program to swap two variables without using a temporary variable.**
84. **What are the uses of the const keyword in C?**




### Basic C Concepts

1. **Why is C called a mid-level programming language?**
   C is often referred to as a mid-level programming language because it combines the features of low-level assembly languages with the flexibility and ease of high-level languages. It provides direct access to system-level resources like memory and hardware, which are characteristic of low-level languages, while also offering higher-level abstractions like functions and data structures.

2. **What are the features of the C language?**
   C language features include:
   - Procedural: Supports procedural programming with functions.
   - Structured: Allows structured programming with control flow constructs.
   - Portable: Code written in C can be compiled on different platforms with minimal changes.
   - Efficient: Provides low-level access to memory and hardware.
   - Extensible: Supports modular programming with libraries.
   - Simple syntax: Has a concise and straightforward syntax.

3. **What is a token?**
   In C, a token is the smallest individual unit in the source code that the compiler recognizes. Tokens include keywords, identifiers, constants, string literals, operators, and punctuation symbols.

4. **What is the use of `printf()` and `scanf()` functions? Also explain format specifiers.**
   - `printf()`: Used to print formatted output to the console. Format specifiers, such as `%d` for integers and `%s` for strings, are placeholders that specify the type and format of the data to be printed.
   - `scanf()`: Used to read formatted input from the console. Format specifiers in `scanf()` specify the type and format of the data to be read and stored in variables.

5. **What's the value of the expression `5["abxdef"]`?**
   This expression is equivalent to `"abxdef"[5]`, which accesses the 6th character in the string `"abxdef"`. So, the value is `'f'`.

6. **What is a built-in function in C?**
   Built-in functions are predefined functions provided by the C standard library. Examples include `printf()`, `scanf()`, `strlen()`, `malloc()`, `free()`, etc.

7. **What is a Preprocessor?**
   The preprocessor is a program that processes the source code before it is compiled. It handles directives starting with `#`, such as `#include` for including header files, `#define` for defining macros, and `#ifdef` for conditional compilation.

8. **In C, What is the `#line` used for?**
   The `#line` directive is used to change the line number and filename used by the compiler for error messages and debugging information. It is commonly used by code generators or preprocessors to maintain accurate line numbers in the output.

9. **How can a string be converted to a number?**
   You can use library functions like `atoi()` (for converting to integers), `atof()` (for converting to floating-point numbers), or `strtol()` (for converting to long integers) to convert a string to a numeric value.

10. **How can a number be converted to a string?**
    You can use functions like `sprintf()` or `snprintf()` to convert numbers to strings. Alternatively, you can use library functions like `itoa()` or `gcvt()`.

11. **What is recursion in C?**
    Recursion is a programming technique where a function calls itself directly or indirectly to solve a problem. In C, recursion allows elegant and concise solutions to certain problems, such as factorial calculation, Fibonacci series, and tree traversal.

12. **Why doesn’t C support function overloading?**
    C does not support function overloading because it does not perform automatic type conversion between arguments. Each function must have a unique name, and the compiler cannot determine which overloaded function to call based on argument types alone.

13. **What is the difference between global `int` and static `int` declaration?**
    - Global `int` declaration: Declares a variable with global scope that is accessible throughout the program.
    - Static `int` declaration: Declares a variable with static storage duration, meaning it retains its value between function calls and is only accessible within the scope where it is declared.

14. **What is a pointer in C?**
    A pointer in C is a variable that holds the memory address of another variable. It allows indirect access to memory locations and facilitates dynamic memory allocation and manipulation of data structures like arrays and linked lists.

15. **Difference between `const char* p` and `char const* p`?**
    Both `const char* p` and `char const* p` declare a pointer to a constant character. The `const` keyword specifies that the data pointed to by `p` is constant and cannot be modified. The pointer `p` itself can be modified to point to different memory locations.

16. **What is pointer to pointer in C?**
    A pointer to pointer in C is a pointer variable that holds the memory address of another pointer. It allows indirect access to a pointer variable, which in turn can be used to access the value stored at a particular memory address.

17. **Why `n++` executes faster than `n+1`?**
    `n++` and `n+1` are not directly comparable operations. `n++` increments the value of `n` and returns its original value, while `n+1` adds 1 to `n` but does not modify its value. In terms of performance, any difference would be negligible, and modern compilers would likely optimize both expressions similarly.

18. **What is typecasting in C?**
    Typecasting in C is the process of converting a value from one data type to another. It can be done explicitly using casting operators like `(type)` or implicitly by the compiler when compatible data types are involved in an expression.

19. **What are the advantages of Macro over function?**
    - Macros are processed by the preprocessor, which can result in faster execution compared to function calls.
    - Macros can accept variable number of arguments, unlike functions with fixed parameters.
    - Macros can perform text substitution, allowing for more flexibility and customization.
    - Macros can be used for conditional compilation, enabling selective inclusion/exclusion of code.

20. **What are Enumerations?**
    Enumerations (enums) in C are user-defined data types that consist of named integer constants. They provide a way to define symbolic names for integral values, making the code more readable and maintainable. Each enumerator in an enum has a default value starting from 0, but it can be explicitly assigned a different value.

21. **When should we use the register storage specifier?**
    The `register` storage specifier hints the compiler to store the variable in a CPU register for faster access. However, modern compilers are proficient in optimizing register usage, so explicitly using `register` may not provide significant performance benefits. It's often best to rely on compiler optimizations and reserve the use of `register` for cases where profiling indicates a performance bottleneck.

### Intermediate C Concepts

22. **Specify different types of decision control statements?**
    Decision control statements in C include:
    - `if`: Executes a block of code based on a condition.
    - `else if`: Allows chaining multiple conditions after an initial `if

` statement.
    - `else`: Executes a block of code if the preceding conditions are false.
    - `switch`: Allows multi-way branching based on the value of an expression.

23. **What is an r-value and l-value?**
    - L-value: An expression that represents an object stored in memory and can appear on the left side of an assignment. Examples include variables, array elements, and dereferenced pointers.
    - R-value: An expression that represents a value rather than an address. It can appear on the right side of an assignment. Examples include literals, constants, and the results of expressions.

24. **What is the difference between `malloc()` and `calloc()`?**
    - `malloc()`: Allocates a block of memory of a specified size but does not initialize the memory contents. The allocated memory may contain garbage values.
    - `calloc()`: Allocates a block of memory of a specified size and initializes all the bytes to zero. It takes two arguments: the number of elements and the size of each element.

25. **What is the difference between `struct` and `union` in C?**
    - `struct`: A user-defined data type that allows bundling different types of data under a single name. Each member of a struct has its own memory location, and the total memory occupied by a struct is the sum of its members' sizes.
    - `union`: Similar to a struct, but all members share the same memory location. Unions are useful when different types of data need to be stored in the same memory location to conserve memory.

26. **What is call by reference in functions?**
    Call by reference in C refers to passing the memory address of a variable to a function parameter rather than passing its value. This allows the function to modify the original variable directly, as it operates on the memory location where the variable is stored.

27. **What is pass by reference in functions?**
    Pass by reference is another term for call by reference. It means passing the reference (memory address) of a variable to a function parameter, allowing the function to directly manipulate the original variable.

28. **What is a memory leak? How to avoid it?**
    A memory leak occurs when a program allocates memory dynamically but fails to deallocate it properly, resulting in unreleased memory that cannot be accessed or reclaimed. To avoid memory leaks, ensure that every dynamically allocated memory block is freed using functions like `free()` when it is no longer needed.

29. **What is Dynamic memory allocation in C? Name the dynamic allocation functions.**
    Dynamic memory allocation in C allows programs to allocate memory dynamically at runtime. The primary functions for dynamic memory allocation are:
    - `malloc()`: Allocates a block of memory of a specified size.
    - `calloc()`: Allocates a block of memory and initializes it to zero.
    - `realloc()`: Resizes a previously allocated block of memory.
    - `free()`: Deallocates a block of dynamically allocated memory.

30. **What is typedef?**
    `typedef` is a keyword in C used to create an alias or synonym for a data type. It allows defining custom names for existing data types, making code more readable and providing abstraction from implementation details.

31. **Why is it usually a bad idea to use `gets()`? Suggest a workaround.**
    Using `gets()` is discouraged because it does not perform bounds checking, leading to buffer overflows and potential security vulnerabilities. Instead, use safer alternatives like `fgets()` which allows specifying the maximum number of characters to read.

32. **What is the difference between `#include "..."` and `#include <...>`?**
    - `#include "..."`: Searches for the header file in the current directory first and then in the standard system directories.
    - `#include <...>`: Searches for the header file only in the standard system directories.

33. **What are dangling pointers? How are dangling pointers different from memory leaks?**
    - Dangling pointers: Pointers that reference memory that has been deallocated or no longer valid. Accessing a dangling pointer can lead to undefined behavior or crashes.
    - Memory leaks: Unreleased memory that cannot be accessed or reclaimed, resulting in wasted system resources. Dangling pointers and memory leaks are related but distinct issues.

34. **What is the difference between ‘g’ and “g” in C?**
    In C, both single quotes (`'`) and double quotes (`"`) are used to denote character and string literals, respectively. Single quotes are used for single characters, while double quotes are used for strings (sequences of characters).

35. **What is a near pointer and a far pointer in C?**
    Near pointers and far pointers are terms related to segmented memory models in older versions of C. They distinguish between pointers that operate within a single segment (near pointers) and pointers that span multiple segments (far pointers). In modern memory models like flat memory, these distinctions are no longer relevant.

36. **Which structure is used to link the program and the operating system?**
    The linker is the component of the compiler toolchain responsible for linking together various object files and libraries to produce the final executable program. It resolves external references, combines code and data sections, and generates the necessary information for the operating system to load and execute the program.

37. **Suppose a global variable and local variable have the same name. Is it possible to access a global variable from a block where local variables are defined?**
    Yes, it

 is possible to access the global variable from within a block where local variables with the same name are defined. However, the local variable will take precedence over the global variable within the scope of the block.

38. **Which is better `#define` or `enum`?**
    The choice between `#define` and `enum` depends on the specific use case and programming style.
    - `#define`: Provides a simple text substitution mechanism for defining constants and macros. It is more flexible but lacks type safety.
    - `enum`: Defines symbolic names for integral values, enhancing readability and type safety. Enums are preferred when defining a set of related constants with a clear hierarchy.

### Advanced C Concepts

39. **How can you remove duplicates in an array?**
    To remove duplicates from an array, you can use various approaches such as sorting the array and then removing adjacent duplicates, using a hash set to track unique elements, or employing bitwise operations for space-efficient solutions.

40. **Can we compile a program without a `main()` function?**
    No, a C program must have a `main()` function as the entry point for execution. Compilers expect to find a `main()` function to begin program execution.

41. **Write a program to get the higher and lower nibble of a byte without using shift operator?**
    One possible solution without using shift operators involves using bitwise AND and OR operations to extract the higher and lower nibbles of a byte.

```c
#include <stdio.h>

int main() {
    unsigned char byte = 0xAB;
    unsigned char higherNibble = byte & 0xF0; // Masking to extract higher nibble
    unsigned char lowerNibble = byte & 0x0F;  // Masking to extract lower nibble
    
    printf("Higher nibble: %02X\n", higherNibble);
    printf("Lower nibble: %02X\n", lowerNibble);
    
    return 0;
}
```

42. **How do you override a defined macro?**
    Macros in C can be redefined using `#undef` followed by `#define`. This allows overriding or redefining existing macros in the code.

```c
#include <stdio.h>

#define PI 3.14159

#undef PI
#define PI 3.14

int main() {
    printf("PI: %f\n", PI); // Output: PI: 3.14
    return 0;
}
```

43. **Write a C program to check if it is a palindrome number or not using a recursive method.**
    Here's a recursive solution to check if a number is a palindrome:

```c
#include <stdio.h>

int isPalindrome(int num, int originalNum) {
    if (num == 0)
        return originalNum;
    originalNum = isPalindrome(num / 10, originalNum);
    if (num % 10 != originalNum % 10)
        return -1;
    return originalNum / 10;
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    int result = isPalindrome(num, num);
    if (result == num)
        printf("Palindrome\n");
    else
        printf("Not a Palindrome\n");
    return 0;
}
```

44. **C program to check the given number format is in binary or not.**
    Here's a program to check if a given number format is binary or not:

```c
#include <stdio.h>
#include <stdbool.h>
#include <string.h>

bool isBinary(const char *str) {
    for (int i = 0; i < strlen(str); i++) {
        if (str[i] != '0' && str[i] != '1')
            return false;
    }
    return true;
}

int main() {
    char str[100];
    printf("Enter a number: ");
    scanf("%s", str);
    if (isBinary(str))
        printf("Binary format\n");
    else
        printf("Not in Binary format\n");
    return 0;
}
```

45. **C Program to find a sum of digits of a number using recursion.**
    Here's a recursive program to find the sum of digits of a number:

```c
#include <stdio.h>

int sumOfDigits(int num) {
    if (num == 0)
        return 0;
    return (num % 10) + sumOfDigits(num / 10);
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    printf("Sum of digits: %d\n", sumOfDigits(num));
    return 0;
}
```

46. **Can you tell me how to check whether a linked list is circular?**
    To check if a linked list is circular, you can use Floyd's cycle-finding algorithm (also known as the "tortoise and hare" algorithm). This algorithm involves using two pointers, one moving at twice the speed of the other. If there is a cycle, the two pointers will eventually meet.

```c
#include <stdio.h>
#include <stdbool.h>

struct Node {
    int data;
    struct Node *next;
};

bool isCircular(struct Node *head) {
    if (head == NULL)
        return false;
    struct Node *slow = head;
    struct Node *fast = head;
    while (fast != NULL && fast->next != NULL) {
        slow = slow->next;
        fast = fast->next->next;
        if (slow == fast)
            return true; // Circular
    }
    return false; // Not circular
}

int main() {
    struct Node *head = NULL;
    // Build your linked list here...
    if (isCircular(head))
        printf("Linked list is circular\n");
    else
        printf("Linked list is not circular\n");
    return 0;
}
```

47. **What is the use of a semicolon (;) at the end of every program statement?**
    In C, the semicolon (`;`) is used to terminate statements. It serves as a delimiter to mark the end of a statement and separate multiple statements within a program. Omitting the semicolon or using it incorrectly can lead to syntax errors during compilation.

48. **How to call a function before `main()`?**
    In C, you cannot directly call a function before `main()` as the execution of a C program always starts from the `main()` function. However, you can use function prototypes or declarations to declare the function before `main()` and define it later in the code.

```c
#include <stdio.h>

void function(); // Function declaration

int main() {
    function(); // Call function
    return 0;
}

void function() {
    printf("Function called\n");
}
```

49. **Differentiate between the macros and the functions.**
    - Macros: Defined using `#define`, provide text substitution, processed by the preprocessor, no type checking, faster execution, no side effects with multiple evaluations.
    - Functions: Defined using a function prototype and definition, provide code encapsulation, executed during runtime, type checking, slower execution due to function call overhead, may have side effects with multiple calls.

50. **Differentiate Source Codes from Object Codes**
    - Source code

: Human-readable code written by the programmer using a high-level programming language like C. It contains the program logic and is saved in text files with extensions like `.c`.
    - Object code: Machine-readable code generated by the compiler during the compilation process. It is in binary format and represents the translated version of the source code. Object code is saved in files with extensions like `.o` or `.obj`.

51. **What are header files and what are its uses in C programming?**
    Header files in C contain function prototypes, macro definitions, and other declarations used by multiple source files. They facilitate code organization, reuse, and modularity by providing a centralized location for common declarations. Header files typically have extensions like `.h` and are included in source files using `#include` directives.

52. **When is the "void" keyword used in a function?**
    The `void` keyword in a function declaration indicates that the function does not return any value. It is used when a function performs a task without producing a result that needs to be returned to the caller.

53. **What is dynamic data structure?**
    Dynamic data structures in C are data structures that can grow or shrink in size during program execution. Examples include linked lists, trees, and dynamic arrays. Dynamic data structures are useful when the size of the data is not known in advance or needs to change dynamically.

54. **Add Two Numbers Without Using the Addition Operator**
    One way to add two numbers without using the addition operator (`+`) is by using bitwise operators such as XOR (`^`) and AND (`&`).

```c
#include <stdio.h>

int add(int a, int b) {
    while (b != 0) {
        int carry = a & b;
        a = a ^ b;
        b = carry << 1;
    }
    return a;
}

int main() {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    printf("Sum: %d\n", add(num1, num2));
    return 0;
}
```

55. **Subtract Two Numbers Without Using Subtraction Operator**
    You can subtract two numbers without using the subtraction operator (`-`) by using bitwise operators and addition.

```c
#include <stdio.h>

int subtract(int a, int b) {
    while (b != 0) {
        int borrow = (~a) & b;
        a = a ^ b;
        b = borrow << 1;
    }
    return a;
}

int main() {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d %d", &num1, &num2);
    printf("Difference: %d\n", subtract(num1, num2));
    return 0;
}
```

56. **Multiply an Integer Number by 2 Without Using Multiplication Operator**
    To multiply an integer number by 2 without using the multiplication operator (`*`), you can use left shift (`<<`) bitwise operator.

```c
#include <stdio.h>

int multiplyBy2(int num) {
    return num << 1;
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    printf("Result: %d\n", multiplyBy2(num));
    return 0;
}
```

57. **Check whether the number is EVEN or ODD, without using any arithmetic or relational operators**
    You can check whether a number is even or odd without using arithmetic or relational operators by using bitwise AND operator.

```c
#include <stdio.h>

int isEven(int num) {
    return !(num & 1);
}

int main() {
    int num;
    printf("Enter a number: ");
    scanf("%d", &num);
    if (isEven(num))
        printf("Even\n");
    else
        printf("Odd\n");
    return 0;
}
```

58. **Reverse the Linked List**
    To reverse a linked list, you need to reverse the links between nodes.

```c
#include <stdio.h>
#include <stdlib.h>

struct Node {
    int data;
    struct Node *next;
};

void reverse(struct Node **head) {
    struct Node *prev = NULL;
    struct Node *current = *head;
    struct Node *next;
    while (current != NULL) {
        next = current->next;
        current->next = prev;
        prev = current;
        current = next;
    }
    *head = prev;
}

void printList(struct Node *node) {
    while (node != NULL) {
        printf("%d ", node->data);
        node = node->next;
    }
    printf("\n");
}

int main() {
    struct Node *head = NULL;
    head = (struct Node *)malloc(sizeof(struct Node));
    head->data = 1;
    head->next = (struct Node *)malloc(sizeof(struct Node));
    head->next->data = 2;
    head->next->next = (struct Node *)malloc(sizeof(struct Node));
    head->next->next->data = 3;
    head->next->next->next = NULL;
    printf("Original linked list: ");
    printList(head);
    reverse(&head);
    printf("Reversed linked list: ");
    printList(head);
    return 0;
}
```

59. **Check for Balanced Parentheses using Stack**
    To check for balanced parentheses using a stack, iterate through the string and push opening parentheses onto the stack. When a closing parenthesis is encountered, pop the stack and check if it matches the corresponding opening parenthesis.

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>
#include <string.h>

#define MAX_SIZE 100

struct Stack {
    int top;
    char items[MAX_SIZE];
};

void push(struct Stack *stack, char item) {
    if (stack->top == MAX_SIZE - 1

) {
        printf("Stack Overflow\n");
        exit(EXIT_FAILURE);
    }
    stack->items[++stack->top] = item;
}

char pop(struct Stack *stack) {
    if (stack->top == -1) {
        printf("Stack Underflow\n");
        exit(EXIT_FAILURE);
    }
    return stack->items[stack->top--];
}

bool isMatchingPair(char left, char right) {
    if (left == '(' && right == ')')
        return true;
    if (left == '[' && right == ']')
        return true;
    if (left == '{' && right == '}')
        return true;
    return false;
}

bool isBalanced(char *expression) {
    struct Stack stack;
    stack.top = -1;
    for (int i = 0; i < strlen(expression); i++) {
        if (expression[i] == '(' || expression[i] == '[' || expression[i] == '{')
            push(&stack, expression[i]);
        else if (expression[i] == ')' || expression[i] == ']' || expression[i] == '}') {
            if (stack.top == -1 || !isMatchingPair(pop(&stack), expression[i]))
                return false;
        }
    }
    return stack.top == -1; // Stack should be empty for balanced expression
}

int main() {
    char expression[MAX_SIZE];
    printf("Enter expression: ");
    fgets(expression, MAX_SIZE, stdin);
    if (isBalanced(expression))
        printf("Balanced\n");
    else
        printf("Not balanced\n");
    return 0;
}
```

60. **Program to find nth Fibonacci number**
    The nth Fibonacci number can be calculated using either recursion or iteration.

```c
#include <stdio.h>

int fibonacci(int n) {
    if (n <= 1)
        return n;
    return fibonacci(n - 1) + fibonacci(n - 2);
}

int main() {
    int n;
    printf("Enter value of n: ");
    scanf("%d", &n);
    printf("Fibonacci(%d) = %d\n", n, fibonacci(n));
    return 0;
}
```

61. **Write a program to find the node at which the intersection of two singly linked lists begins.**
    To find the intersection point of two singly linked lists, you can use a hash set to store visited nodes of one list and check for intersection in the second list.

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>

struct ListNode {
    int val;
    struct ListNode *next;
};

struct ListNode *getIntersectionNode(struct ListNode *headA, struct ListNode *headB) {
    if (headA == NULL || headB == NULL)
        return NULL;
    struct ListNode *ptrA = headA;
    struct ListNode *ptrB = headB;
    while (ptrA != ptrB) {
        ptrA = (ptrA == NULL) ? headB : ptrA->next;
        ptrB = (ptrB == NULL) ? headA : ptrB->next;
    }
    return ptrA;
}

int main() {
    // Construct linked lists and find intersection node
    return 0;
}
```

62. **Merge Two sorted Linked List**
    To merge two sorted linked lists, you can traverse both lists simultaneously and compare nodes to build the merged list.

```c
#include <stdio.h>
#include <stdlib.h>

struct ListNode {
    int val;
    struct ListNode *next;
};

struct ListNode *mergeTwoLists(struct ListNode *l1, struct ListNode *l2) {
    struct ListNode dummy;
    struct ListNode *tail = &dummy;
    dummy.next = NULL;
    while (l1 != NULL && l2 != NULL) {
        if (l1->val <= l2->val) {
            tail->next = l1;
            l1 = l1->next;
        } else {
            tail->next = l2;
            l2 = l2->next;
        }
        tail = tail->next;
    }
    tail->next = (l1 != NULL) ? l1 : l2;
    return dummy.next;
}

int main() {
    // Construct linked lists and merge them
    return 0;
}
```

### Memory Management

**63. Difference between memory allocation on the stack and heap:**
In C, memory allocation can be done either on the stack or the heap. The stack is a region of memory that stores local variables and function call information. It operates in a last-in-first-out (LIFO) manner, meaning the most recently allocated memory is the first to be deallocated. Stack memory is limited in size and generally fixed.

Heap memory, on the other hand, is a larger pool of memory that can be dynamically allocated and deallocated during program execution. Heap memory is more flexible than stack memory and can grow and shrink as needed. However, managing heap memory requires explicit allocation and deallocation using functions like `malloc()` and `free()`, which can lead to memory leaks if not handled properly.

**64. Handling memory allocation errors:**
When dealing with memory allocation errors, such as a failure of `malloc()`, it's important to check the return value of the allocation function to see if it returns `NULL`, indicating failure. If `malloc()` fails to allocate memory, you can handle the error by either exiting the program gracefully or taking alternative actions depending on the context. For example:

```c
int *ptr = malloc(sizeof(int));
if (ptr == NULL) {
    fprintf(stderr, "Memory allocation failed\n");
    exit(EXIT_FAILURE);
}
```

**65. Techniques for preventing memory leaks:**
Memory leaks occur when dynamically allocated memory is not deallocated properly, leading to a gradual loss of available memory. To prevent memory leaks, it's essential to free dynamically allocated memory when it's no longer needed. Some techniques for preventing memory leaks include:

- Keeping track of all dynamically allocated memory and ensuring it is freed before the program exits.
- Using tools like Valgrind to detect memory leaks during runtime.
- Following best practices such as allocating memory only when necessary, freeing memory as soon as it's no longer needed, and avoiding unnecessary dynamic memory allocations.

**66. Best practices for memory management in C:**
Some best practices for memory management in C include:

- Always initialize pointers after declaration.
- Check the return value of memory allocation functions (`malloc()`, `calloc()`) for errors.
- Free dynamically allocated memory using `free()` when it's no longer needed.
- Avoid memory leaks by keeping track of allocated memory and ensuring proper deallocation.
- Use stack memory for small, temporary variables whenever possible to avoid unnecessary heap allocations.
- Minimize the scope of variables to limit their lifetime and improve memory management.
- Use tools like Valgrind for memory debugging and profiling.

### Advanced Data Structures

**67. Self-balancing binary search trees:**
Self-balancing binary search trees are binary search trees that automatically adjust their structure to ensure that the tree remains balanced. Two commonly used self-balancing binary search trees are AVL trees and red-black trees. These trees maintain a balance criterion, such as ensuring that the heights of the left and right subtrees of any node differ by at most one (for AVL trees) or adhering to specific coloring rules (for red-black trees). This balancing ensures efficient operations like insertion, deletion, and search with logarithmic time complexity.

**68. Implementation of a hash table in C:**
A hash table is a data structure that stores key-value pairs, allowing for efficient insertion, deletion, and retrieval of values based on keys. To implement a hash table in C, you typically need an array of linked lists (buckets), where each bucket stores key-value pairs with the same hash value. Here's a basic outline of how to implement a hash table:

```c
#define SIZE 100 // Size of the hash table array

typedef struct Node {
    int key;
    int value;
    struct Node* next;
} Node;

Node* hashTable[SIZE];

// Hash function to map keys to indices
int hash(int key) {
    return key % SIZE;
}

// Function to insert a key-value pair into the hash table
void insert(int key, int value) {
    int index = hash(key);
    Node* newNode = malloc(sizeof(Node));
    newNode->key = key;
    newNode->value = value;
    newNode->next = NULL;

    // Insert at the beginning of the linked list
    newNode->next = hashTable[index];
    hashTable[index] = newNode;
}

// Function to retrieve the value associated with a key
int get(int key) {
    int index = hash(key);
    Node* current = hashTable[index];
    while (current != NULL) {
        if (current->key == key) {
            return current->value;
        }
        current = current->next;
    }
    return -1; // Key not found
}

// Other hash table operations such as delete can be implemented similarly
```

**69. Common operations on graphs:**
Graphs are versatile data structures used to model relationships between entities. Some common operations on graphs include:

- Depth-First Search (DFS): Visit each vertex and explore as far as possible along each branch before backtracking.
- Breadth-First Search (BFS): Visit each neighbor of the current vertex before moving on to the next level of neighbors.
- Time and space complexity for DFS and BFS depend on the graph representation (e.g., adjacency list or matrix) and the number of vertices and edges.

**70. Scenarios for using custom data structures:**
Custom data structures might be beneficial over standard library options in scenarios where specific requirements or performance considerations come into play. For example:

- When the standard library options don't meet the specific needs of the application.
- When performance optimizations are required for a particular use case.
- When there's a need for specialized data structures tailored to the problem domain.

### Open Ended/Problem Solving

**71. Design a function to reverse a string in-place (without allocating additional memory):**

To reverse a string in-place means to modify the string itself without allocating extra memory for another string to hold the reversed characters. We can achieve this by swapping characters from both ends of the string until we reach the middle.

Here's a function to reverse a string in-place:

```c
#include <stdio.h>
#include <string.h>

void reverseString(char *str) {
    int length = strlen(str);
    for (int i = 0; i < length / 2; i++) {
        char temp = str[i];
        str[i] = str[length - i - 1];
        str[length - i - 1] = temp;
    }
}

int main() {
    char str[] = "Hello, World!";
    printf("Original string: %s\n", str);
    reverseString(str);
    printf("Reversed string: %s\n", str);
    return 0;
}
```

Time Complexity: The time complexity of this function is O(n), where 'n' is the length of the input string. This is because we iterate through half of the string (up to the middle) and perform constant time operations (swapping characters).

**72. Write a C program to find the longest common subsequence of two strings:**

A common subsequence of two strings is a sequence of characters that appear in the same order in both strings, but not necessarily consecutively. We can use dynamic programming to find the longest common subsequence (LCS) of two strings efficiently.

Here's an implementation using dynamic programming:

```c
#include <stdio.h>
#include <string.h>

int max(int a, int b) {
    return (a > b) ? a : b;
}

int longestCommonSubsequence(char *X, char *Y, int m, int n) {
    int LCS[m + 1][n + 1];
    for (int i = 0; i <= m; i++) {
        for (int j = 0; j <= n; j++) {
            if (i == 0 || j == 0)
                LCS[i][j] = 0;
            else if (X[i - 1] == Y[j - 1])
                LCS[i][j] = LCS[i - 1][j - 1] + 1;
            else
                LCS[i][j] = max(LCS[i - 1][j], LCS[i][j - 1]);
        }
    }
    return LCS[m][n];
}

int main() {
    char X[] = "AGGTAB";
    char Y[] = "GXTXAYB";
    int m = strlen(X);
    int n = strlen(Y);
    printf("Length of Longest Common Subsequence: %d\n", longestCommonSubsequence(X, Y, m, n));
    return 0;
}
```

Time Complexity: The time complexity of this solution is O(m * n), where 'm' and 'n' are the lengths of the input strings 'X' and 'Y', respectively. This is because we fill in a dynamic programming table of size (m+1) x (n+1) and perform constant time operations for each cell.

**73. Implement a simple LRU (Least Recently Used) cache eviction policy:**

LRU cache eviction policy removes the least recently used items from the cache when it is full and a new item needs to be inserted. We can implement this using a combination of a doubly linked list and a hashmap.

Here's how it works:
- We maintain a doubly linked list to keep track of the order in which items are accessed, with the most recently accessed item at the front of the list and the least recently accessed item at the end.
- We use a hashmap to store the keys and pointers to the corresponding nodes in the doubly linked list for fast access.
- When a new item is accessed, we check if it exists in the hashmap. If it does, we move the corresponding node to the front of the list to indicate that it's the most recently used item. If it doesn't, we insert the item at the front of the list and add it to the hashmap. If the cache is full, we remove the least recently used item from the end of the list and the hashmap.

Here's a simple implementation of an LRU cache in C:

```c
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>

#define CACHE_SIZE 3

typedef struct Node {
    int key;
    int value;
    struct Node *prev;
    struct Node *next;
} Node;

typedef struct {
    Node *head;
    Node *tail;
    int size;
} LRUCache;

LRUCache* createLRUCache() {
    LRUCache *cache = (LRUCache*)malloc(sizeof(LRUCache));
    cache->head = NULL;
    cache->tail = NULL;
    cache->size = 0;
    return cache;
}

Node* createNode(int key, int value) {
    Node *node = (Node*)malloc(sizeof(Node));
    node->key = key;
    node->value = value;
    node->prev = NULL;
    node->next = NULL;
    return node;
}

void moveToFront(LRUCache *cache, Node *node) {
    if (node == cache->head) {
        return; // Node is already at the front
    }
    if (node == cache->tail) {
        cache->tail = node->prev;
        cache->tail->next = NULL;
    } else {
        node->next->prev = node->prev;
        node->prev->next = node->next;
    }
    node->next = cache->head;
    node->prev = NULL;
    cache->head->prev = node;
    cache->head = node;
}

void evictLRU(LRUCache *cache) {
    if (cache->size == 0) {
        return;
    }
    Node *temp = cache->tail;
    cache->tail = cache->tail->prev;
    if (cache->tail != NULL) {
        cache->tail->next = NULL;
    }
    free(temp);
    cache->size--;
}

int getValue(LRUCache *cache, int key) {
    // Search for the key in the hashmap
    // If found, move the corresponding node to the front of the list
    // Return the value
}

void setValue(LRUCache *cache, int key, int value) {
    // If the key exists in the hashmap, update the value and move the corresponding node to the front of the list
    // If the key doesn't exist and the cache is full, evict the least recently used item
    // Insert the new item at the front of the list and add it to the hashmap
}

void printLRUCache(LRUCache *cache) {
    Node *current = cache->head;
    while (current != NULL) {
        printf("(%d, %d) ", current->key, current->value);
        current = current->next;
    }
    printf("\n");
}

int main() {
    LRUCache *cache = createLRUCache();

    setValue(cache, 1, 10);
    setValue(cache, 2, 20);
    setValue(cache, 3, 30);
    printLRUCache(cache); // Output: (3, 30) (2, 20) (1, 10)

    setValue(cache, 4, 40); // Evict (1, 10)
    printLRUCache(cache); // Output: (4, 40) (3, 30) (2, 20)

    setValue(cache, 5, 50); // Evict (2, 20)
    printLRUCache(cache); // Output: (5, 50) (4, 40) (3, 30)

    return 0;
}
```

Time Complexity: The time complexity of accessing and updating items in the LRU cache is O(1) on average, as we use a hashmap for fast access and a doubly linked list for efficient manipulation of the most recently accessed items.

**74. Describe an approach for compressing a large text file in C:**

Text file compression aims to reduce the size of a file by encoding its contents using fewer bits. One common approach for compressing text files is using techniques like Huffman coding or Run-Length Encoding (RLE).

Here's a high-level overview of how you could implement compression using Run-Length Encoding (RLE) in C:

1. **Read the text file:** Begin by reading the contents of the text file character by character.

2. **Run-Length Encoding (RLE):** Perform Run-Length Encoding on the text data. RLE replaces sequences of repeating characters with a single character followed by the count of how many times it repeats.

   For example:
   ```
   Original text: AAAABBBCCCCDDDD
   Compressed text: A4B3C4D4
   ```

3. **Write compressed data to a new file:** After compressing the text using RLE, write the compressed data to a new file.

4. **Optional:** You can also use additional techniques like Huffman coding for further compression if needed.

Here's a basic example of how you could implement Run-Length Encoding (RLE) compression in C:

```c
#include <stdio.h>

void compressFile(FILE *inputFile, FILE *outputFile) {
    char prevChar, currentChar;
    int count = 1;

    // Read the first character from the input file
    prevChar = fgetc(inputFile);

    // Read characters until end of file
    while ((currentChar = fgetc(inputFile)) != EOF) {
        if (currentChar == prevChar) {
            // Increment count if current character is the same as the previous one
            count++;
        } else {
            // Write compressed data to output file
            fprintf(outputFile, "%c%d", prevChar, count);

            // Reset count for the new character
            count = 1;
        }
        // Update previous character
        prevChar = currentChar;
    }
    // Write compressed data for the last character
    fprintf(outputFile, "%c%d", prevChar, count);
}

int main() {
    FILE *inputFile, *outputFile;
    inputFile = fopen("input.txt", "r");
    outputFile = fopen("output.txt", "w");

    if (inputFile == NULL || outputFile == NULL) {
        printf("Error opening files!\n");
        return 1;
    }

    compressFile(inputFile, outputFile);

    printf("Compression successful!\n");

    fclose(inputFile);
    fclose(outputFile);
    return 0;
}
```

Time Complexity: The time complexity of Run-Length Encoding (RLE) compression depends on the size of the input text file. In the worst-case scenario, where there are no repeating characters, the time complexity is O(n), where 'n' is the number of characters in the input file. However, if there are repeating characters, the time complexity can be less than O(n) as the algorithm skips repeating characters.

This basic implementation demonstrates how Run-Length Encoding (RLE) can be used to compress a text file in C.

### Additional Questions for TCS Interviews

**75. Explain the concept of the "volatile" keyword in C:**

The `volatile` keyword in C is used to indicate that a variable may be changed at any time by external factors not directly associated with the program's execution. It informs the compiler that the variable's value can be modified unexpectedly, such as by hardware interrupts, other threads, or memory-mapped I/O operations.

When a variable is declared as `volatile`, the compiler is instructed to avoid performing certain optimizations that might assume the variable's value remains unchanged between successive accesses. This ensures that reads and writes to the variable are performed as specified in the program, without any optimizations that could lead to incorrect behavior.

Here's an example demonstrating the usage of `volatile`:

```c
#include <stdio.h>

int main() {
    volatile int sensorValue; // Declare a volatile variable
    
    while (1) {
        // Read sensor value from hardware
        sensorValue = readSensor();
        
        // Perform some operations
        // ...
        
        printf("Sensor value: %d\n", sensorValue);
    }
    
    return 0;
}
```

In this example, `sensorValue` is declared as `volatile` because its value can change asynchronously due to external factors (e.g., hardware interrupts). By using `volatile`, we ensure that the compiler doesn't optimize away reads or reorder memory accesses, guaranteeing that the most up-to-date value of `sensorValue` is always used.

**76. How can you achieve polymorphism in C:**

In C, polymorphism can be achieved through function pointers and structures. Here's a basic example:

```c
#include <stdio.h>

// Define a structure representing a shape
typedef struct {
    void (*draw)(void); // Function pointer to draw the shape
} Shape;

// Functions to draw different shapes
void drawCircle() {
    printf("Drawing a circle\n");
}

void drawSquare() {
    printf("Drawing a square\n");
}

int main() {
    Shape circle = { drawCircle }; // Create a circle object
    Shape square = { drawSquare }; // Create a square object

    // Draw the shapes polymorphically
    circle.draw(); // Output: Drawing a circle
    square.draw(); // Output: Drawing a square

    return 0;
}
```

In this example, we define a `Shape` structure containing a function pointer `draw` that points to a function responsible for drawing the shape. By assigning different drawing functions to the `draw` function pointer, we achieve polymorphism, where the same function call (`draw`) produces different behavior depending on the type of object it operates on.

**77. What are bitwise operators and how are they used in C:**

Bitwise operators in C perform operations on individual bits of integers. They are commonly used for tasks such as bit manipulation, setting or clearing specific bits, and performing bitwise logic operations (AND, OR, XOR).

Here are the bitwise operators in C:

- `&` (Bitwise AND): Performs a bitwise AND operation between corresponding bits of two operands.
- `|` (Bitwise OR): Performs a bitwise OR operation between corresponding bits of two operands.
- `^` (Bitwise XOR): Performs a bitwise XOR (exclusive OR) operation between corresponding bits of two operands.
- `~` (Bitwise NOT): Flips the bits of its operand, changing 1 to 0 and 0 to 1.
- `<<` (Left shift): Shifts the bits of the left operand to the left by the number of positions specified by the right operand.
- `>>` (Right shift): Shifts the bits of the left operand to the right by the number of positions specified by the right operand.

Here's an example demonstrating the usage of bitwise operators:

```c
#include <stdio.h>

int main() {
    unsigned int a = 5; // 101 in binary
    unsigned int b = 3; // 011 in binary

    // Bitwise AND
    unsigned int result_and = a & b; // 101 & 011 = 001 (1 in decimal)
    printf("Bitwise AND: %u\n", result_and);

    // Bitwise OR
    unsigned int result_or = a | b; // 101 | 011 = 111 (7 in decimal)
    printf("Bitwise OR: %u\n", result_or);

    // Bitwise XOR
    unsigned int result_xor = a ^ b; // 101 ^ 011 = 110 (6 in decimal)
    printf("Bitwise XOR: %u\n", result_xor);

    // Bitwise NOT
    unsigned int result_not = ~a; // ~101 = 11111111 11111111 11111111 11111010 (4294967290 in decimal)
    printf("Bitwise NOT: %u\n", result_not);

    // Left shift
    unsigned int result_left_shift = a << 1; // 101 << 1 = 1010 (10 in decimal)
    printf("Left shift: %u\n", result_left_shift);

    // Right shift
    unsigned int result_right_shift = a >> 1; // 101 >> 1 = 10 (2 in decimal)
    printf("Right shift: %u\n", result_right_shift);

    return 0;
}
```

**78. Explain the difference between `struct` and `typedef struct`:**

In C, `struct` is used to define a structure type, which is a collection of variables (members) grouped together under a single name. `typedef struct`, on the other hand, combines the declaration of a structure with the creation of a typedef alias for that structure type.

Here's an example illustrating the difference:

```c
#include <stdio.h>

// Define a structure using struct keyword
struct Person {
    char name[20];
    int age;
};

// Define a structure using typedef
typedef struct {
    char name[20];
    int age;
} Person_t;

int main() {
    // Using struct keyword
    struct Person person1;
    person1.age = 25;

    // Using typedef
    Person_t person2;
    person2.age = 30;

    printf("Person 1 age: %d\n", person1.age); // Output: 25
    printf("Person 2 age: %d\n", person2.age); // Output: 30

    return 0;
}
```

In the example above, both `struct Person` and `Person_t` define a structure with the same members (`name` and `age`). However, `typedef struct` allows us to define the structure and create an alias (`Person_t`) simultaneously, making the code cleaner and easier to read.

Absolutely! Let's proceed with the remaining questions:

**79. What is the significance of the `static` keyword in C:**

The `static` keyword in C has several different uses depending on its context:

- **Static variables inside functions:** When `static` is used with a variable inside a function, it makes the variable retain its value between function calls. These variables are initialized only once and persist throughout the program's execution.

- **Static variables outside functions:** When `static` is used with a global variable (outside any function), it limits the variable's scope to the file in which it is declared. It cannot be accessed from other files using the `extern` keyword.

- **Static functions:** When `static` is used with a function declaration, it limits the function's scope to the file in which it is declared. Static functions cannot be called from other files using the `extern` keyword.

- **Static local variables:** When `static` is used with a local variable inside a function, it makes the variable retain its value between function calls, similar to static variables inside functions. However, static local variables have a narrower scope than non-static local variables; they are only accessible within the block in which they are declared.

Here's an example demonstrating the use of static variables inside functions:

```c
#include <stdio.h>

void increment() {
    static int count = 0;
    count++;
    printf("Count: %d\n", count);
}

int main() {
    increment(); // Output: Count: 1
    increment(); // Output: Count: 2
    increment(); // Output: Count: 3
    return 0;
}
```

In this example, the static variable `count` retains its value between calls to the `increment` function, allowing us to maintain state across multiple function invocations.

**80. Write a C program to sort an array using bubble sort:**

Bubble sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. Here's an implementation of bubble sort in C:

```c
#include <stdio.h>

void bubbleSort(int arr[], int n) {
    for (int i = 0; i < n - 1; i++) {
        for (int j = 0; j < n - i - 1; j++) {
            if (arr[j] > arr[j + 1]) {
                // Swap arr[j] and arr[j + 1]
                int temp = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = temp;
            }
        }
    }
}

int main() {
    int arr[] = {64, 34, 25, 12, 22, 11, 90};
    int n = sizeof(arr) / sizeof(arr[0]);
    bubbleSort(arr, n);
    printf("Sorted array: \n");
    for (int i = 0; i < n; i++) {
        printf("%d ", arr[i]);
    }
    return 0;
}
```

This program sorts an array using the bubble sort algorithm and prints the sorted array.
The time complexity of the bubble sort algorithm, as implemented in the 80th question, is O(n^2), where 'n' is the number of elements in the array.
In bubble sort, for each element in the array, it iterates through the remaining elements and compares adjacent elements, swapping them if they are in the wrong order. This process continues until the entire array is sorted.
In the worst-case scenario, when the array is in reverse order or nearly sorted, bubble sort will require approximately n * (n - 1) / 2 comparisons and swaps to sort the array. This results in a quadratic time complexity of O(n^2).
Bubble sort is not efficient for large datasets or nearly sorted arrays due to its quadratic time complexity. However, it is simple to implement and works well for small datasets or when only a few elements are out of order.


**81. Explain the difference between `break` and `continue` statements in C:**

In C, both `break` and `continue` are control flow statements used inside loops to alter the flow of execution:

- **`break` statement:** When encountered inside a loop, the `break` statement immediately terminates the loop and transfers control to the statement following the loop.
- **`continue` statement:** When encountered inside a loop, the `continue` statement skips the remaining code in the current iteration of the loop and proceeds to the next iteration.

Here's an example illustrating the difference:

```c
#include <stdio.h>

int main() {
    // Example of break statement
    for (int i = 0; i < 5; i++) {
        if (i == 3) {
            break; // Exit the loop when i equals 3
        }
        printf("%d ", i); // Output: 0 1 2
    }

    printf("\n");

    // Example of continue statement
    for (int i = 0; i < 5; i++) {
        if (i == 2) {
            continue; // Skip printing when i equals 2
        }
        printf("%d ", i); // Output: 0 1 3 4
    }

    return 0;
}
```

In the first loop, the `break` statement causes the loop to terminate prematurely when `i` equals 3. In the second loop, the `continue` statement skips printing the value of `i` when it equals 2.

**82. How can you dynamically allocate a 2D array in C:**

To dynamically allocate a 2D array in C, you can use a pointer to pointers (double pointer) or a single pointer with contiguous memory allocation. Here's an example using a pointer to pointers:

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int rows = 3;
    int cols = 4;

    // Dynamically allocate memory for rows
    int **matrix = (int **)malloc(rows * sizeof(int *));
    if (matrix == NULL) {
        printf("Memory allocation failed\n");
        return 1;
    }

    // Dynamically allocate memory for columns of each row
    for (int i = 0; i < rows; i++) {
        matrix[i] = (int *)malloc(cols * sizeof(int));
        if (matrix[i] == NULL) {
            printf("Memory allocation failed\n");
            return 1;
        }
    }

    // Initialize and access elements
    for (int i = 0; i < rows; i++) {
        for (int j = 0; j < cols; j++) {
            matrix[i][j] = i * cols + j;
            printf("%d ", matrix[i][j]);
        }
        printf("\n");
    }

    // Free dynamically allocated memory
    for (int i = 0; i < rows; i++) {
        free(matrix[i]);
    }
    free(matrix);

    return 0;
}
```

The time complexity of bubble sort is O(n^2) in the worst-case scenario, where 'n' is the number of elements in the array. This is because bubble sort iterates through the array multiple times, and in each iteration, it compares adjacent elements and swaps them if they are in the wrong order. The worst-case scenario occurs when the array is in reverse order, requiring the maximum number of swaps to sort the array.


**83. Write a program to swap two variables without using a temporary variable:**

You can swap two variables without using a temporary variable by using arithmetic operations or bitwise XOR. Here's an example using arithmetic operations:

```c
#include <stdio.h>

int main() {
    int a = 5, b = 10;

    printf("Before swapping: a = %d, b = %d\n", a, b);

    // Swap variables without using a temporary variable
    a = a + b;
    b = a - b;
    a = a - b;

    printf("After swapping: a = %d, b = %d\n", a, b);

    return 0;
}
```

In this program, we use addition and subtraction to swap the values of `a` and `b` without using a temporary variable.

**84. What are the uses of the `const` keyword in C:**

The `const` keyword in C is used to declare constants, i.e., variables whose values cannot be changed once initialized. Here are some common uses of the `const` keyword:

- **Defining symbolic constants:** You can define symbolic constants using `const` to improve code readability and maintainability. For example:
  ```c
  const int MAX_SIZE = 100;
  ```

- **Function parameters:** Using `const` in function parameters indicates that the function does not modify the parameter's value. This allows the compiler to optimize code and catch potential errors. For example:
  ```c
  void printArray(const int arr[], int size);
  ```

- **Preventing unintended modification:** You can declare variables as `const` to prevent unintended modification of their values. This enhances code safety and readability. For example:
  ```c
  const float PI = 3.14159;
  ```

- **Pointer declarations:** You can use `const` with pointers to declare constant pointers or pointers to constant values. This enforces immutability of either the pointer itself or the value it points to. For example:
  ```c
  const int *ptr1; // Pointer to a constant integer
  int *const ptr2; // Constant pointer to an integer
  const int *const ptr3; // Constant pointer to a constant integer
  ```

The `const` keyword helps in creating safer and more maintainable code by enforcing immutability where needed.

These examples demonstrate practical uses of the `const` keyword in C programming.







###CPP


1. **What are the differences between C and C++?**
2. **Discuss the differences in memory management between C and C++.**
3. **Explain the differences in syntax and features between C and C++.**
4. **How does C++ support object-oriented programming compared to C?**
5. **Discuss the differences in error handling mechanisms between C and C++.**
6. **Explain the differences in function declaration and definition between C and C++.**
7. **What are the differences in the use of pointers between C and C++?**
8. **How does C++ support features like templates, namespaces, and exception handling that are not present in C?**
9. **Discuss the differences in the standard libraries of C and C++.**
10. **What are the differences in the approach to string handling between C and C++?**
11. **Discuss the differences in the approach to memory management, such as dynamic memory allocation, between C and C++.**
12. **How does C++ support features like constructors, destructors, and class-based encapsulation, which are not available in C?**
13. **Explain how C++ supports features like function and operator overloading, which are not available in C.**
14. **What are the differences in the approach to I/O operations between C and C++?**
15. **Discuss the differences in the approach to modular programming and code organization between C and C++.**
16. **Explain the differences in the use of libraries and header files between C and C++.**
17. **How does C++ support features like namespaces and templates, which are not available in C?**
18. **Discuss the differences in the approach to memory management, such as dynamic memory allocation and deallocation, between C and C++.**
19. **Explain how C++ supports features like classes and objects, which are not available in C.**
20. **What are the differences in the approach to error handling and exception handling between C and C++?**
21. **Discuss the differences in the approach to code organization and modularity between C and C++.**
22. **What are the differences in the approach to data abstraction and encapsulation between C and C++?**

**More C++ Interview Questions for Freshers:**

23. **What are the different data types present in C++?**
24. **What is the difference between struct and class in C++?**
25. **What is operator overloading?**
26. **What is polymorphism in C++?**
27. **Explain constructor in C++.**
28. **Tell me about virtual functions.**
29. **Compare compile-time polymorphism and runtime polymorphism.**
30. **What do you know about friend class and friend function?**
31. **What are the C++ access specifiers?**
32. **Define inline function.**
33. **What is a reference in C++?**
34. **What do you mean by abstraction in C++?**
35. **Is destructor overloading possible? If yes, then explain, and if no, then why?**
36. **What do you mean by call by value and call by reference?**
37. **What is an abstract class, and when do you use it?**
38. **What are destructors in C++?**
39. **What are static members and static member functions?**
40. **Explain inheritance.**

**C++ Interview Questions for Experienced:**

41. **What is a copy constructor?**
42. **What is the difference between shallow copy and deep copy?**
43. **What is the difference between virtual functions and pure virtual functions?**
44. **If class D is derived from a base class B, in what order would the constructors of these classes get called when creating an object of type D?**
45. **Can we call a virtual function from a constructor?**
46. **What are void pointers?**
47. **What is the 'this' pointer in C++?**
48. **How do you allocate and deallocate memory in C++?**
49. **What are smart pointers (unique_ptr, shared_ptr, weak_ptr), and why are they preferred over raw pointers?**
50. **Explain threads, processes, and their differences.**

**More C++ Interview Questions for Experienced:**

51. **What are the challenges in writing concurrent code?**
52. **Discuss some common design patterns used in C++ (e.g., Singleton, Factory, Observer).**
53. **How do design patterns improve code structure and maintainability?**
54. **What are some techniques for optimizing C++ code for performance?**
55. **Discuss the trade-offs between readability and optimization.**
56. **What are the differences between `std::vector`, `std::list`, and `std::map` containers in the STL?**
57. **Explain the concept of function overloading and provide an example.**
58. **What is the role of the `const` keyword in C++? How does it affect member functions and parameters?**
59. **What are lambda expressions in C++? How are they useful?**
60. **Discuss the differences between `std::unique_ptr`, `std::shared_ptr`, and `std::weak_ptr`. When would you use each?**
61. **Explain the concept of multiple inheritance in C++. What are its advantages and disadvantages?**
62. **What is the purpose of the `mutable` keyword in C++? Provide an example.**
63. **Discuss the differences between the `static_cast`, `dynamic_cast`, and `const_cast` casts in C++. When would you use each?**
64. **Explain the role of the `volatile` keyword in C++. When is it used?**
65. **What are the differences between `std::mutex`, `std::recursive_mutex`, and `std::timed_mutex`? When would you use each for synchronization?**
66. **What are the advantages and disadvantages of using exceptions for error handling in C++?**
67. **Explain the concept of move semantics in C++. How does it improve performance compared to copy semantics?**
68. **Discuss the differences between the `std::map` and `std::unordered_map` containers in the STL. When would you choose one over the other?**
69. **What are the differences between the `std::function` and function pointers in C++? When would you use each?**


**More C++ Interview Questions for Experienced:**

70. **Explain the role of the `nullptr` keyword in C++. How does it differ from `NULL` and `0`?**
71. **What are the differences between C++11 and previous versions of C++?**
72. **Discuss the features introduced in C++11, C++14, and C++17.**
73. **Explain the concept of lambda capture in C++.**
74. **What are the benefits of using `constexpr` functions in C++?**
75. **Discuss the differences between `std::array` and built-in arrays in C++.**
76. **Explain the usage of the `auto` keyword in C++11.**
77. **What is the purpose of the `override` keyword in C++11?**
78. **Discuss the usage of range-based for loops in C++.**
79. **Explain the concept of `decltype` in C++.**
80. **What are the advantages of using `std::array` over `std::vector` in certain scenarios?**
81. **Discuss the differences between `std::unique_lock` and `std::lock_guard`.**
82. **Explain the usage of the `noexcept` specifier in C++.**
83. **What is the purpose of the `final` keyword in C++11?**
84. **Discuss the role of move constructors and move assignment operators in C++11.**
85. **What is the purpose of the `explicit` keyword in C++? Provide an example.**


### OOPS


**Basic OOPs Interview Questions:**
1. **What is meant by the term OOPs?**
2. **What is the need for OOPs?**
3. **What are some major Object-Oriented Programming languages?**
4. **What are some other programming paradigms other than OOPs?**
5. **What is meant by Structured Programming?**
6. **What are the main features of OOPs?**
7. **What are some advantages of using OOPs?**
8. **Why is OOPs so popular?**

**Advanced OOPs Interview Questions:**
9. **What is a class?**
10. **What is an object?**
11. **What is encapsulation?**
12. **What is Polymorphism?**
13. **What is Compile-time Polymorphism and how is it different from Runtime Polymorphism?**
14. **How does C++ support Polymorphism?**
15. **What is meant by Inheritance?**
16. **What is Abstraction?**
17. **How much memory does a class occupy?**
18. **Is it always necessary to create objects from a class?**
19. **What is a constructor?**
20. **What are the various types of constructors in C++?**
21. **What is a copy constructor?**
22. **What is a destructor?**
23. **Are class and structure the same? If not, what's the difference between a class and a structure?**
24. **Explain Inheritance with an example?**
25. **Are there any limitations of Inheritance?**
26. **What are the various types of inheritance?**
27. **What is a subclass?**
28. **Define a superclass?**
29. **What is an interface?**
30. **What is meant by static polymorphism?**
31. **What is meant by dynamic polymorphism?**
32. **What is the difference between overloading and overriding?**
33. **How is data abstraction accomplished?**
34. **What is an abstract class?**
35. **How is an abstract class different from an interface?**
36. **What are access specifiers and what is their significance?**
37. **What is an exception?**
38. **What is meant by exception handling?**
39. **What is meant by Garbage Collection in OOPs world?**
40. **What is a friend function in C++?**
41. **What is function overloading in C++?**
42. **What is operator overloading in C++?**
43. **What is a virtual function in C++?**
44. **What is a pure virtual function in C++?**
45. **What is a virtual destructor in C++?**
46. **What is multiple inheritance in C++?**
47. **What is the `const` keyword in C++?**
48. **What are references in C++?**
49. **What is the difference between `const` and `constexpr` in C++?**
50. **What is the diamond inheritance problem in C++? How can it be resolved?**
51. **What are the four pillars of Object-Oriented Programming (OOPs)?**
52. **Can you explain each of the four pillars of OOPs (Encapsulation, Inheritance, Polymorphism, Abstraction) with examples?**
53. **How does Encapsulation contribute to better software design and maintenance?**
54. **What are the benefits of Inheritance in Object-Oriented Programming?**
55. **Explain how Polymorphism enhances code flexibility and reusability.**
56. **How does Abstraction help in managing complexity in large-scale software projects?**
57. **What is abstract class?**

### STL

**STL Data Structure Questions:**

1. **Vector:**
   - **What is a vector in the STL?**
   - **Explain the advantages of using vectors over arrays.**
   - **How do you resize a vector dynamically?**
   - **Discuss the time complexity of various operations on vectors.**

2. **List:**
   - **What is a list in the STL?**
   - **Compare and contrast lists with vectors.**
   - **Explain the advantages and disadvantages of using lists.**
   - **How do you insert and delete elements in a list?**

3. **Map:**
   - **What is a map in the STL?**
   - **How are elements stored in a map?**
   - **Discuss the time complexity of operations like insertion, deletion, and searching in a map.**
   - **Provide examples of when to use a map.**

4. **Set:**
   - **What is a set in the STL?**
   - **How are elements stored in a set?**
   - **Explain the difference between a set and a map.**
   - **Discuss the time complexity of operations like insertion, deletion, and searching in a set.**

5. **Queue:**
   - **What is a queue in the STL?**
   - **How is a queue implemented in the STL?**
   - **Discuss the operations supported by a queue.**
   - **Compare and contrast queues with other data structures like stacks and lists.**

6. **Stack:**
   - **What is a stack in the STL?**
   - **How is a stack implemented in the STL?**
   - **Discuss the operations supported by a stack.**
   - **Provide examples of when to use a stack.**

**STL Algorithm Questions:**

1. **Sorting Algorithms:**
   - **Explain the difference between stable and unstable sorting algorithms.**
   - **Discuss the implementation and time complexity of sorting algorithms like quicksort, mergesort, and heapsort.**
   - **How do you use the `std::sort` function in C++?**

2. **Searching Algorithms:**
   - **Discuss the implementation and time complexity of searching algorithms like linear search and binary search.**
   - **How do you use the `std::find` function in C++?**

3. **Iterators:**
   - **What are iterators in C++?**
   - **Explain the difference between input, output, forward, bidirectional, and random access iterators.**
   - **How do you use iterators to traverse containers like vectors and lists?**

4. **Algorithms on Containers:**
   - **How do you use algorithms like `std::copy`, `std::transform`, and `std::accumulate` in C++?**
   - **Provide examples of applying these algorithms on containers like vectors and lists.**
   - **Discuss the advantages of using algorithms from the STL over manual implementations.**

5. **Binary Search Tree (BST) Algorithms:**
   - **What is a binary search tree?**
   - **Explain how to perform operations like insertion, deletion, and searching in a binary search tree.**
   - **Discuss the advantages and disadvantages of using a BST compared to other data structures.**

### DATA STRUCTURE


**Basic Data Structure Interview Questions for Freshers:**

**Conceptual Understanding:**
1. **What are Data Structures?**
2. **Why Create Data Structures?**
3. **What are some applications of Data structures?**
4. **Explain the process behind storing a variable in memory.**
5. **Can you explain the difference between file structure and storage structure?**

**Understanding Basic Data Structures:**
6. **Describe the types of Data Structures?**
7. **What is a stack data structure? What are the applications of the stack?**
8. **What are different operations available in the stack data structure?**
9. **What is a queue data structure? What are the applications of the queue?**
10. **What are different operations available in the queue data structure?**
11. **Differentiate between stack and queue data structure.**
12. **How to implement a queue using a stack?**
13. **How do you implement stack using queues?**
14. **What is an array data structure? What are the applications of arrays?**
15. **Elaborate on different types of array data structure.**
16. **What is a linked list data structure? What are the applications for the Linked list?**
17. **Elaborate on different types of Linked List data structures?**
18. **Difference between Array and Linked List.**
19. **What is an asymptotic analysis of an algorithm?**
20. **What is hashmap in data structure?**

**Data Structure Interview Questions for Experienced:**

**Advanced Data Structures and Algorithms:**
21. **What is binary tree data structure? What are the applications for binary trees?**
22. **What is binary search tree data structure? What are the applications for binary search trees?**
23. **What are tree traversals?**
24. **What is a deque data structure and its types? What are the applications for deque?**
25. **What are some key operations performed on the Deque data structure?**
26. **What is a priority queue? What are the applications for priority queue?**
27. **Compare different implementations of the priority queue.**
28. **What is a graph data structure and its representations? What are the applications for graphs?**
29. **What is the difference between the Breadth First Search (BFS) and Depth First Search (DFS)?**
30. **What is AVL tree data structure, its operations, and its rotations? What are the applications for AVL trees?**
31. **What is a B-tree data structure? What are the applications for B-trees?**
32. **Define Segment Tree data structure and its applications.**
33. **Define Trie data structure and its applications.**
34. **Define Red-Black Tree and its applications.**
35. **Which data structures are used for implementing LRU cache?**
36. **What is a heap data structure?**
37. **What is a hash table data structure and its applications?**
38. **Describe different collision resolution techniques in hash tables.**
39. **What is the time complexity of basic operations (insertion, deletion, search) in a hash table?**
40. **Explain the concept of dynamic programming and its applications in solving problems efficiently.**

**Complex Data Structure and Algorithm Concepts:**
41. **What is a suffix tree data structure and its applications?**
42. **Discuss the advantages and disadvantages of using an array-based implementation versus a linked list-based implementation.**
43. **Explain the concept of amortized analysis in the context of data structures.**
44. **What are self-balancing binary search trees? Provide examples and explain their significance.**
45. **Describe the difference between a heap and a binary search tree.**
46. **How would you implement a stack using an array? What are the advantages and disadvantages of this approach?**
47. **What is the importance of understanding time complexity in data structure and algorithm design?**
48. **Discuss the concept of Big O notation and its relevance in analyzing algorithm efficiency.**
49. **Explain the process of tree traversal and discuss its different methods (in-order, pre-order, post-order).**
50. **What is the difference between a breadth-first search (BFS) and a depth-first search (DFS) in graph traversal?**



### DBMS


Certainly! Here's the properly indexed and formatted list of DBMS interview questions:

**Basic DBMS Interview Questions:**
1. **What is DBMS and what is its utility? Explain RDBMS with examples.**
2. **What is a database?**
3. **Mention the issues with traditional file-based systems that make DBMS a better choice?**
4. **Explain a few advantages of a DBMS.**
5. **Explain different languages present in DBMS.**
6. **What are the ACID properties in DBMS?**
7. **Are NULL values in a database the same as that of blank space or zero?**

**Intermediate DBMS Interview Questions:**
8. **What is Data Warehousing?**
9. **Explain different levels of data abstraction in a DBMS.**
10. **What is an entity-relationship (E-R) model? Explain Entity, Entity Type, and Entity Set in DBMS.**
11. **Explain different types of relationships amongst tables in a DBMS.**
12. **Explain the difference between intension and extension in a database.**
13. **Explain the difference between the DELETE and TRUNCATE command in a DBMS.**
14. **What is a lock? Explain the major difference between a shared lock and an exclusive lock during a transaction in a database.**
15. **What is normalization and denormalization?**

**Advanced DBMS Interview Questions:**
16. **Explain different types of Normalization forms in a DBMS.**
17. **Explain different types of keys in a database.**
18. **Explain the difference between a 2-tier and 3-tier architecture in a DBMS.**

**Intermediate DBMS Interview Questions:**
19. **What is a transaction? Explain the properties of a transaction.**
20. **What are the different types of JOIN operations? Explain with examples.**
21. **Explain the concept of indexing in a database and its benefits.**
22. **What are the differences between clustered and non-clustered indexes?**
23. **Explain the difference between a primary key and a foreign key.**
24. **What is a trigger in a DBMS? When and why do we use triggers?**

**Advanced DBMS Interview Questions:**
25. **Explain the CAP theorem in the context of distributed databases.**
26. **What is database partitioning? Explain its types (horizontal, vertical, sharding).**
27. **What is a deadlock in a database? How can you prevent or handle deadlocks?**
28. **Explain the different types of database recovery techniques.**
29. **What is a B+ tree? Explain its advantages over other tree structures for indexing.**

**Additional Topics Possibly Asked in TCS Prime Interview:**

**Query Optimization Techniques:**
1. **What is query optimization, and why is it important in database management?**
2. **Explain the steps involved in query optimization.**
3. **Discuss various factors that influence query performance in a database.**
4. **What are some common query optimization techniques used in relational databases?**
5. **How does the query optimizer determine the most efficient execution plan for a given query?**

**Data Mining and Data Warehousing:**
6. **Define data mining and its role in extracting meaningful patterns from large datasets.**
7. **What are the key differences between data mining and traditional statistical analysis?**
8. **Explain the process of data warehousing and its benefits in decision-making processes.**
9. **Discuss some popular data mining algorithms used for classification and clustering.**
10. **How does data mining contribute to business intelligence and predictive analytics?**

**Big Data and NoSQL Databases:**
11. **Define Big Data and discuss the challenges associated with managing and analyzing large volumes of data.**
12. **What are NoSQL databases, and how do they differ from traditional relational databases?**
13. **Discuss the advantages and disadvantages of using NoSQL databases for handling Big Data.**
14. **Explain the CAP theorem in the context of distributed NoSQL databases.**
15. **Provide examples of popular NoSQL databases and their use cases.**

**Cloud Database Management:**
16. **What is cloud database management, and how does it differ from traditional on-premises database management?**
17. **Discuss the benefits of migrating database systems to the cloud.**
18. **Explain the concepts of Database as a Service (DBaaS) and Platform as a Service (PaaS) in cloud computing.**
19. **What are some common challenges associated with cloud database management, and how can they be addressed?**
20. **Describe the security measures and compliance standards in place for ensuring data protection in cloud-based database systems.**

**Data Compression Techniques:**
21. **Define data compression and explain its importance in database management.**
22. **Discuss various data compression algorithms used in database systems.**
23. **Compare lossless and lossy data compression techniques, providing examples of each.**
24. **What are some factors to consider when selecting a data compression technique for a database system?**
25. **Explain how data compression can impact query performance and storage efficiency in a database.**

**Data Security and Encryption:**
26. **Discuss the importance of data security in database management and the potential risks of data breaches.**
27. **What are some common security threats faced by database systems, and how can they be mitigated?**
28. **Explain the concept of encryption and its role in protecting sensitive data stored in databases.**
29. **Describe the difference between encryption at rest and encryption in transit in the context of database security.**
30. **How do compliance regulations such as GDPR and HIPAA impact data security practices in database management?**

**Database Management System Architecture:**
31. **Describe the architecture of a typical database management system (DBMS), including its components and their interactions.**
32. **Explain the client-server model in database management and discuss its advantages.**
33. **What is the role of the database engine in a DBMS, and how does it interact with storage systems?**
34. **Discuss the different layers of abstraction in a database system architecture and their functions.**
35. **How does distributed database architecture differ from centralized database architecture?**

**Database Design Principles and Best Practices:**
36. **What are the key principles of good database design, and why are they important?**
37. **Discuss the process of database normalization and its significance in reducing data redundancy and improving data integrity.**
38. **Explain the concept of data modeling and the various types of data models used in database design.**
39. **What are some best practices for designing efficient database schemas and indexing strategies?**
40. **How does denormalization fit into the database design process, and when is it appropriate to denormalize a database schema?**


### Computer Network

**Basic Networking Interview Questions:**
1. **How are Network types classified?**
2. **Explain different types of networks.**
3. **Explain LAN (Local Area Network)**
4. **Tell me something about VPN (Virtual Private Network)**
5. **What are the advantages of using a VPN?**
6. **What are the different types of VPN?**
7. **What are nodes and links?**
8. **What is the network topology?**
9. **Define different types of network topology**
10. **What is an IPv4 address? What are the different classes of IPv4?**
11. **What are Private and Special IP addresses?**

**Intermediate Interview Questions:**
12. **Describe the OSI Reference Model**
13. **Define the 7 different layers of the OSI Reference Model**
14. **Describe the TCP/IP Reference Model**
15. **Define the 4 different layers of the TCP/IP Reference Model**
16. **Differentiate OSI Reference Model with TCP/IP Reference Model**
17. **What are the HTTP and the HTTPS protocol?**
18. **What is the SMTP protocol?**
19. **What is the DNS?**
20. **What is the use of a router and how is it different from a gateway?**

**Advanced Interview Questions:**
21. **What is the TCP protocol?**
22. **What is the UDP protocol?**
23. **Compare between TCP and UDP**
24. **What is the ICMP protocol?**
25. **What do you mean by the DHCP Protocol?**
26. **What is the ARP protocol?**
27. **What is the FTP protocol?**
28. **What is the MAC address and how is it related to NIC?**
29. **Differentiate the MAC address with the IP address**
30. **What is a subnet?**
31. **Compare the hub vs switch**
32. **What is the difference between the ipconfig and the ifconfig?**
33. **What is the firewall?**
34. **What are Unicasting, Anycasting, Multicasting, and Broadcasting?**
35. **What happens when you enter google.com in the web browser?**

**Additional Networking Interview Questions:**
36. **Explain the concept of subnetting and supernetting.**
37. **What is the purpose of a subnet mask?**
38. **Describe the process of subnetting a network.**
39. **What is NAT (Network Address Translation) and its types?**
40. **Explain the concept of VLAN (Virtual Local Area Network).**
41. **Describe the difference between half-duplex and full-duplex communication.**
42. **What is a MAC address table, and how does it function in a network switch?**
43. **Explain the purpose and operation of ARP (Address Resolution Protocol).**
44. **Describe the concept of CIDR (Classless Inter-Domain Routing) notation.**
45. **What is a broadcast storm, and how can it be prevented?**
46. **Explain the difference between a router and a switch.**
47. **What is a proxy server, and how does it work?**
48. **Describe the role of DHCP (Dynamic Host Configuration Protocol) in network configuration.**
49. **Explain the concept of Quality of Service (QoS) in networking.**
50. **What is a DNS cache poisoning attack, and how can it be mitigated?**
51. **Describe the advantages and disadvantages of wireless networking compared to wired networking.**
52. **Explain the purpose and operation of MAC filtering in wireless networks.**
53. **What is the purpose of a default gateway in networking?**
54. **Describe the function of a network firewall and its types.**
55. **Explain the concept of port forwarding and its use in networking.**