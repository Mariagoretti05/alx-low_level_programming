                    BIT MANIPULATION


           REQUIREMENTS

Language: C OS: Ubuntu 20.04 LTS Compiler: gcc 11.2.0 Style guidelines: Betty style

              DESCRIPTION OF EACH FILE
0. A function that converts a binary number to an unsigned int.

Prototype: unsigned int binary_to_uint(const char *b);

1. A function that prints the binary representation of a number.

Prototype: void print_binary(unsigned long int n);

2. A function that returns the value of a bit at a given index.

Prototype: int get_bit(unsigned long int n, unsigned int index);

3. A function that sets the value of a bit to 1 at a given index.

Prototype: int set_bit(unsigned long int *n, unsigned int index);

4. A function that sets the value of a bit to 0 at a given index.

Prototype: int clear_bit(unsigned long int *n, unsigned int index);

5. A function that returns the number of bits you would need to flip to get from one number to another.

Prototype: unsigned int flip_bits(unsigned long int n, unsigned long int m);

100. A  function that checks the endianness.

Prototype: int get_endianness(void);

101. Find the password for this program.
Save the password in the file 101-password
Your file should contain the exact password, no new line, no extra space
