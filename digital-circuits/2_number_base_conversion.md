# Number base conversion

## Decimal to binary

#### Sucessive division by 2

The process to transform decimal number to binary is described below:

a) Divide the decimal number by 2
b) Write the remainder
c) Use the quotient for the next division
d) Repeat the process until the quotient to be zero

**Example**

25 ÷ 2 = 12 remainder 1
12 ÷ 2 = 6  remainder 0
6  ÷ 2 = 3  remainder 0
3  ÷ 2 = 1  remainder 1
1  ÷ 2 = 0  remainder 1

25₁₀ = 11001₂

##### Notice

The division process must be stopped when the quotient is equal zero. The latest step on division is 1 ÷ 2 = 0 remainder 1.

It's true for all positive number different of zero.

## Binary to decimal

The process to transform binary numbes to decimal is described below

a) For each bit, give a index, starting with zero and from right to lef
b) For each bit 1, sum the raised in the index
c) You should ignore bits zero

**Example**

bit: 3 2 1 0
value: 1 0 1 1

1·2³ + 0·2² + 1·2¹ + 1·2⁰
= 8 + 0 + 2 + 1
= 11₁₀

## Binary to hexadecimal

1 hexadecimal digit = 4 bits (nibble)

The process to convert binary numbers to hexadecimal numbers is described below.

a) Write the binary number
b) Group it in groups containing 4 bits, starting from right to left
c) If the latest group in left has less than 4 bits, add zeros
d) Convert each group for a hexadecimal number

**Example**

a) 11010111
b) 11010111 → 1101 0111
c) 1101 = D and 0111 = 7
d) 11010111₂ = D7₁₆


## Hexadecimal to binary

The process to convert hexadecimal numbers to binary is  described below.

a) Each hexadecimal digit is exactly 4 bits (1 nibble)
b) Replace each hex digit by your correspondent binary group

**Example**

D7 to binary

a) D → 1101 and 7 → 0111
b) D7 = 11010111₂

