# Huffman-Coding
Text File compression and decompression has always been a challenging problem in the last decade. The 
purpose is to develop more effective algorithm in order to reduce the computing time and utilize lower memory 
space.
Project is to develop a text file compression/decompression tool using Huffman Coding, a lossless, bottomup compression algorithm. Huffman code is a particular type of optimal prefix code that is commonly used for 
lossless data compression. The process of finding or using such a code proceeds by means of Huffman coding
Algorithm can currently compress or decompress up to 50% of the size of any text file.
Save Storage Space
Compressing folders can prevent problems before they occur, and also save more space for youto
store other valuable content, and there will be no lag when using the computer.
Archive Documents
Compression tools are also great for archiving old files. One can compress any number of files ofthe same 
type into a single file and add corresponding notes to them, which will simplify the filesystem.
 Prevent Transmission Interruption
File compression increases data transfer speed The longer the file takes to send, the more likelythe 
transfer will be interrupted. The time required to transfer a compressed word file is one tenth of the time
required to transfer the same uncompressed file, which will greatly reduce therisk of unexpected 
interruptions, and guarantee the work efficiency.
Ensure Data Security
File compression can also hide information. In addition, it is also a good choice to pack multiplefiles
containing sensitive information with compression software and then add a password.
 Meet Server Requirements
On some Internet servers, file compression is mandatory. The server operator may not allow thetransfer 
of uncompressed files. File compression is also useful when sending email attachments,which often have 
file size limitations.
BEST APPROACH –
 Greedy algorithm is the best approach for constructing the above-mentioned program because itgreedily
searches for an optimal solution.
 The Greedy method is the simplest and straightforward approach. It is not an algorithm, but it isa 
technique. The main function of this approach is that the decision is taken on the basis of the currently 
available information. Whatever the current information is present, the decision is made without
worrying about the effect of the current decision in future.
HUFFMAN ALGORITHM -
 Huffman coding is a lossless data compression algorithm. The idea is to assign variable-lengthcodes 
to input characters, lengths of the assigned codes are based on the frequencies of corresponding 
characters. The most frequent character gets the smallest code and the least frequent character gets
the largest code.
The variable-length codes assigned to input characters are Prefix codes, means the codes (bit sequences) 
are assigned in such a way that the code assigned to one character is not the prefix ofcode assigned to 
any other character. This is how Huffman Coding makes sure that there is no ambiguity when decoding 
the generated bitstream.
 There are mainly two major parts in Huffman Coding
I. Build a Huffman Tree from input characters.
II. Traverse the Huffman Tree and assign codes to characters.
 Steps to build Huffman Tree
1. Input is an array of unique characters along with their frequency of occurrences andoutput
is Huffman Tree.
2. Create a leaf node for each unique character and build a min heap of all leaf nodes (MinHeap 
is used as a priority queue. The value of frequency field is used to compare two nodes in min
heap. Initially, the least frequent character is at root)
3. Extract two nodes with the minimum frequency from the min heap.
4. Create a new internal node with a frequency equal to the sum of the two nodes frequencies.
Make the first extracted node as its left child and the other extracted node asits right child. Add 
this node to the min heap.
5. Repeat steps#2 and #3 until the heap contains only one node. The remaining node is theroot
node and the tree is complete.
Let us understand the algorithm with an example:
 Real-life applications of Huffman Encoding-
 Huffman encoding is widely used in compression formats like GZIP, PKZIP (WinZip) and
BZIP2.
 Multimedia codecs like JPEG, PNG and MP3 uses Huffman encoding (to be more precisedthe
prefix codes)
 Huffman encoding still dominates the compression industry since newer arithmetic andrange
coding schemes are avoided due to their patent issues.
