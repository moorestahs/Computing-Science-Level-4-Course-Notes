---
title: "The Processor and Memory"
draft: false
weight: 60
---
## The Processor

The processor, sometimes known as the __central processing unit__ (CPU), is the part of a computer system that carries out the __instructions__ of a computer program, to perform the basic arithmetical, logical, and input/output operations of the system.  It is sometimes known as the brains of the computer.

![Illustration1](/cpu-3-parts.png)

The processor is divided into three parts :

+ The __Arithmetic and Logic Unit__(ALU) performs all the calculations (e.g. + - / *) and Logical operations (e.g. AND, OR).

+ The __Control Unit__ controls the sequencing of fetching, decoding and execution of instructions.

+ The __Registers__ are temporary memory locations within the processor itself.

## Memory

Memory is a set of chips which store programs and data in the computer.  

All memory is divided into storage locations. 

Each storage location is given a unique address so that the computer can read and write the data to that location correctly.

In the diagram opposite, memory location 1001 is storing the number 23.  The memory location 1004 is storing A.

## Buses

In a computer, all the program instructions are stored in memory and transferred to the processor one instruction at a time to be executed. To do this there must be connections between the processor and memory. These connections are known as buses.

A bus is a group of wires used collectively to transmit information. 

<video controls width="640">
    <source src="/processor-buses-animation.mp4">
    Sorry, your browser doesn't support embedded videos.
</video>

There are 2 buses that connect the processor and memory.

+ The Address Bus identifies the memory location that is going to be accessed.   It is only a one-way bus as only the processor can identify the memory address.

+ The Data Bus transfers data between the processor and memory and vice versa.  It is a two-way bus as information can be written from the processor to memory and read from memory to the processor.
