# Introduction #

This list will eventually be an interrupt table, but for the time being, its just gonna be a list of the features.


# Details #

Here is a short list of current features:
  * **getchar** - INPUT: Nothing. OUTPUT: Character in AL.
> > _Gets one character from stdin (no it doesn't have to be a keyboard!) and stores it in al for you._
  * **gets** - INPUT: Byte Array in SI. OUTPUT: Null Ended String in SI.
> > _Gets a null ended string from stdin, you point it an array in si, it returns a string in it, perfect for use with print\_string._
  * **waitkey** - INPUT: Nothing. OUTPUT: Nothing.
> > _Waits for a keypress, then returns to program, doesn't return anything._
  * **print\_string** - INPUT: Null Ended String in SI. OUTPUT: Nothing.
> > _Prints a string pointed to by si, stops at null ending, NOT newline._

# Upcoming Functions #
Some Upcoming functions to expect soon:
  * More printing stuff, like printing numbers.
  * Basic String Functions.
  * Blind input for passwords and stuff.