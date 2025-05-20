# Data-Structure-Assignments
## Overview
This repo showcases my understanding of fundamental data structures and algorithms. These assignments were completed as part of my coursework at Drexel University. 

## Assignments
Assignment 1: This C program implements a dynamic list and allows insertion, deletion, and search operations with automatic resizing of memory. Commands are read from a file and executed in real time. The program demonstrates efficient memory management and dynamic data structure handling.

Assignment 2: This C program implements an autocomplete suggestion system. It reads a dictionary of words with associated weights and a list of query words, then outputs up to the top 10 matching dictionary entries (by prefix and weight) for each query. Memory is dynamically managed to store dictionary entries and ensure clean deallocation at the end.

Assigment 3: This C program implements a basic spell checker using an open addressing hash table. It reads words from a dictionary file into a hash table, then scans an input text file for words. If a word isn't found in the dictionary, it prints the word as misspelled and suggests corrections based on transposed, missing, or extra letters. Optional insertion of misspelled words into the dictionary can be added by a command-line flag.

Assignment 4: This program compresses text files using Huffman encoding by building a frequency-based binary code for each character. It outputs a code table and an encoded file, along with compression statistics. Uses the encode mode with input and output file paths to run the compression.

Assignment 5: This program solves the sliding puzzle (like the 8-puzzle) using a breadth-first search with a hash table to avoid repeated states. It reads the puzzle board from a file, checks if it’s solvable, then explores moves until it finds the solution and outputs the moves taken.
