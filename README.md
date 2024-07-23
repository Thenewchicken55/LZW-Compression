# LZW Compression Algorithm

This repository contains a Python Notebook program for compressing a text document called bible2.txt.

## Setup

To run the program, you opent he .ipynb file in your environment and run all the cells.

## Usage

### Part 1

Part 1 follows the LZW algorithm where each word is 12 bits, even ASCII characters which only need 8 bits to represent, so it's not as efficient. 

Part 1 compresses bible2.txt into bible2.txt.lzw and decompresses it back into bible2.txt.2

### Part 2

Part 2 is a modified version of part 1 where you compress using the least amount of bits as possible, first with 8 bit ascii, then with 9 bit words, then 10 bits, etc. making this more efficient than part 1

Part 2 compresses bible2.txt into bible2.txt.lzw2 and decompresses it back into bible2.txt.2M
