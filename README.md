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
```diff
+ Chapter 1
```
&emsp; &emsp; &emsp; &emsp; double.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/double.c <br>
<br>
```diff
+ Chapter 2
```
&emsp; &emsp; &emsp; &emsp; arith.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.h <br>
&emsp; &emsp; &emsp; &emsp; arith.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.c <br>
&emsp; &emsp; &emsp; &emsp; stack.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/stack.c <br>
<br>
```diff
Chapter 3
```
&emsp; &emsp; &emsp; &emsp; atom.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.h <br>
&emsp; &emsp; &emsp; &emsp; atom.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.c <br>
<br>
```diff
Chapter 4
```
&emsp; &emsp; &emsp; &emsp; except.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.h <br>
&emsp; &emsp; &emsp; &emsp; except.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.c <br>
&emsp; &emsp; &emsp; &emsp; assert.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.h <br>
&emsp; &emsp; &emsp; &emsp; assert.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.c <br>
<br>
```diff
Chapter 5
```
&emsp; &emsp; &emsp; &emsp; mem.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.h <br>
&emsp; &emsp; &emsp; &emsp; mem.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.c <br>
&emsp; &emsp; &emsp; &emsp; memchk.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/memchk.c <br>
<br>
```diff
Chapter 6
```
&emsp; &emsp; &emsp; &emsp; arena.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.h <br>
&emsp; &emsp; &emsp; &emsp; arena.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.c <br>
<br>
```diff
Chapter 7
```
&emsp; &emsp; &emsp; &emsp; list.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.h <br>
&emsp; &emsp; &emsp; &emsp; list.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.c <br>
<br>
```diff
Chapter 8
```
&emsp; &emsp; &emsp; &emsp; table.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.h <br>
&emsp; &emsp; &emsp; &emsp; getword.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.h<br>
&emsp; &emsp; &emsp; &emsp; getword.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.c <br>
&emsp; &emsp; &emsp; &emsp; table.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.c <br>
<br>
```diff
Chapter 9
```
&emsp; &emsp; &emsp; &emsp; set.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.h <br>
&emsp; &emsp; &emsp; &emsp; set.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.c <br>
<br>
```diff
Chapter 10
```
&emsp; &emsp; &emsp; &emsp; array.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.h <br>
&emsp; &emsp; &emsp; &emsp; arrayrep.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arrayrep.h <br>
&emsp; &emsp; &emsp; &emsp; array.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.c <br>
<br>
```diff
Chapter 11
```
&emsp; &emsp; &emsp; &emsp; seq.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.h <br>
&emsp; &emsp; &emsp; &emsp; seq.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.c <br>
<br>
```diff
Chapter 12
```
&emsp; &emsp; &emsp; &emsp; ring.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.h <br>
&emsp; &emsp; &emsp; &emsp; ring.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.c <br>
<br>
```diff
Chapter 13
```
&emsp; &emsp; &emsp; &emsp; bit.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.h <br>
&emsp; &emsp; &emsp; &emsp; bit.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.c <br>
<br>
```diff
Chapter 14
```
&emsp; &emsp; &emsp; &emsp; fmt.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.h <br>
&emsp; &emsp; &emsp; &emsp; fmt.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.c <br>
<br>
```diff
Chapter 15
```
&emsp; &emsp; &emsp; &emsp; str.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.h <br>
&emsp; &emsp; &emsp; &emsp; ids.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ids.c <br>
&emsp; &emsp; &emsp; &emsp; str.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.c <br>
<br>
```diff
Chapter 16
```
&emsp; &emsp; &emsp; &emsp; text.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/test.h <br>
&emsp; &emsp; &emsp; &emsp; text.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/text.c <br>
<br>
```diff
Chapter 17
```
&emsp; &emsp; &emsp; &emsp; xp.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.h <br>
&emsp; &emsp; &emsp; &emsp; xp.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.c <br>
<br>
```diff
Chapter 18
```
&emsp; &emsp; &emsp; &emsp; ap.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.h <br>
&emsp; &emsp; &emsp; &emsp; calc.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/calc.c <br>
&emsp; &emsp; &emsp; &emsp; ap.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.c <br>
<br>
```diff
Chapter 19
```
&emsp; &emsp; &emsp; &emsp; mp.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.h <br>
&emsp; &emsp; &emsp; &emsp; mpcalc.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mpcalc.c <br>
&emsp; &emsp; &emsp; &emsp; mp.c https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.c <br>
<br>
```diff
Chapter 20
```
&emsp; &emsp; &emsp; &emsp; thread.h https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/thread.h <br>
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
