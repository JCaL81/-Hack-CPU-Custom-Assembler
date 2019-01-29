# -Hack-CPU-Custom-Assembler
CPU Architecture based and expanded upon presentations by Noam Nisan and Shimon Schocken.

Assembler Changelog:

1.0 Assembler Completed

1.1 Proper executable file created as well as a better directory prompt

1.2 Line Number/Hexadecimal/Bit Split options added

1.3 Comments added; Fixed bug that crashed program due to spacing between lines of code

1.4 Added Screen Refresh control capabilites (add * to the end of any C command to refresh screen)

1.5 Doesn't end when assembler is finished + crash fixes resulting from issues with strings & spacings after lines

1.6 Added support for symbols/variable names i.e. (LOOP), @LOOP, ect. Using (anything) can denote a location in the program you can call to later with @anything allowing to easily jump. Using @anything can also be used to denote a location in memory, like the name of a variable. See example TextProgram.txt for symbols in use.

