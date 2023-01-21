# Hanson Data Structures
C Interfaces and Implementations Techniques for Creating Reusable Software By David R. Hanson <br>
Extractions of code in the book in a more readable format.<br>

## Chapters Assigned in CS40@Tufts
Hanson: Ch. 1 & 2; Intro and First Section (titled "Interface") of Ch. 3-4, 7-9, 11; Section 8.2 <br>

## Breakdown of Hanson Chapters
```diff
@@ Foundations @@
+ 1. Introduction
+ 2. Interfaces and Implementations
+ 4. Exceptions and Assertions
- 5. Memory Management
- 6. More Memory Management
```
```diff
@@ Data Structures @@
+ 7. Lists
+ 8. Tables
+ 9. Sets
- 10. Dynamic Arrays
+ 11. Sequences
- 12. Rings
- 13. Bit Vectors
```
```diff
@@ Strings @@ 
+ 3. Atoms
- 14. Formatting
- 15. Low-Level Strings
- 16. High-Level Strings
```
```diff
@@ Arithmetic @@
- 17. Extended-Precision Arithmetic
- 18. Arbitrary-Precision Arithmetic
- 19. Multiple-Precision Arithmetic
```
```diff
@@ Threads @@
- 20. Threads
```

```diff
! Interface Summary 
# starts on page 470 in textbook
```

## Code in Book
Chapter 1: double.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/double.c <br>
Chapter 2: arith.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; arith.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.c <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; stack.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/stack.c <br>
Chapter 3: atom.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; atom.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.c <br>
Chapter 4: except.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; except.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.c <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; assert.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; assert.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.c <br>
Chapter 5: mem.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; mem.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.c <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; memchk.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/memchk.c <br>
Chapter 6: arena.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; arena.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.c <br>
Chapter 7: list.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; list.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.c <br>
Chapter 8: table.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; getword.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.h<br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; getword.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.c <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; table.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.c <br>
Chapter 9: set.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.h <br>
&emsp; &emsp; &emsp; &nbsp; &nbsp; set.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.c <br>
Chapter 10: array.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.h <br>
&emsp; &emsp; &emsp; &emsp; arrayrep.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arrayrep.h <br>
&emsp; &emsp; &emsp; &emsp; array.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.c <br>
Chapter 11: seq.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.h <br>
&emsp; &emsp; &emsp; &emsp; seq.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.c <br>
Chapter 12: ring.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.h <br>
&emsp; &emsp; &emsp; &emsp; ring.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.c <br>
Chapter 13: bit.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.h <br>
&emsp; &emsp; &emsp; &emsp; bit.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.c <br>
Chapter 14: fmt.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.h <br>
&emsp; &emsp; &emsp; &emsp; fmt.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.c <br>
Chapter 15: str.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.h <br>
&emsp; &emsp; &emsp; &emsp; ids.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ids.c <br>
&emsp; &emsp; &emsp; &emsp; str.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.c <br>
Chapter: 16 text.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/test.h <br>
&emsp; &emsp; &emsp; &emsp; text.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/text.c <br>
Chapter 17: xp.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.h <br>
&emsp; &emsp; &emsp; &emsp; xp.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.c <br>
Chapter 18: ap.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.h <br>
&emsp; &emsp; &emsp; &emsp; calc.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/calc.c <br>
&emsp; &emsp; &emsp; &emsp; ap.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.c <br>
Chapter 19: mp.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.h <br>
&emsp; &emsp; &emsp; &emsp; mpcalc.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mpcalc.c <br>
&emsp; &emsp; &emsp; &emsp; mp.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.c <br>
Chapter 20: thread.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/thread.h <br>
&emsp; &emsp; &emsp; &emsp; sem.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sem.h <br>
&emsp; &emsp; &emsp; &emsp; chan.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/chan.h <br>
&emsp; &emsp; &emsp; &emsp; sort.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sort.c <br>
&emsp; &emsp; &emsp; &emsp; spin.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/spin.c <br>
&emsp; &emsp; &emsp; &emsp; sieve.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sieve.c <br>
&emsp; &emsp; &emsp; &emsp; chan.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/chan.c <br>
&emsp; &emsp; &emsp; &emsp; thread.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/thread.c <br>
&emsp; &emsp; &emsp; &emsp; swtch.s https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/swtch.s <br>

```diff 
! See David R Handsons GitHub for other code ! 
``` 
<p align="center"> https://github.com/drh/cii <p>
