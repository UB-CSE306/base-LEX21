# LEX19

## Overview

In this lab exercise you will be working with the memcheck tool from the valgrind suite. In class yesterday, we explored several errors that memcheck can detect and discussed what code problems can give rise to them. In this exercise, you get to explore memory problems in some code, with the goal being to resolve them.

The exercise is split into two parts, partA and partB.  The code for each part is its own directory.  Start with partA and then move on to partB.

Apply good development and debugging practices, including use of a GitHub repo and branching as appropriate.  When you run valgrind, use either of these forms:

```bash
   valgrind --tool=memcheck --leak-check=yes -v ./main
   valgrind --tool=memcheck --leak-check=yes ./main
```

You may incorporate these into targets in the makefiles to make running the code easier.

## Getting to work

Open [the LEX 19 response form](https://docs.google.com/forms/d/e/1FAIpQLSePxUcwwaLPKRC12tQTGc44uG1vCNmToKrdPpxawv1CzKWKvw/viewform?usp=sf_link), follow the instructions and put answers to questions into the form.

It is **very important** that you add/commit/push your changes at least as often as indicated in the response form: we need to see that you followed the steps indicated, and we need to see what output your program produce at selected points in time.  If you don't do this we cannot properly assess your work.

You are also expected to use git branching and merging sensibly as you work your way through this LEX, to give you additional practice before the lab practical exams which are on the horizon.

## Finishing up

Open [the LEX 19 feedback form](https://docs.google.com/forms/d/e/1FAIpQLScmF7Yv0GCgl11YAc0d3_xfuk0SPaj6vhqeRkDPb7GeBcgM6g/viewform?usp=sf_link) and give your thoughts on this lab exercise.
