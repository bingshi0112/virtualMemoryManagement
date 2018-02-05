# virtualMemoryManagement
written in Python 3.6
This program translates logical to physical addresses. It will read from a txt file containing logical addresses and using a TLB as well as a page table, will translate each logical address to its corresponding physical address and output the value of the byte stored at the translated physical address. It will also report Page-fault rate and TLB hit rate in the end.
input: address.txt (containing 100 entries of 32 bits decimal logical addresses to be translated)
output: output.txt (containing logical address with its corresponding translated physical address, byte value stored, page-fault rate, TLB hit rate)
