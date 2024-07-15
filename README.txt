First Written in 7/15/2024:
Write by Hanjinhee (Born in 2002.08.22)

Edit History

1 : 2024.07.15
    - Declaration of cross-compilation project.
    - Warranty noticed.
2 : 
3 : 


This is about compiler_plus that is cross Compilation project.

This compiler can produce target-machine's hexadecimal code by compiling C programming language.
By using them(hex code), 


Compilation(Translation) process
 1. while(c file exists):
 - If something(function/type value) definition not exist in current file, 
    compilation failed. (Type  [int , float, double ...] initialization is not Neccessary.)
-If  translation success, it means your C programming file logically corrected.
It is not warrant your translated C files (target-machine-code) run correctly.
That reason depend on your target Hardware(Board) state. Whereas emulator run correct. 
what you want to watch, it(emulator) suppose only somewhat hardware not broken down.
-Actually, supposing hardware(Board) broken down issues are much complicated. 
Additionally, it not warrant your target Board run correctly in real-time.

So, It must translate correctly not suppose such above reasons. If it's Compilation output(Just Software)
not warranted, who trust this system?(Zero amount). So that, Compilation(as called as translation) must be 
warranted without target-Hardware(Board).   
 

 