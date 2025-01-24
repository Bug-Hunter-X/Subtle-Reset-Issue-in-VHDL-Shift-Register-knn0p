This repository demonstrates a common, yet subtle, bug in VHDL code related to shift registers and their interaction with reset signals.  The bug lies in how the reset signal is handled within the process. The initial code only clears the register upon reset but doesn't continue shifting. The solution demonstrates the correct way to handle such scenarios, ensuring proper functionality even when the reset signal is active.