# Text-file-compressor
This is a text file compressor based on Huffman coding algorithm

This project is based on Huffman Coding, a lossless, bottom-up compression algorithm. It can compress and decompress any text files.

Implementation in Project

This project supports two functions:
1) Encode: Compresses input file passed.
2) Decode: Decompresses Huffman coded file passed back to its original file.

# Commands to run the code

g++ encode.cpp huffman.cpp -o encode

./encode inputFile.txt compressed.bin

g++ decode.cpp huffman.cpp -o decode

./decode compressed.bin output.txt
