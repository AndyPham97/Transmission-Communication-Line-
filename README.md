# COMP2401---Assignment-2
A program that simulates a transmission communication line.

###TO RUN THE RECIEVE PROGRAM###
In CMD, compile the recieve program using the following statements:
gcc –o recv receive.c bit_manipulation.c
gcc  -g –o recv receive.c bit_manipulation.c

Run the recieve program using: ./recv
Enter in the sequence of short integers from your transmit program, it will then
output transmitted message and then the corrected transmitted message

###TO RUN THE TRANSIT PROGRAM###

In CMD, compile the transit program using the following statements:
gcc –o tran transmit.c bit_manipulation.c
gcc  -g –o tran transmit.c bit_manipulation.c

Run the transmit program using: ./tran
Enter in a message, then it will output a sequence of short integers


Note: There has some errors with how it sets the parity bits and how I was using bit masks to do that. If you can fix it, that would be great!
