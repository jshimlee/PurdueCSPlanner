# PurdueCSPlanner

Project Goal:

This tool will help incoming and current Purdue students plan their CS degree. It takes a selected track, electives, and AP credits, and builds a sample roadmap by semester for a Purdue CS degree. It will respect course prerequisites and degree requirements.

MVP scope:
The tool will be written in Java and will be limited to terminal output. All course, prerequisite, and requirement data will be entered by hand in .txt files. The User enters course and AP data in terminal to minimize complexity.

Example output for a student with AP Calculus AB credit:

Fall 2026
  CS 180  Object Oriented Programming    (4 credits)
  MA 162  Calculus II                    (4 credits)
  (Written communication elective)       (3 credits)
  (Culture elective)                     (3 credits)

Spring 2027
  CS 182 Foundations of Computer Science (3 credits)
  CS 240 Programming in C                (3 credits)
  MA 261 Multivariable Calculus          (4 credits)
  (Oral communication elective)          (3 credits)

  ...

Tech stack:
Contains only .java and .txt files, terminal I/O
MVP contains external libraries; the standard library only

Future Plans:
  - Include functionality outside CS degree
  - Add support for completed credits for current students
  - Full stack public website
  - Save user info in database with google login

