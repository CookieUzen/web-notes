---
title: Computer Organization
description: Unit 2 of Computer Science
---

# Computer Architecture

## CPU

The Central Processing Unit (CPU) is an integral part of a computer.
The CPU follows the `input, process, output model`, and is responsible for doing most of the calculations our computers need to do in order to run.
The CPU is the brain of a computer.

A CPU contains:
- Control Unit (CU)
- Arithmetic Logic Unit (ALU)
- Memory Address Register (MAR)
- Memory Data Register (MDR)

`CU` is responsible for operation of the CPU. It retrieves instructions from memory, then execute.

`ALU` performs math/logic/IO operations. The CU provides ALU data and instructions.

`MAR` is responsible for the memory address of data needed, while `MDR` is responsible for retrieving the data from the memory address.

## Machine Instruction Cycle

This is the steps in which instructions are carried out in machine code.
1. Fetch instructions from Primary Memory to Control Unit
2. Decode instructions in Control Unit (loads additional data)
3. Execute instructions
4. Stores results and check for next instruction

## Primary Memory

- 1 bit = one or zero
- 8 bits = 1 byte
- 64 bit system = 64 bits in each Memory Bus data transfer
- MB = Mega Byte, Mb = Mega bit

Memory is separated into `Random Access Memory` and `Read Only Memory`.

### RAM

RAM stores program instructions and relevant data. Data in RAM is stored in unique places: Memory Addresses.
Note, RAM allows for frequent read-write, and is volatile. If power is lost, all information is lost.

RAM is separated into two different types:
- __Dynamic RAM (DRAM)__, DRAM is slower than SRAM, but cheaper. Used in RAM sticks we use.
- __Static RAM (SRAM)__, SRAM is faster but more expensive (and smaller). SRAM is placed between the CPU and RAM. It is also called a cache.

### Cache

Cache holds useful information CPUs frequently uses.
This is so that the CPU does not have to use the slower DRAM when fetching instructions.
The CPU always read and write through the cache memory.

There are 3 levels of cache memory.
L1 is on the processor itself.
L2 lies between primary memory and the CPU.
Newer L3 cache is fulfilling similar roles to a L2 cache.

### ROM

ROM holds instructions.
But ROM is read only, and stores permanent information.
Such as instructions for boot or the BIOS (Basic Input Output System).

Often, ROM stores embedded data that is non-volatile, and is used to store permanent programs.
ROM is also commonly smaller than RAM.

### Registers

Registers are a small storage location that holds data.
We use the word `word` to indicate the register size (in bytes).

Both MAR and MDR are registers.
MAR stores memory address, MDR stores data (which is then saved to RAM).
A Memory (Address) Bus helps communicate between the MAR and the primary memory.
A Data Bus helps communicate between the MDR and the ALU.

## Secondary Memory

Slower memory than is non-volatile.
Used to store data permanently from RAM.

During startup, RAM is empty.
And thus Secondary Memory is needed to load data onto RAM.

When primary memory is not enough for one application, Virtual Memory enables program to store their data on Secondary Memory.
Virtual Memory moves the memory of unused application to secondary memory, freeing up space for newly opened application.
The memory is loaded into primary memory back on when the unused application is accessed again.

Some examples of secondary memory are:
- Hard Drive
- DVD/CD
- USB
- SD Card
- Floppy Disk
- Magnetic Tape

# Operating and Application Systems

An `Operating System` is a set of software that controls the computer's hardware resources and provides services for computer programs.
It interactive between the user and the hardware of the computer system.

The main services of an OS are:
- Peripheral Communication
- Memory Management
- Resource Monitoring and Multitasking
- Networking
- Disk Access and Data Management
- Security

## Software Application

Computer system uses `Software Application` to complete some task.
The main types of software application includes:
- Word Processors
- Spreadsheets
- Database Management Systems
- Web Browsers
- Email
- Computer Aided Design
- Graphic Processing Software

### Word Processor

A software used for production of any sort of document. Used for composing, editing, formatting, and printing of a document.

### Spreadsheets

Spreadsheets are programs used for the analysis of data.
Data is represented on cells, organized in rows and columns.
Spreadsheets are used for operation of arithmetic and mathematical functions.

### Database Management System

A DBMS is an application application that manages a database.
Common features of a DBMS includes:
- Create Queries
- Update Stores
- Modifies Queries
- Extract Information

This program provides an interface between a database between an user.
A database can often be represented as table, with rows and columns of data.

### Web Browser

A web browser is a software that is used to access, retrieve, and present content on the Internet.

### Email

Electronic mail is an application that sends digital message as mail.
Email use the `Simple Mail Transfer Protocol` (SMTP).

### Computer Aided Design

CAD is a type of software that assists engineers is creating a design.
CAD engineers to inspect a design from many positions or angles, allowing them to create designs better.

### Graphics Processing Software

A graphic processing software allows designers to edit, create, crop, erase, an image.

## Common Features of an Application

The two typical applications in a computer system is a GUI and a CLI.

A `Command Line Interface` (CLI) is an application than runs in a terminal.
A CLI is faster, use less memory, and more powerful.
Yet, it is harder to learn.

A `Graphical User Interface` (GUI) is an application that utilize icons and pictures to make the application more accessible.
It is easy to use compared to a CLI.
But requires more memory, a graphical display and a mouse, and is more difficult to implement.

### GUI Implementation

A common GUI includes several elements:
- Toolbar
- Menu
- Dialogue box

# Binary Representation

