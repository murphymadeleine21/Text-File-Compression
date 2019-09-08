# Text-File-Compression
Given an old and new text file, program can write a smaller "diff" file with instructions for the new file using the old. Demonstrates use of hash tables, linked lists, and use of the hash function.

Given two files that only differ in a few ways, sending the entire new file is costly in terms of space. This program searches through the two files and finds the similarities, and then writes an instruction "diff" file which can then be applied to write out the entire new file using the old.
