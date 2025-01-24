# VHDL Counter with Reset Bug

This repository demonstrates a common subtle bug in VHDL code related to counter resets. The provided `bug.vhdl` file contains a counter implementation that may not reset to 0 correctly under certain conditions.  The `bugSolution.vhdl` file offers a corrected version.

## Bug Description

The original counter code has an issue in its reset handling. In specific situations, the counter might not consistently reset to zero, leading to unpredictable behavior.  This is a subtle off-by-one error that could go undetected.