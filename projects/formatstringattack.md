---
layout: project
type: project
image: img/Screenshot 2023-08-31 180430.png
title: "Format String Attack"
date: 2023
published: true
labels:
  - Linux Security
  - Python
summary: "To learn about string format vulnerabilities."
---

<img class="img-fluid" src="../img/Screenshot (47) crop.png">

The printf() function in C is used to print out a string according to a format. Its first argument is called
format string, which defines how the string should be formatted. Format strings use placeholders marked
by the % character for the printf() function to fill in data during the printing. The use of format strings
is not only limited to the printf() function; many other functions, such as sprintf(), fprintf(),
and scanf(), also use format strings. Some programs allow users to provide the entire or part of the
contents in a format string. If such contents are not sanitized, malicious users can use this opportunity to get
the program to run arbitrary code.

The objective of this lab is for students to gain the first-hand experience on format string vulnerabilities
by putting what they have learned about the vulnerability from class into actions. Students will be given a
program with a format string vulnerability; their task is to exploit the vulnerability to achieve the following
damage: (1) crash the program, (2) read the internal memory of the program, (3) modify the internal memory of the program, and most severely, (4) inject and execute malicious code using the victim program’s
privilege
