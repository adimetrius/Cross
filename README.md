# Cross
Cross-compiling replica of CP2 compiler

CP2 is the standard compiler shipped with BlackBox Component Framework. 
It is not cross-compiling: it compiles modules on the base of modules in the 
current (running) system, which the compiler is a part of.

Cross is a slightly modified version of CP2 that performs cross-compilation: 
that is, it can pick up symbol files for imported modules, 
and output symbol and code files for compiled modules, 
from and into explicitly specified primary and secondary bases (directories).

