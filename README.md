# cs382-lab-5-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs382-solved-7/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128075&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS382 Lab 5  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
CS 382 Computer Architecture

1 Task 1: Simple Conditionals

The first task of this lab is to write a program that check that if the given three sides can form a right triangle. A right triangle is the one that has an angle of 90 degrees, and can be verified by the following formula:

𝑐2 = 𝑎2+𝑏2

where 𝑎, 𝑏, and 𝑐 are the lengths of three sides of the triangle.

The data segment is declared as follows:

1 .data

2 side_a: .quad 3

3 side_b: .quad 4

4 side_c: .quad 5

5 yes: .string “It is a right triangle. ”

6 len_yes: .quad . – yes // Calculate the length of string yes

7 no: .string “It is not a right triangle. ”

8 len_no: .quad . – no // Calculate the length of string no

where you can assume side_c is always the longest side. If it is a right triangle, you’d need to print the string “It is a right triangle. ” ; otherwise “It is not a right triangle. ” .

To print a string, you might want to review and borrow the code from lab 2.

Requirements Note your code is a complete assembly program (not just a sequence of instructions). It should be able

to assemble, link, and execute without error and warnings. When executed, the program should finish without problems. If your code cannot assemble, you get no credit – this is the same as C programs that cannot be compiled;

MUL instruction can be used for multiplications;

You can use either CBZ / CBNZ or B.EQ / B.NE for branching;

Avoid using registers X29 and X30;

You have to put comments on each line of instruction;

2 Task 2: More Conditionals

This task is to get familiar with other conditional branching instructions such as B.LE . You are given the starter code as follows (it can also be downloaded from Canvas):

The code given to you calls C library function scanf() to receive three signed integers from keyboard (seperated

right .

Again, to print messages, you’d need to invoke system calls learned in lab 3.

Because we used C library function here, during linking, you’d need flag -lc in the command. Related information can be found in Appendix B.2.3.3 in the textbook.

Requirements Note your code is a complete assembly program (not just a sequence of instructions). It should be able

to assemble, link, and execute without error and warnings. When executed, the program should finish without problems. If your code cannot assemble, you get no credit – this is the same as C programs that cannot be compiled;

Your code should complete the task successfully without errors. Please do check edge cases;

You have to put comments on each line of instruction;

3 Grading

The lab will be graded based on a total of 10 points, 5 for task 1 and 5 for task 2. The following lists deductibles, and the lowest score is 0 – no negative scores:

Task 1:

• -5: the code does not assemble, or the program terminates abnormally/unsuccessfully;

• -5: the code is generated by compiler;

• -5: the code does not attempt the task;

• -5: the code cannot be explained clearly in person;

• -5: no output is printed;

• -5: not using conditionals;

• -3: the right triangle checking result is wrong; • -1: one or more instructions is missing comments;

• -1: no pledge and/or name.

Task 2:

• -5: the code does not assemble, or the program terminates abnormally/unsuccessfully;

• -5: the code is generated by compiler;

• -5: the code does not attempt the task;

• -5: the code cannot be explained clearly in person;

• -5: no output is printed;

• -5: not using conditionals;

• -1: 1 point off for each of the following test cases:

* -5 6 3 ;

* -5 10 -30 ;

* -6 -2 0 ;

* 3 4 3 ;

* 10 30 30 ;

* -20 20 -20 ;

• -1: one or more instructions is missing comments;

• -1: no pledge and/or name.

Attendance: check off at the end of the lab to get attendance credit.
