CILK programs to do matrix operations.
Matrix addition with static work division : matAddStat.cilk

Compile with 
./cilkc matAddStat.cilk -o madd -DCILKC

Note:
If you get error in waitstatus.h file, #ifndef the line with "CILKC" flag.
eg:
#ifndef CILKC
	/* erring line*/
#endif
