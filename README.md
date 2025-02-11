# Java ArrayIndexOutOfBoundsException Bug
This repository contains a simple Java program that demonstrates an ArrayIndexOutOfBoundsException. The bug is caused by an incorrect loop condition that attempts to access an array element beyond its bounds. The solution demonstrates how to correct the loop condition to avoid the error.

## Bug
The `bug.java` file contains the buggy code. The for loop iterates one element beyond the array's size, causing an `ArrayIndexOutOfBoundsException`.

## Solution
The `bugSolution.java` file provides the corrected code with the proper loop condition. The loop now correctly iterates up to but not including `arr.length`, preventing the index from going out of bounds. 
