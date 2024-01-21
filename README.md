Monty Project
This project involves creating an interpreter for Monty ByteCodes files, which are scripts written in the Monty scripting language. The interpreter operates on a unique stack with specific instructions to manipulate it.

Learning Objectives
By completing this project, we gained knowledge and understanding of the following concepts:

General
LIFO and FIFO: The meaning of Last In, First Out (LIFO) and First In, First Out (FIFO) principles.
Stacks and Queues: What a stack and a queue are and when to use each data structure.
Implementations: Common implementations of stacks and queues.
Use Cases: The most common use cases of stacks and queues.
Global Variables: The proper way to use global variables.
Programming Skills
C Programming: Implementing functionalities in the C programming language.
Header Files: Organizing the code with header files, including prototypes for functions.
Coding Style: Following the Betty style guidelines for clean and readable code.
Memory Management: Utilizing malloc and free for dynamic memory allocation.
GitHub Usage: Managing the code in a GitHub repository, ensuring compliance with project rules.
Project Structure
The project consists of multiple tasks, each involving the implementation of specific Monty ByteCode opcodes. The tasks are as follows:

push, pall: Implement the push opcode to push elements onto the stack and the pall opcode to print all values on the stack.

pint: Implement the pint opcode to print the value at the top of the stack.

pop: Implement the pop opcode to remove the top element of the stack.

swap: Implement the swap opcode to swap the top two elements of the stack.

add: Implement the add opcode to add the top two elements of the stack.

nop: Implement the nop opcode that does nothing.

sub: Implement the sub opcode to subtract the top element from the second top element of the stack.

div: Implement the div opcode to divide the second top element by the top element of the stack.

mul: Implement the mul opcode to multiply the second top element with the top element of the stack.

mod: Implement the mod opcode to compute the remainder of the division of the second top element by the top element of the stack.

comments: Implement the capability to treat lines starting with # as comments.

pchar: Implement the pchar opcode to print the character at the top of the stack.

pstr: Implement the pstr opcode to print the string starting at the top of the stack.

rotl: Implement the rotl opcode to rotate the stack to the top.

rotr: Implement the rotr opcode to rotate the stack to the bottom.

stack, queue: Implement the stack and queue opcodes to set the format of the data to either LIFO (stack) or FIFO (queue).
