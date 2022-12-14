# Pwn

## Assembly reminder

![bof_1](./assets/bof_1.png)

## Data registers

| 32-bit Register | 64-bit Register | Description                                                                                                 |
| --------------- | --------------- | ----------------------------------------------------------------------------------------------------------- |
| EAX             | RAX             | Accumulator is used in input/output and for arithmetic operations                                           |
| EBX             | RBX             | Base is used in indexed addressing                                                                          |
| ECX             | RCX             | Counter is used to rotate instructions and count loops                                                      |
| EDX             | RDX             | Data is used for I/O and in arithmetic operations for multiply and divide operations involving large values |

## Pointers registers

| 32-bit Register | 64-bit Register | Description                                                                                                 |
| --------------- | --------------- | ----------------------------------------------------------------------------------------------------------- |
| EIP             | RIP             | Instruction Pointer stores the offset address of the next instruction to be executed                        |
| ESP             | RSP             | Stack Pointer points to the top of the stack                                                                |
| EBP             | RBP             | Base Pointer is also known as Stack Base Pointer or Frame Pointer thats points to the base of the stack     |
| EDX             | RDX             | Data is used for I/O and in arithmetic operations for multiply and divide operations involving large values |

## Index registers

| Register 32-bit | Register 64-bit | Description                                                             |
| --------------- | --------------- | ----------------------------------------------------------------------- |
| ESI             | RSI             | Source Index is used as a pointer from a source for string operations   |
| EDI             | RDI             | Destination is used as a pointer to a destination for string operations |

fgfg