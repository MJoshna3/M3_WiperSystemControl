# TEST CASES AND CORRESPONDING OUTPUT
# High Level Test Cases
Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS
HR_01 | Check if the BUTTON is pressed | program execution | MicroController/Engine Starts | LED ON(RED) | PASS
HR_02 | Check if the BUTTON is pressed | program execution | WIPER Starts | LED ON(BLUE) | PASS
HR_03 | Check if the BUTTON is pressed | program execution | WIPER Starts | LED ON(GREEN) | PASS
HR_04 | Check if the BUTTON is pressed | program execution | WIPER Starts | LED ON(ORANGE) | PASS
HR_05 | Check if the BUTTON is pressed | - | MicroController/Engine Stops | LED TURNED OFF | PASS
# Low Level Test Cases
Test ID | Description | Exp.i/p | Exp.o/p | Actual o/p | STATUS
LR_01 | Check if the BUTTON is pressed | program execution | MicroController/Engine Starts | LED ON(RED) | PASS
LR_02 | Check if the BUTTON is pressed again | program execution | WIPER Starts and speed of wiper is slow | LED ON(BLUE) | PASS
LR_03 | Check if the BUTTON is pressed again | program execution | WIPER Starts and speed of wiper is moderate | LED ON(GREEN) | PASS
LR_04 | Check if the BUTTON is pressed again | program execution | WIPER Starts and speed of wiper is Good | LED ON(ORANGE) | PASS
LR_05 | Check if the BUTTON is pressed again | - | MicroController/Engine Stops | LED TURNED OFF | PASS
