# STARTER-jpa00

Starter code for jpa00

Assignment Description: <https://ucsb-cs156.github.io/f20/labs/jpa00>

This lab is a simple `"Hello, World!" type assignment to familiarize
you with compiling Java using Maven, and submitting using Gradescope.

# Explanation of files

## Top level

* `README.md` It is considered good practice to document every `git` repo
  with a file called `README.md`.  The `.md` extension refers to MarkDown,
  which is a format that allows you to create nice looking documents
  working from plain text.   The source code is human readable,
  and when formatted, it looks even nicer.  The text you are reading
  right now is written in Markdown in the `README.md` file.

  
* `pom.xml` This file is similar to a `Makefile`
  when working with C/C++ programming.  This file works with a piece of
  software called Maven.

  For more information, see: <https://ucsb-cs156.github.io/topics/maven/>,
  and <https://ucsb-cs156.github.io/topics/maven_hello_world/>, where both
  Maven, and the specific `pom.xml` in this project are explained in detail.

* `src` This directory contains the source code for this project.

  All Maven projects must have a `src` directory at the top level.

* `src/main/java`  This directory is the directory where all Java code
  for a Maven project (other than test code) is expected to live.

  Once we introduce *packages*, we'll also see levels of directories
  under `src/main/java` that correspond to the package structure,
  but for simple projects without packages, we put our code directly here.

* `src/main/java/Hello.java`  This is the source file where our
  `"Hello, World!"` program can be found.


## Hidden Files

If you use `ls -a` on this directory, you should the following hidden files:

* `.git` This is the subdirectory in which the `git` repository keeps a
  a record of all the various versions of the files in the repo, as well
  as metadata about the files in the repository.
* `.gitignore` This file is a list of files and filename patterns that should
  be ignored by `git`.   These files are ones that should *not* be
  stored in the `git` repository; many are generally files produced
  by compiling the code.

  See <https://ucsb-cs156.github.io/topics/git_gitignore/> for more
  information.

