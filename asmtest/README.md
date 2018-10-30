Submitted assembly tests will go here

After submitting your test program, you may use any of these programs written by your peers to test your processor.


In addition to your actual test assembly code, write a short README with:
 - Expected results of the test
 - Any memory layout requirements (e.g. `.data` section)
 - Any instructions used outside the basic required subset (ok to use, but try to submit at least one test program everyone can run)

Submit the test program and README by submitting a pull request to the main course repository. Code should be in `/asmtest/<your-team-name>/` (you may use subfolders if you submit multiple tests).

This is our assembly code for finding the nth fibonacci term. $t0 and $t1 hold the first 2 fibonacci terms. One can find the nth fibonacci term by inputting n into $t2.

This just uses the temp registers 0 through 3 and $v1 to output the result.

All of the functions are those that the single cycle MIPS CPU can execute
