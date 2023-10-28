# Operating Systems: Consumer-Producer 

This code implements a producer and consumer program that communicate through a bounded buffer in shared memory.

# Compilation:
gcc producer.c -lrt -o producer
gcc consumer.c -lrt -o consumer

# Running:
The producer program (parent) takes the following three command-line arguments (all integers):
1. The size of the bounded buffer (bufSize). This is the number of items that can fit in the
bounded buffer. Valid range is (2, 500)
2. The number of items to produce/consume (itemCnt). 
3. A seed for the random number generator (randSeed). 
