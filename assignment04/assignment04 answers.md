#### Problem 1

b) When useing bit banding, the compiler uses a Load Register and a Move to store the alias and value in the registers, then it uses a Store Register to store the value in the alias

c) When writing to a bit directly, the compiler uses two Load Registers to store the address in a register, then store the data at that address in another register.  Followed by either a logical OR (to set the bit) or a Bit Clear (to clear the bit), and a Store Register to store the modified data in the address

#### Problem 2
a) It pushes all but 4 arguments onto the stack, then moves the remaining arguemtns into R0-R3

b) Before calling the function with 5 arguements, it pushes the 5th argument onto the stack.  Then it moves the 1st through 4th arguements into registers 0 through 3.

c) Just after calling the function with 5 arguements (after pushing R4-R7 onto the stack), it moves the 1st argument to R4 and pops the 5th argument off the stack into R0
