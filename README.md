##LaTeX package for including correct answers and solutions 

in a multiple choice exam.

Use
```
\usepackage[margin]{correctanswer}
```
to mark correct answers in the margin, or use `here` to insert the correct
answers in the text, or `end` to generate a separate page of correct answers at
the end. Option `watermark` produces a watermark that distinguishes a copy with
answers from a copy without answers.

Include answers by
```
\correct(-1\baselineskip){C}
```
to indicate that `C` is the correct choice.

There are other options, that I need to describe.

TODO: write documentation and fix this README so it sucks less.
