# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java
- Application for printing directory tree
- Show hidden files
- Use color output
- Root directory to begin printing tree
- hidden files are identified by names that start with a .
- color output is enabled by default, disable by using flags. Flags are __ ?
 -h show hidden files
 -nc do not use color
 

## ConsoleColor.java
- Using enum instead of class 
- Only colors allowed to choose:
BLACK
RED
GREEN
YELLOW
BLUE
PURPLE
CYAN
WHITE
RESET
-NSI escape code. A terminal recognizes it as an instruction rather than ordinary text.
-getCode() returns the code 
-toString returns the code so the colors can be used directly
-Reset, changes the terminal color back to default



## ColorPrinter.java / ColorPrinterTest.java
- This class is responsible for printing colored text
-stores currentColor using ConsoleColor enum and a PrintStream that determines where the output is printed
- setCurrentColor() changes the color 
- getCurrentColor returns it
- reset determines whethere the console color should reset after printing
- the constructor allows the printer to start with either default white color or a specifed color
- need to implement print(String message, boolean rest)


## TruffulaOptions.java / TruffulaOptionsTest.java

## TruffulaPrinter.java / TruffulaPrinterTest.java

## AlphabeticalFileSorter.java