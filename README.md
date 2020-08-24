# 8-bit-computer

RAM


A computer needs a place to store the program we would like it to execute. This is achieved by Random Access Memory, this computer has 16 bytes of RAM. it utilizes the 7415189 which is 64 bits organized as a 16 word by 4 bit array. in order to have 16 bytes 2 chips were used. As evident in the logic diagram, the memory contents are accessed by selecting 4 address lines (4 bits for a total of 16 slots). There is also a data buffer that enables writing to a memory location when chip select and write enable pins are low (active low). I wanted to be able to manually address the RAM while also having the ability to accept values from the Bus. This was achieved by using a QUAD 2 input multiplexer (74ls157). I used a similar circuit to manually program the RAM by utilizing 2 74ls157 chips.

