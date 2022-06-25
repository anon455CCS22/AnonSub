# time-deniable-sigs

This is an anonymized impelementation of Time Deniable Signatures. It uses a modification of an existing Gentry-Silverberg HIBE implementation with key re-randomization and an implementation of an RSW time lock puzzle.

This codebase utilizes [charm](https://github.com/JHUISI/charm) and requires it to be installed. Charm has dependencies on GMP, PBC, and Openssl. Instructions for installation can be found [here](https://github.com/JHUISI/charm/blob/dev/INSTALL).   

The code of main.py in directory code/ currently produces benchmarks for N in the ranges specified in the paper. 

You can run tests w. python3 main.py test. The tests should take 3-4 min

HIDE/ - this is Gentry-Silverberg's HIDE scheme

 

