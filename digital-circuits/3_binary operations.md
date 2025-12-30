# Binary Operations

## Add

a) Sum the bits, from right to left
b) Consider the carry
c) The final carry can create another bit (MSB)

- 0 + 0 = 0
- 1 + 0 = 1
- 0 + 1 = 0
- 1 + 1 = 0, carry 1

## Subtraction

a) Subtract bit by bit, starting from right to left.
b) If necessary, borrow the leftmost bit 
c) Ignore the zeros on the left side

> When we borrow a bit it means sum 2 (10 on binary base) on the current bit.

**Example**

Consider 1011 - 0110, from right to left:

1 - 0 = 1 (carry 0)
1 - 1  = 0 (carry 0)
0 - 1 = 10 - 1  = 1(borrow 1 from the leftmost bit)
0 - 0 = 1

## Binary multiplication

This operation is similar to multiplication with decimal numbers, but only with 0 and 1.

a) Multiply each bit of the multiplicand by the bit of the multiplier.
b) Shift each row according to the position of the bit in the multiplier.
c) Add all the rows (binary addition).

