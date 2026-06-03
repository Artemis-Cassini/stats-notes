### Switches
-  The engineers treated a positive voltage as a "1" and a zero voltage as a "0". 0s and 1s are known as **bits** (binary digits)

---
### Processors and Memory
- To support different calculations, circuits called **processors** were created to process (aka execute) a list of desired calculations, with each calculation called an **instruction**
- Instructions are stored in a memory. A **memory** is a circuit that can store 0s and 1s in each of a series of thousands of addressed locations, like a series of addressed mailboxes that each can store an envelope (the 0s and 1s)

---
### Instructions

| Process             | Description                                                                          |
| ------------------- | ------------------------------------------------------------------------------------ |
| **Add X, # num, Y** | Adds data in memory location *X* to the number *num*, storing result in location *Y* |
| **Sub X, # num, Y** | Subtracts *num* from data in location *X*, storing result in location *Y*            |
| **Mul X, # num, Y** | Multiplies data in location *X* by *num*, storing result in location *Y*             |
| **Div X, # num, Y** | Divides data in location *X* by *num*, storing result in location *Y*                |
| **Jmp Z**           | Tells the processor that the next instruction to execute is in memory location *Z*   |
- The programmer-created sequence of instructions is called a **program, application**, or just **app**

---
### Writing Computer Programs
- Instructions represented as 0s and 1s are known as **machine instructions**, and a sequence of machine instructions together form an **executable program** 
- Because 0s and 1s are hard to comprehend, programmers soon created programs called _assemblers_ to automatically translate human readable instructions, such as "Mul 97, #9, 98", known as **assembly** language instructions, into machine instructions
- In the 1960s and 1970s, programmers created **high-level languages** to support programming using formulas or algorithms 
- To support high-level languages, programmers created **compilers**, which are programs that automatically translate high-level language programs into executable programs