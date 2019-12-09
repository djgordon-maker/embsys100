### Question 1

When the processor responds to an exception, it pushes R0, R1, R2, R3, R12, LR, PC, and APSR onto the stack.

At the same time it loads the address of the exception handler from vector table into the PC, and EXC_RETURN into the LR

EXC_RETURN describes the state to return the processor to when leaving the exception handler.
