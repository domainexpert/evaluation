`klee-out-1` was created by the following run:
```
klee -precision -no-branch-check -loop-breaking -libc=uclibc -max-time=1 ./sor.bc
```