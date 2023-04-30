Download Link: https://assignmentchef.com/product/solved-csc4103-assignment1-multithreading
<br>
To learn the use of POSIX Pthreads or Java Threads

<h1>Background</h1>

Modern operating systems provide features for a process to use multiple threads to speed up accesses. In the class, we have learned the concepts associated with multithreaded computer systems, such as multithreading models. There are various thread libraries. POSIX Pthreads, and Java Threads are widely used for creating and manipulating threads.  The textbook (Threads, Chapter 4) gives examples of multithreaded programs using these libraries.

<h1>Programming Task</h1>

In this assignment, you need to implement the <strong>Project – Matrix Multiplication </strong>given in the textbook (Chapter 4, 8<sup>th</sup> edition), which is also attached in this project description.  Your program will calculate each element <strong><em>C<sub>i,j</sub></em></strong> of the matrix product <strong><em>C</em></strong> of two matrices <strong><em>A</em></strong> and <strong><em>B</em></strong> using an individual/separate thread.  So, the number of threads is equal to the number of terms in the matrix product. Use either <strong>POSIX Pthreads or Java threads</strong> to implement this program.  The matrices to be multiplied are:




“1 4%

$      ‘                   “8 7 6%

<em>A </em>=$2 5′    and <em>B </em>=$#5  4 3’&amp;

$#3  6’&amp;

<strong><u>Programming Language</u> </strong>

C/C++ or Java

All files you submit must have a <strong>header</strong> with the following (enclosed in comment lines):

You need to use the server “<strong>classes.csc.lsu.edu</strong>” to work on the assignment. You can login to your account in the server using SSH. Create a directory <strong>prog1</strong> (by typing <strong>mkdir prog1) </strong>in your home directory in which you create your program or source code.




Make sure that you are in the <strong>prog1</strong> directory while submitting your program. Submit your assignment to the grader by typing the following command:

<strong>         ~cs4103_chf/bin/p_copy 1 </strong>

This command copies everything in your prog1 directory to the grader’s account. Check whether all required files have been submitted successfully:

<strong>         ~cs4103_chf/bin/verify 1 </strong>





