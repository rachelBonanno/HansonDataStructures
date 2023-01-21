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
&emsp; double.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/double.c <br>
<br>
```diff
+ Chapter 2
```
&emsp; arith.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.h <br>
&emsp; arith.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arith.c <br>
&emsp; stack.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/stack.c <br>
<br>
```diff
+ Chapter 3
```
&emsp; atom.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.h <br>
&emsp; atom.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/atom.c <br>
<br>
```diff
+ Chapter 4
```
&emsp; except.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.h <br>
&emsp; except.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/except.c <br>
&emsp; assert.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.h <br>
&emsp; assert.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/assert.c <br>
<br>
```diff
- Chapter 5
```
&emsp; mem.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.h <br>
&emsp; mem.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mem.c <br>
&emsp; memchk.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/memchk.c <br>
<br>
```diff
- Chapter 6
```
&emsp; arena.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.h <br>
&emsp; arena.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arena.c <br>
<br>
```diff
+ Chapter 7
```
&emsp; list.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.h <br>
&emsp; list.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/list.c <br>
<br>
```diff
+ Chapter 8
```
&emsp; table.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.h <br>
&emsp; getword.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.h<br>
&emsp; getword.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/getword.c <br>
&emsp; table.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/table.c <br>
<br>
```diff
+ Chapter 9
```
&emsp; set.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.h <br>
&emsp; set.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/set.c <br>
<br>
```diff
- Chapter 10
```
&emsp; array.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.h <br>
&emsp; arrayrep.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/arrayrep.h <br>
&emsp; array.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/array.c <br>
<br>
```diff
+ Chapter 11
```
&emsp; seq.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.h <br>
&emsp; seq.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/seq.c <br>
<br>
```diff
- Chapter 12
```
&emsp; ring.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.h <br>
&emsp; ring.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ring.c <br>
<br>
```diff
- Chapter 13
```
&emsp; bit.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.h <br>
&emsp; bit.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/bit.c <br>
<br>
```diff
- Chapter 14
```
&emsp; fmt.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.h <br>
&emsp; fmt.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/fmt.c <br>
<br>
```diff
- Chapter 15
```
&emsp; str.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.h <br>
&emsp; ids.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ids.c <br>
&emsp; str.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/str.c <br>
<br>
```diff
- Chapter 16
```
&emsp; text.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/test.h <br>
&emsp; text.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/text.c <br>
<br>
```diff
- Chapter 17
```
&emsp; xp.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.h <br>
&emsp; xp.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/xp.c <br>
<br>
```diff
- Chapter 18
```
&emsp; ap.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.h <br>
&emsp; calc.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/calc.c <br>
&emsp; ap.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/ap.c <br>
<br>
```diff
- Chapter 19
```
&emsp; mp.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.h <br>
&emsp; mpcalc.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mpcalc.c <br>
&emsp; mp.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/mp.c <br>
<br>
```diff
- Chapter 20
```
&emsp; thread.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/thread.h <br>
&emsp; sem.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sem.h <br>
&emsp; chan.h &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/chan.h <br>
&emsp; sort.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sort.c <br>
&emsp; spin.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/spin.c <br>
&emsp; sieve.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/sieve.c <br>
&emsp; chan.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/chan.c <br>
&emsp; thread.c &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/thread.c <br>
&emsp; swtch.s &emsp; &emsp; &emsp; https://github.com/rachelBonanno/HansonDataStructures/blob/main/code/swtch.s <br>

```diff 
! See David R Handsons GitHub for other code ! 
``` 
<p align="center"> https://github.com/drh/cii <p>
