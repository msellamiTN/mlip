# mlip Machine Learning in Python

Worked out programs from Machine Learning in Python by Michael Bowles. Since I 
know Matlab and R more than Python, my purpose was to work through the book by
Bowles and understand how to implement penalized regression and ensemble methods
in Python.

A strength of the book is the concise code and the implementation of each algorithm from scratch. Bowles implements Ridge, LASSO, and LARS from scratch before using the scikit-learn module. This helps you see what is going on.

On the downside, the code is not modularized, and therefore in many of the programs the same code is replicated. Additionally, the code that is used is not written in function form. Instead, the layout of the code is in one long script, which makes focusing on specific portions more difficult.

Because of these issues, I first wrote out the programs that Bowles has listed in the book. Then, I made a few changes to the programs.

Starting with Chapter 4, I wrote function definitions for the programs. I'm currently trying to better organize the code into modules. 

Also, the programs have been modified to read data from disk. The programs in the book are written so that data is read through URLs at the UC Irvine Machine Learning Repository. However, since I code away from WiFi on occasion, often while I'm on BART, I downloaded the data to disk. The files that I downloaded were: sonar.all-data, winequality.csv, and abalone.dat. The functions that I wrote read in the data from these data files.

This is currently a work in progress


