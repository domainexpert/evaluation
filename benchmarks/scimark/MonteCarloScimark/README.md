`klee-out-6` was created by the following run:
```
klee -precision -no-branch-check -loop-breaking -libc=uclibc -max-time=1 ./montecarlo.bc
```