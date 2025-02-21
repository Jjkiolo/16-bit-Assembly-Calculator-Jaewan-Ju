# 16-bit-Assembly-Calculator-Jaewan-Ju
Features
  displays instructions beforehand
  supports 4 different operators -, +, * and /
  terminates when either 'XX', 'xx', 'Xx' or 'xX' is put in
  displays negative answers correctly
    For example: 22-77 = -55
  handles numbers of any length from 0 to 65525.
    For example: 22+1132 = 1154
  handles negative input values.
    For example: -2+7 = 5
  displays the error message when user doesn't follow the instructions correctly

Justification about the messes in the code
  There are some blocks full of nop instructions. Those areas should be clear with no instructions as they are likely to be connected to the console.
  The program could be slow when dealing with lengthy numbers. JGE and JL do not work properly when it comes to big numbers due to two's complement.

How to compile the code on Sting and run it on WASP
  1. unzip WASP4aq(1).zip
  2. Open 16-bit-Assembly-Calculator by Jaewan Ju.txt
  3. Press Ctrl + A and Ctrl + C
  4. Open Sting1.1.exe in WASP folder
  5. Click the text editor on the lefthand side
  6. Press Ctrl + V
  7. Uncheck 'Bleep' in the middle
  8. Click 'Assembly'
  9. Click 'Save Wex'
  10. Save the machine code converted from the assembly code as whatever name you want
  11. Right click 'WASP' at the right-top corner
  12. Check 'Console', 'Disabled Animation' and 'Run'
  13. Click 'Save and Launch'
  14. Type any equation you want to work out on the console following the instructions described on the console
