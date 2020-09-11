# RTOS
RTOS lab session programs
# Meghna Barthwal
# Roll no: 45
# SAP ID: 500067359
# Batch: CSE-IOT B1
# RTOS Session0 Q1
The segmets should be run differently. This file contains different code segments.
1. This is the base program to compare.
2. Introducing an uninitialized global variable, for change in bss.
3. Introducing an initialized global variable, for change in data.
4. Introducing an uninitialized static variable, for change in bss.
5. Introducing an initialized static variable, for change in data.
6. Introducing function call, for change in text.

compile: gcc lab1q1.c -o lab1q1.exe 
run: size lab1q1.exe

![output screen shot memorymap](Screenshot (187).png)


# RTOS Session0 Q2
There is a delay function given by user. It will count the number upto that but if we type anything in between except esc than the delay function will restart.