Computer systems use bits and bytes to store information.
This is a binary system.

## Bit and Byte

There is 8 bits in a byte.
A bit is a boolean, either true or false, yes or no.
Or more accurately, a bit is a digit in binary.

Since each bit can store 2 values, a binary of length $n$ can store $2^n$ possible values.

## Binary

The number system we commonly use is `base 10`.
This means for every digit incremented, the number will add by $10^n$.
Binary is `base 2`, where every digit incremented, the number will add by $2^n$.

When denoting the base of a number, we can add a subscript to the number.
For example: $9_{10} = 1001_{2}$.

Here's a table showing the multipliers of an eight bit binary:

|Digit       |   8   |   7   |   6   |   5   |   4   |   3   |   2   |   1   |
|------------|-------|-------|-------|-------|-------|-------|-------|-------|
|Power of 2  | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
|------------|-------|-------|-------|-------|-------|-------|-------|-------|
|Multiplier  |  128  |  64   |  32   |  16   |   8   |   4   |   2   |   1   |

### Negative Numbers In Binary

There is two methods of indicating a negative number: `two’s complement` and `signed binary`.
When storing a negative binary, an additional digit left to the MSB is required.

When using a signed binary, the `most significant bit` (leftmost digit) stores the negative sign.
If the MSB is $0$, then the number is positive, $1$ if the number is negative.

When using two's complement, the MSB's multiplier becomes negative.
Below is a table for an $8$ bit binary stored in two's complement.
Storing binary in two's complement makes performing mathematical operation easier that using a signed binary.

|Digit       |   8   |   7   |   6   |   5   |   4   |   3   |   2   |   1   |
|------------|-------|-------|-------|-------|-------|-------|-------|-------|
|Power of 2  |-$2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |
|------------|-------|-------|-------|-------|-------|-------|-------|-------|
|Multiplier  | -128  |  64   |  32   |  16   |   8   |   4   |   2   |   1   |

To convert a unsigned binary to two's complement,
1. inverse all digits
2. add 1

## Hexadecimal

`Hexadecimal` are numbers stored in base 16.
Use the notation $number_{16}$ to define hexadecimal numbers.

|Digit        | 4       | 3       | 2       | 1       |
|-------------|---------|---------|---------|---------|
|Power of 1   | $16^3$  | $16^2$  | $16^1$  | $16^0$  |
|-------------|---------|---------|---------|---------|
|Multiplier   | 4096    | 256     | 16      | 1       |

| Base 10     | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 |
|-------------|---|---|---|---|---|---|---|---|---|----|----|----|----|----|----|
| Hexadecimal | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | A  | B  | C  | D  | E  | F  |

### Converting Binary and Hexadecimal

A four digit binary can store 16 values, exactly the same length of one digit of hexadecimal.
Thus, when converting binary to hexadecimal, we can group the binary in chunks of four digits, and convert each chunk.
When converting hexadecimal to binary, we expand each digit of the hexadecimal individually, then append all the binary together.

## Representing Characters with Binary

In order to represent a character as binary, as table of binary to character have to be established before hand.
`ASCII` (American Standard Code for Information Technology) is one common standard.
An ASCII letter requires a 7 bit binary, and stores the alphabet along with commonly used key codes.

`Unicode` is a modern character-encoding scheme.
Unicode uses more bits that ASCII.
For example, the UTF-16 scheme uses 16 bits, more than twice the size of ASCII.
Due to the increase in memory, Unicode can contain characters and emojis from every language around the world.

When storing more that one character we will use a string --- a sequence of characters.

## Representing Images

When storing color, we would use a color encoding scheme.
The most commonly used scheme is `RGB`.
RGB stores color as 3 separate binary representing the intensity of red, green and blue.
Normally, an 8 bit binary will be used to store each color, resulting in a 32 bit binary for each color.
Since an 8 bit binary is the same length as a 2 digit hexadecimal, sometimes RGB will be stored in hex values.

An image is made up of a grid of `pixels`.
Since each pixel is a color, we can assign each pixel a KGB value.
In image will be stored as a big table of pixels (RGB values). A video is a sequence of pictures, and can be stored as such.

# Simple Logic Gates

`Logic Gates` perform mathematical operations on boolean values.
They are used from making electronic circuits to validating conditions in programing.
Logic gates have 2 input (except for NOT gate) and one output.
Below is a list of logic gates:
Note, _true_ $= 1$, _false_ $=0$

- __NOT:__ flips boolean
- __AND:__ evaluate _true_ __only__ if both inputs are _true_, otherwise evaluate _false_
- __OR:__ evaluate _true_ if one input is _true_, otherwise evaluate _false_
- __NAND:__ reverse of `AND`, combination of `AND` and `NOT`
- __NOR:__ reverse of `OR`, combination of `OR` and `NOT`
- __XOR:__ evaluate true if one only __one__ input is _true_, otherwise evaluate _false_

**TODO: insert table of symbols for logic gates**

## Truth Tables

**TODO: Construct truth table**

A boolean expression as many outcome as $2^n$, where $n$ is the number of logic gates.
When creating a truth table, fill each column for the inputs first.
For the first column, fill the first half of rows 0, and the rest 1.
For the second row, fill the first quarter of the rows 0, the second quarter of the rows with 1, repeat until all rows are filled.
For every next column, repeat the pattern: divide the rows into smaller and smaller segments.

## Simplification and Boolean Expressions

## Logic and Venn Diagrams Using Logic Gates
