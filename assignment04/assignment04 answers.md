1. When useing bit banding, the compiler uses a Load Register and a Move to store the alias and value in the registers, then it uses a Store Register to store the value in the alias
2. When writing to a bit directly, the compiler uses two Load Registers to store the address in a register, then store the data at that address in another register.  Followed by either a logical OR (to set the bit) or a Bit Clear (to clear the bit), and a Store Register to store the modified data in the address

