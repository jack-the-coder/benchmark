# benchmark

This repository contains a dead-simple benchmark. It does nothing more than hog 100% of a single core of your CPU for a while, and then exit. To get an accurate benchmark result, simply run `time ./a.out` (assuming `a.out` is executable). 

If `a.out` does not run on your system, for some odd reason, you can try running `cc benchmark.c` to get a new executable file to run. Compilation should be instant. 

## Hall of Fame Times: 

- My computer: (i5-7400): `./a.out  264.72s user 0.01s system 100% cpu 4:24.71 total` (or, in other words, it took 4 minutes and 24.71 seconds). 
- @eado's MacBook Pro (i7-7820HQ): `./a.out  259.96s user 0.65s system 99% cpu 4:21.63 total` (4 minutes and 21.63 seconds).

