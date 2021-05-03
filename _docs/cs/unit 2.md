---
title: Computer Organization
description: Unit 2 of Computer Science
---

# Computer Architecture

The Central Processing Unit (CPU) is an integral part of a computer. The
CPU follows the `input, process, output model`, and is responsible for
doing most of the calculations our computers need to do in order to run.
The CPU is the brain of a computer.

A CPU contains:

-   Control Unit

-   Arithmetic Logic Unit

-   Memory Address Register

-   Memory Data Register

CU is responsible for operation of the CPU. It retrieves instructions
from memory, then execute.

ALU performs math/logic/IO operations. The CU provides ALU data and
instructions.

MAR is responsible for the memory address of data needed, while MDR is
responsible for retrieving the data from the memory address.

# Primary Memory

-   1 bit = one or zero

-   8 bits = 1 byte

-   64 bit system = 64 bits in each Memory Bus data transfer

-   MB = Mega Byte, Mb = Mega bit

Memory is separated into `Random Access Memory` and `Read Only Memory`.

## RAM

RAM stores program instructions and relevant data. Data in RAM is stored
in unique places: Memory Addresses.

Note, RAM allows for frequent read-write, and is volatile. If power is
lost, all information is lost.

RAM is separated into two different types:

-   Dynamic RAM

-   Static RAM

### DRAM

DRAM is slower than SRAM, but cheaper. This is the RAM sticks we use.

### SRAM

SRAM is faster but more expensive (and smaller). SRAM is placed between
the CPU and RAM. It is also called a cache.

Cache holds useful information CPUs frequently uses. This is so that the
CPU does not have to use the slower DRAM when fetching instructions. The
CPU always read and write through the cache memory.

There are 3 levels of cache memory. L1 is on the processor itself. L2
lies between primary memory and the CPU. Newer L3 cache is fulfilling
similar roles to a L2 cache.

## ROM

ROM holds instructions. But ROM is read only, and stores permanent
information. Such as instructions for boot or the BIOS (Basic Input
Output System).

Often, ROM stores embedded data that is non-volatile, and is used to
store permanent programs. ROM is also commonly smaller than RAM.

# Registers

Registers are a small storage location that holds data. We use the word
`word` to indicate the register size (in bytes).

Both MAR and MDR are registers. MAR stores memory address, MDR stores
data (which is then saved to RAM). A Memory (Address) Bus helps
communicate between the MAR and the primary memory. A Data Bus helps
communicate between the MDR and the ALU.

# Machine Instruction Cycle

This is the steps in which instructions are carried out in machine code.

1.  Fetch instructions from Primary Memory to Control Unit

2.  Decode instructions in Control Unit (loads additional data)

3.  Execute instructions

4.  Stores results and check for next instruction

# Secondary Memory

Slower memory than is non-volatile. Used to store data permanently from
RAM.

During startup, RAM is empty. And thus Secondary Memory is needed to
load data onto RAM.

When primary memory is not enough for one application, Virtual Memory
enables program to store their data on Secondary Memory. Virtual Memory
moves the memory of unused application to secondary memory, freeing up
space for newly opened application. The memory is loaded into primary
memory back on when the unused application is accessed again.

Some examples of secondary memory are:

-   Hard Drive

-   DVD/CD

-   USB

-   SD Card

-   Floppy Disk

-   Magnetic Tape

# Operating and application Systems

An `Operating System` is a set of software that controls the computer's
hardware resources and provides services for computer programs. It
interactive between the user and the hardware of the computer system.

The main services of an OS are:

-   Peripheral Communication

-   Memory Management

-   Resource Monitoring and Multitasking

-   Networking

-   Disk Access and Data Management

-   Security

# Software Application

Computer system uses software application to complete some task. The
main types of Software Application includes:

-   Word Processors

-   Spreadsheets

-   Database Management Systems

-   Web Browsers

-   Email

-   Computer Aided Design

-   Graphic Processing Software

## Word Processor

A software used for production of any sort of document. Used for
composing, editing, formatting, and printing of a document.

## Spreadsheets

Spreadsheets are programs used for the analysis of data. Data is
represented on cells, organized in rows and columns. Spreadsheets are
used for operation of arithmetic and mathematical functions.

## Database Management System

A DBMS is an application application that manages a database. Common
features of a DBMS includes:

-   Create Queries

-   Update Stores

-   Modifies Queries

-   Extract Information

This program provides an interface between a database between an user. A
database can often be represented as table, with rows and columns of
data.

## Web Browser

A web browser is a software that is used to access, retrieve, and
present content on the Internet.

## Email

Electronic mail is an application that sends digital message as mail.
Email use the `Simple Mail Transfer Protocol` (SMTP).

## Computer Aided Design

CAD is a type of software that assists engineers is creating a design.
CAD engineers to inspect a design from many positions or angles,
allowing them to create designs better.

## Graphics Processing Software

A graphic processing software allows designers to edit, create, crop,
erase, an image.

# Common Features of an Application

The two typical applications in a computer system is a GUI and a CLI.

A Command Line Interface (CLI) is an application than runs in a
terminal. A CLI is faster, use less memory, and more powerful. Yet, it
is harder to learn.

A Graphical User Interface (GUI) is an application that utilize icons
and pictures to make the application more accessible. It is easy to use
compared to a CLI. But requires more memory, a graphical display and a
mouse, and is more difficult to implement.

## GUI Implementation

A common GUI includes several elements:

-   Toolbar

-   Menu

-   Dialogue box

# Binary Representation

Computer systems use bits and bytes to store information. This is a
binary system.

There is 8 bits in a byte. A bit is a boolean, either yes or a no. Or
more accurately, a bit is a digit in binary.

The number system we commonly use is base-10. This means for every digit
incremented, the number will add by $10^n$. Binary is base-2, where
every digit incremented, the number will add by $2^n$.

## Binary

Here's a table showing the multipliers of an eight bit binary:

  Digit           8       7       6       5       4       3       2       1
  ------------ ------- ------- ------- ------- ------- ------- ------- -------
  Power of 2    $2^7$   $2^6$   $2^5$   $2^4$   $2^3$   $2^2$   $2^1$   $2^0$
  Multiplier     128     64      32      16       8       4       2       1

## Negative Numbers In Binary

There is two methods of indicating a negative number: `two’s complement`
and ``
