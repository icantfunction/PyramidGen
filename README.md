# Pyramid Generator

This is a simple JavaScript program that generates a pyramid of a specified size.

## How it Works

The program uses a function `padRow` to generate each row of the pyramid. This function takes two arguments: the current row number and the total number of rows. It returns a string that represents the row.

The main part of the program is a loop that calls `padRow` for each row of the pyramid and adds the result to the `rows` array. If the `inverted` variable is `true`, the row is added to the beginning of the array; otherwise, it's added to the end.

Finally, the program prints out the pyramid by joining all the rows with newline characters.

## Usage

To run the program, make sure you have Node.js installed, then run the following command in your terminal:

```bash
node PyramidGen.js