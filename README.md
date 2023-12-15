C - Stacks, Queues - LIFO, FIFO


The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument.

Task:

1. Implement the push and pall opcodes.

The push opcode

The opcode push pushes an element to the stack.

The pall opcode

The opcode pall prints all the values on the stack, starting from the top of the stack.

2. Implement the pint opcode.

The pint opcode

The opcode pint prints the value at the top of the stack, followed by a new line.

3. Implement the pop opcode.

The pop opcode

The opcode pop removes the top element of the stack.

4. Implement the swap opcode.

The swap opcode

The opcode swap swaps the top two elements of the stack.

5. Implement the add opcode.

The add opcode

The opcode add adds the top two elements of the stack.

6. Implement the nop opcode.

The nop opcode

The opcode nop doesn’t do anything.
