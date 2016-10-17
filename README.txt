CS 422S - Operating Systems
Spring 2016
Team Members: David Ayeke ,Joseph Woodson ,Edwin Munguia

Project 2 - Part 2
  A. XV6 Virtual address translate
  B. XV6 Dereference Null Pointer

Grab Modified files and replaced them in your XV6 directory and then run "make"

A. VA -> PA
  Created a new SYSCALL named translate(). This syscall will take in a Virtual Address
  and turn into a Physical Address.

  i. Created a user program called translateTest.c that will test the system call.
  Makefile was modified to add this user program. translateTest will pass in a
  mock virtual address, and will print to console the physical address and then
  exit gracefully.
  ii. type: translateTest    into XV6 to run.


B. Dereference Null Pointer
  Created a user program called dereferenceNull.c and modified Makefile accordingly
  to add this program. Using XV6 console and qemu, type "dereferenceNull" to run
  the test. Should return a trap.
