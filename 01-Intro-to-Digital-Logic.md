# Digital Signals

A digital signal has two states at any given time - `HIGH` and `LOW`. This is
in stark contrast to an analog signal, which has many different frequencies.
Digital circuits consume far less power than analog circuits and enable higher
bandwidths.

*Dynamic signal levelling* is easier in digital -- the signal varies from 0 to
Vdd, in contrast to analog where signals can vary quite dramatically.

# Numerical Systems

There are two classes of numeral system: unary and positional.

*Unary* numeral systems in use include tally marks and Roman numerals. These
numeral systems are not particularly useful for computation -- they are
inefficient to store and cumbersome to manipulate.

A *positional* number system uses place value to relate digits with each other.

Example:
\[ 1385.3 = 1 \times 10^3 + 3 \times 10^2 + 8 \ times 10^1 + 5 \times 10^0 + 3 \times 10^{-1} \]

(**NOTE:** The "decimal point" is more generally referred to as the *radix
point*.)

The radix point acts as the dividing line between \[ b^0 \] and \[ b^{-1} \],
where $b$ is a base.

## Binary, hexadecimal, and octal

Digital systems operate in base 2, or binary. Binary numbers can get very long
and rather painful to write out, so it is often easier to use hexadecimal or
octal numbers. The hexadecimal number system allows us to represent a 4-bit
number using a single digit. Any binary number can be written as hex simply by
grouping the number every 4 bits.

In octal, a single digit represents a 3-bit number.

## Converting between bases

You use *successive division* -- divide the number by the base multiple times
and capture the remainder each time, then place each remainder in reverse order
of division.
