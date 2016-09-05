# MIPS Assembly Exercises

Each subdirectory in this repository is an exercise.

Each exercise consists of a README.md and some automated tests.

For these problems, we use the popular MIPS simulator [MARS](http://courses.missouristate.edu/KenVollmar/mars/). Download the MARS jar archive from the MARS website and place it somewhere easily accessible. Also install the Java SDK if you do not have it already.

To run the tests, assemble and run the test runner file for a given exercise either via the MARS simulator GUI, or on the command line. To run on the command line,
specify first the runner file and then your implementation, like so:

    java -jar /path/to/mars.jar nc runner.mips impl.mips

To run in the GUI, `include` your implementation at the bottom of "runner.mips"
by uncommenting the final line.

The test runner will either complete with a “success” message or terminate on a failing test with a message specifying the input for which that test failed.



## Exercises

These are ordered roughly in order of difficulty.
The README.md file for each exercise explains in more detail what the exercise is about.

  **binary**
  Write a program that will convert a binary number, represented as a string (e.g. '101010'), to its decimal equivalent using first principles

  **octal**
  Write a program that will convert a octal number, represented as a string (e.g. '1735263'), to its decimal equivalent using first principles (i.e. no, you may not use built-in or external libraries to accomplish the conversion).

  **trinary**
  Write a program that will convert a trinary number, represented as a string (e.g. '102012'), to its decimal equivalent using first principles.

  **hexadecimal**
  Write a program that will convert a hexadecimal number, represented as a string (e.g. "10af8c"), to its decimal equivalent using first principles (i.e. no, you may not use built-in or external libraries to accomplish the conversion).

  **leap**
  Write a program that will take a year and report if it is a leap year.

  **difference-of-squares**
  Find the difference between the sum of the squares and the square of the sums of the first N natural numbers.

  **hamming**
  Write a program that can calculate the Hamming difference between two DNA strands.

  **rna-transcription**
  Write a program that, given a DNA strand, returns its RNA complement (per RNA transcription).

  **isogram**
  Determine if a word or phrase is an isogram.

  **triangle**
  Write a program that can tell you if a triangle is equilateral, isosceles, or scalene.

  **scrabble-score**
  Write a program that, given a word, computes the scrabble score for that word.

  **raindrops**
  Write a program that converts a number to a string, the contents of which depends on the number's factors.


## Source

These exercises are from the [MIPS Assembly][mips] track on [Exercism][exercism]

[exercism]: http://exercism.io
[mips]: http://exercism.io/languages/mips
