# 1.	#include <iostream>:
## Including the iostream Library

At the very beginning of our C++ program, we have `#include <iostream>`.  This line is crucial because it *includes* the `iostream` library `iostream` specifically provides the tools for input and output operations, like displaying text on the screen (using `cout`) and getting input from the user (using `cin`).  Without this line, we wouldn't be able to use these essential tools.
2.	using namespace std;:
## Using the Standard Namespace

`using namespace std;`.  This line tells the compiler to use the `std` (standard) namespace.  Namespaces are like containers for names.  `iostream` By using this line, we can use the names of these components (like `cout` and `cin`) directly without having to write `std::cout` and `std::cin` every time
3.	int main() 
## The Main Function: Where Execution Begins

Every C++ program *must* have a `main()` function.  This is the entry point of your program – it's where the execution begins.  The `int` before `main` indicates that the function returns an integer value.  Conventionally, a return value of 0 indicates that the program executed successfully. The curly braces `{}` enclose the code that will be executed when the program runs.
4.	cout <<:
## Displaying Output with cout

Inside the `main()` function, we often use `cout` to display output to the console (your screen).  `cout` is an object from the `iostream` library. The `<<` operator is used to "insert" data into the output stream.
endl is another useful tool from iostream. It inserts a newline character, which moves the cursor to the beginning of the next line.

5.	cin >> ...; (Input):
## Getting Input with cin

`cin` is used to get input from the user, typically from the keyboard.  It's also an object from the `iostream` library. The `>>` operator is used to extract data from the input stream.

6.	return 0; (Returning from Main):
Markdown
## Returning from Main

At the end of the `main()` function
<img width="632" alt="image" src="https://github.com/user-attachments/assets/9b759a31-9845-47ff-9095-50cb5f7338c0" />


