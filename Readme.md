# What is is?

This code is a modification of the MemoryModule code from Joachim Bauch.
    which can be found at https://github.com/fancycode/MemoryModule

It has been modified to be more evasive towards static analysis and to support loading from memory.

# Why?

The required for this modifications come from the use functions being reflected in IAT.
this causes the the exe to be flagged as suspicious by AVs.

Soo these modifications are done to avoid this detection.

These modifications are done by Arth Maurya
https://github.com/Oorth