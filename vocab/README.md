# Vocab

- [Home](/README.md#async-table-of-contents)
- [Chapter 2](#chapter-2)
- [Chapter 3](#chapter-3)
- [Chapter 4](#chapter-4)

- [Appendix B](#appendix-b)

## Chapter 2
([top](#vocab))
#### instruction set
> *The vocabulary of commands understood by a given architecture.*

#### stored-program concept
> *The idea that instructions and data of many types can be stored in memory as numbers, leading to the stored program* computer.

#### word
> *The natural unit of access in a computer, usually a group of 32 bits; corresponds to the size of a register in the MIPS architecture.*

#### data transfer instruction
> *A command that moves data between memory and registers.*

#### address
> *A value used to delineate the location of a specific data element within a memory array*

#### alignment restriction
> *A requirement that data be aligned in memory on natural boundaries*

#### binary digit
> *Also called a **binary bit**. One of the two numbers in base 2, 0 or 1, that are the components of information.*

#### least significant bit
> *The rightmost bit in a MIPS word.*

#### most significant bit
> *The leftmost bit in a MIPS word.*

#### instruction format
> *A form of representation of an instruction composed of fields of binary numbers*

#### machine language
> *Binary representation used for communication with a computer system*

#### hexadecimal
> *Numbers in base 16*

#### MIPS fields
> #### op
> *Basic operation of the instruction, traditionally called the opcode*
> #### rs
> *The first register source operand*
> #### rt
> The second register source operand*
> #### rd
> *The register destination operand. It gets the result of the operation*
> #### shamt
> *Shift amount*
> #### funct
> *Function. This field, often called the function code, selects the specific variant of the operation in the op field*

#### opcode
> *The field that denotes the operation and format of an instruction*

#### AND
> *A logical bit-by-bit operation with two operands that calculates a 1 only if there is a 1 in both operands*

#### OR
> *A logical bit-by-bit operation with two operands that calculates a 1 if there is a 1 in either operand.*

#### NOT
> *A logical bit-by-bit operation with one operand that inverts the bits; that is, it replaces every 1 with a 0, and every 0 with a 1.*

#### NOR
> *A logical bit-by-bit operation with two operands that calculates the NOT of the OR of the two operands. That is, it calculates a 1 only if there is a 0 in both operands*

#### conditional branch
> *An instruction that requires the comparison of two values and that allows for a subsequent transfer of control to a new address in the program based on the outcome of the comparison.

#### basic block
> *A sequence of instructions without branches (except possibly at the end) and without branch targets or branch labels (except possibly at the beginning).*

#### jump address table
> *Also called **jump table**. A table of addresses of alternative instruction sequences*

#### procedure
> *A stored subroutine that performs a specific task based on the parameters with which it is provided* Procedures are one way to implement abstraction in software.

#### jump-and-link instruction
> *An instruction that jumps to an address and simultaneously saves the address of the following instructions in a register ($ra in MIPS)*

#### return address
> *A link to the calling site that allows a procedure to return to the proper address; in MIPS it is stored in register $ra.*

#### caller
> *The program that instigates a procedure and provides the necessary paremeter values.*

#### callee
> *A procedure that executes a series of stored instructions based on parameters provided by the caller and then returns control to the caller*

#### program counter (PC)
> *The register containing the address of the instruction the program being executed* A more sensible name would have been *instruction address register.*

#### stack
> *A data structure for spilling registers organized as last-in-firs-out queue.*

#### stack pointer
> *A value denoting the most recently allocated address in a stack that shows where registers should be spilled or where old register values can be found.* In MIPS, it is register $sp.

#### push
> *Add element to stack*

#### pop
> *Remove element from stack*

#### global pointer
> *The register that is reserved to point to the static area.*

#### procedure frame
> *Also called **activation record**. The segment of the stack containing a procedure's saved registers and local variables.*

#### frame pointer
> *A value denoting the location of the saved registers and loal variables for a given procedure*

#### text segment
> *The segment of a UNIX object file that contains the machine language code for routines in the source file*

#### PC-relative addressing (program counter)
> *An addressin regime in which the address is the sum of the program counter (PC) and a constant in the instruction.*

#### addressing mode
> *One of several addressing regimes delimited by their varied use of operands and/or addresses.*

#### data race
> *Two memory accessses form a data race if they are from different threads to the same location, at least one is write, and they occure one after another*

#### assembler language
> *A symbolic language that can be translated into binary machine language*

#### pseudoinstructoin
> *a common variation of assembly language instruction often treated as if it were an instruction in its own right*

#### symbol table
> *a table that matches names of labels to the addresses of the memory words that instructions occupy*

#### linker
> *also called **link editor**. A systems program that combines indepenetly assembled machine language programs and resolves all undefined labels into an executable file.*

#### executable file
> *A functional program in the format of an object file that contains no unresolved references. It can contain symbol tables and debugging information. A "stripped executable" does not contain that information. Relocation information may be included for the loader*

## Chapter 3

([top](#vocab))

#### Arithmetic Logic Unit
> ***ALU** Hardware that performs addition, subtraction, and usually logical operations such as AND and OR*

#### exception
> *Also caled **interupt**. An unscheduled event that disrupts program execution; used to detect overflow.*

#### interrupt
> *An exception that comes from outside of the processor. (Some architectures use the term interrupt for all exceptions.)

#### dividend
> *A number being divided*

#### divisor
> *a number that the dividend is divided by*

#### quotient
> *the primary result of a division; a number that when multiplied by the divisor and added to the raminder produces the dividend.*

#### remainder
> *the secondary result of a division; a number that when added to the product of the quotient and the divisor produces the dividend.*

#### scientific notation
> *A notation that renders numbers with a single digit to the left of the decimal point.*

#### normalized
> *a number in floating-point notation that has no leading 0s*

#### floating point
> *computer arithmetic that represents numbers in which the binary point is not fixed*

#### fraction
> *the value, generally between 0 and 1, placed in the fraction field. The fraction is also called the mantissa*

#### exponent
> *in the numerical representation system of floatin-point arithmetic, the value that is placed in the exponent field.*

#### overflow (floating-point)
> *a situation in which a positive exponent becomes too large to fit in the exponent field*

#### underflow (floating-point)
> *a situatoin win which a negative exponnent becomes too large to fit in the exponent field*

#### double precision
> *a floating-point value represented in two 32-bit words*

#### single precision 
> *a floating-point value represented in one 32-bit word*

## Chapter 4
([top](#vocab))


## Appendix B
([top](#vocab))
#### asserted signal
> *a signal that is (logically) true, or 1*

#### deasserted signal
> *a signal that is (logically) false, or 0*


#### combinational logic
> *a logic system whose bock do not acontain memory and hence compute the same output given the same input*

#### sequential logic
> *a group of logic elements that contain memory and hence whose value depends on the inputs as well as the current contents of the memory*

#### gate
> *a device that implements basic logic functions, such as AND or OR*
