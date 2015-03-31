Diamond Kata
============

This project contains sourcefiles and a skeleton for a solution to the Diamond Kata. You can of course just code
this kata from scratch in any way you wish. This repo will help you to explore two different approaches to the
problem - an interative approach, where you 'recycle' test cases, and an incremental approach, where all test cases
are valid for the full solution.

Kata Description
----------------

(this description is copied from http://cyber-dojo.org)

Given a letter print a diamond starting with 'A'
with the supplied letter at the widest point.

For example: print-diamond 'E' prints

<pre>
    A
   B B
  C   C
 D     D
E       E
 D     D
  C   C
   B B
    A
</pre>
For example: print-diamond 'C' prints

<pre>
  A
 B B
C   C
 B B
  A
</pre>

How to use the code in this repo
--------------------------------

* For an 'incremental' approach, test drive your implementation using 'DiamondIncrementalSpec.scala'.
* For an 'iterative' approach, test drive your implementation using 'DiamondIterativeSpec.scala'.

I suggest you try the kata both ways. In a Coding Dojo, you could have half the group do it one way while the other
half does it the other way, then swap. Suggested questions for the retrospective when you compare the approaches:

* How easy is it to proceed in small steps?
* How easy is it to pinpoint what is wrong when you make a mistake?
* How easy is it to refactor the implementation?
* Should 'one_row' be public in the Diamond class? What would happen if it wasn't?
* Which approach (iterative or incremental) should you use when doing TDD in general?