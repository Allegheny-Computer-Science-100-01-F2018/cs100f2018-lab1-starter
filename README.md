
# cs100f2018-lab1-starter

Designed for use with [GitHub Classroom](https://classroom.github.com/), this
repository contains the solution for Laboratory 1 assignment in Computer Science 100. Since the Travis builds for this repository will initially fail (as evidenced by
a red &#x2717; appearing in the commit logs instead of a green &#x2714;), the
programmer is responsible for completing all of the steps needed to satisfy the
requirements for the assignment, thus causing a &#x2714; to instead appear in
the commit logs.


## Introduction

This assignment requires a programmer to implement and test a Java program,
called `DisplayOutput`, that will produce four lines of output. The first line
of output will contain the name of the programmer and the date at which the
program was run. The next three lines of output will feature any one-sentence
and one-line statements of advice that the programmer would like to provide to
the person using the program. As verified by
[Checkstyle](https://github.com/checkstyle/checkstyle), the source code for the
`DisplayOutput.java` file must adhere to all of the requirements in the [Google
Java Style Guide](https://google.github.io/styleguide/javaguide.html).

The programmer is also responsible for writing a one-paragraph reflection,
stored in the file `writing/reflection.md`, that explains the challenges that
you faced and the solutions you developed. This is a Markdown file that must
adhere to the standards described in the [Markdown Syntax
Guide](https://guides.github.com/features/mastering-markdown/). Remember, you
can preview the contents of a committed Markdown file by clicking on the name
of the file in your GitHub repository.

The source code in the `DisplayOutput.java` file must also pass additional tests
set by the [GatorGrader tool](https://github.com/GatorEducator/gatorgrader). For
instance, GatorGrader will check to ensure that `DisplayOutput` produces exactly
four lines of output and that you use the `new Date()` construct in the Java
code. When you use the `git commit` command to transfer your source code to your
GitHub repository, [Travis CI](https://travis-ci.com/) will initialize a build
of your assignment, checking to see if it meets all of the requirements. If
your source code meet all of the established requirements, then you
will see a green &#x2714; in the listing of commits in GitHub. If your
submission does not meet the requirements, a red &#x2717; will appear instead.
The instructor will reduce a programmer's grade for this assignment if the red
&#x2717; appears on the last commit in GitHub immediately before the
assignment's due date.

Available for download at the course website [course
website](http://www.cs.allegheny.edu/sites/jjumadinova/teaching/100/labs.html),
the carefully formatted assignment sheet for this project provides more details
about the steps that a computer scientist should take to complete this
assignment.

## Learning

If you have not done so already, please read all of the relevant [GitHub
Guides](https://guides.github.com/) that explain how to use many of the features
that GitHub provides. In particular, please make sure that you have read the
following GitHub guides: [Mastering
Markdown](https://guides.github.com/features/mastering-markdown/), [Hello
World](https://guides.github.com/activities/hello-world/), and [Documenting Your
Projects on GitHub](https://guides.github.com/features/wikis/). Each of these
guides will help you to understand how to use both [GitHub](http://github.com) and
[GitHub Classroom](https://classroom.github.com/).

To do well on this assignment, you should also read Chapters 1 and 2 in the
course textbook, paying particularly close attention to Sections 1.5 and 2.1.
Please see the course instructor or one of the teaching assistants or tutors if
you have questions about any of these reading assignments.

## Commands

To get started in using the GatorGrader tool, you can change into the directory
for this assignment and type the command `gradle grade` in your terminal.
Running this command will produce a lot of output that you should carefully
inspect. If the output indicates that GatorGrader judges that there are no
mistakes in the assignment, then this means that your source code and writing
are passing all of the automated baseline checks. However, if the output
indicates that there are mistakes, then you will need to understand what they
are and then try to fix them.

You can also complete several important Java programming tasks by using the
`gradle` tool. For instance, you can compile (i.e., create bytecode from the
program's source code if it is a correct program) the program using the command
`gradle build`. There are other additional commands that you can type:

- `gradle clean`: clean the project of all the derived files
- `gradle check`: check the quality of the code using Checkstyle
- `gradle build`: create the bytecode from the Java source code
- `gradle run`: run the Java program in the command-line
- `gradle tasks`: display details about the Gradle system

To run one of these commands, you must be in the main (or "home base") directory
for this assignment where the `build.gradle` file is located. Then, you can type
the command in the terminal and study the output.

## Output

Typing the command `gradle run` in the terminal window produces the following
output for the instructor's version of `DisplayOutput`. As long as your program
adheres to all of the requirements for the assignment and passes all of the
verification checks, your version may produce (partially) different output.

```
> Task :run
Janyl Jumadinova Mon Sep 03 18:27:48 EDT 2018
Welcome to programming.
Github is awesome.
Java is cool.


BUILD SUCCESSFUL in 0s
2 actionable tasks: 1 executed, 1 up-to-date
```

## Checks

Your submission must pass the following checks:

- labone/DisplayOutput.java:
  - Feature two single-line comments
  - Feature two multiple-line comments
  - Contain four uses of a `println(` statement
  - Contain one use of a `new Date(` statement
  - Produce four lines of output in the terminal

- writing/reflection.md:
  - Contains one contiguous paragraph of formatted text
  - Contains one paragraph containing at least 150 words

- GitHub repository:
  - Contains two commits beyond the starting number

## Travis

This assignment uses [Travis CI](https://travis-ci.com/) to automatically run
the checking programs every time you commit to your GitHub repository. The
checking will start as soon as you have accepted the assignment, thus creating
your own private repository, and the course instructor enables Travis for it. If
you are using Travis for the first time, you will need to authorize Travis CI to
access the private repositories that you created on GitHub. If you do not see either a yellow circle or a green checkmark or a red x
in your listing of commits, then please ask the instructor to see whether or not
Travis CI was correctly enabled.

## Requirements

The GatorGrader software that supports the checking of this assignment was
developed for the following software and versions:

- Gradle 4.6
- Java 1.8.0
- MDL 0.4.0
- Proselint 0.8.0
- Python 3.6

## Problems

If you have found a problem with this assignment's provided source code, then
you can go to the [Computer Science 100 Lab 1
Starter](https://github.com/Allegheny-Computer-Science-100-01-F2018/cs100f2018-lab1-starter)
repository and create an issue by clicking the "Issues" tab and then clicking
the green "New Issue" button.If you have found a problem with the [GatorGrader
tool](https://github.com/GatorEducator/gatorgrader) and the way that it checks
you assignment, then you can follow the aforementioned steps to create an issue
in its repository. To ensure that your issue is properly resolved, please
provide as many details as is possible about the problem that you experienced.

Students who find, and use the appropriate GitHub issue tracker to correctly
document, a mistake in any aspect of this laboratory assignment will receive
 extra credit towards their grade for it.

## Assistance

If you are having trouble completing any part of this project, then please talk
with either the course instructor or a teaching assistant during the laboratory
session. Alternatively, you may ask questions in the Slack team for this
course. Finally, you can schedule a meeting during the course instructor's
office hours.
