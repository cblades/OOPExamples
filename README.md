# Java and Object-Oriented Programming by Example


## What is this?
This repository is my attempt to provide a well-paced, straight-forward introduction to java and object-oriented programming.

This is a work in progress, you may see empty sections, or `//todo` notes that I have left myself.  If you feel you can contribute, feel free to submit a pull request (although I reserve the right to edit, expand, or out-right reject your suggestions).  

## Who Are You?  Why Should I Listen to You?
I am mostly a typical enterprise java developer.  I have several years of experience and just enough expertise to be arrogant enough to write this guide.  My goal is for this guide to not be opinionated, but rather to introduce foundational knowledge and, where there may be disagreement, to be up-front and to express the community consensus wherever possible. 

Reasons you should trust me:
`// todo establish credability`

More importantly, wherever I use or reference a specific tool, library, or class, I will link to the relevant documentation.


## How Should I Use This Guide?
Every directory in this repository will have a `README.md` file (such as this one), that is exposition relevant to the material in that directory and sub-directories.  Other files in the directory will be annotated examples of the topics addressed in the `README.md`.

To navigate this project, I suggest that you start at this top-level directory, and then proceed to `src/`, where you will find another `README.md` file.  Proceed down the directory structure to `com/`, then `cblades/`, and then `oop/`, reading any `README.md` files you encounter.

At `src/com/cblades/oop`, you will encounter several directories with names like `01/`, `02/`, `03/`, etc.  Proceed through them in order; i.e., all the way to the bottom of the directory tree at `01/` before progressing to `02/`.


In directories where there are sourcecode files, the `README.md` will give a brief overview of what they are, and tell you in which order to read them.  It may also use snippets from the same files to illustrate points.  Code snippets will always come from a file in the current directory, and will be attributed.

Each sourcecode file will take this form:

```java
/***
 * PURPOSE:
 * An overview of the concepts covered in this file, in a numbered-list format:
 * 1) Where does a program start?
 * 3) How do you print something to the console?
 *
 * PREREQUISITES:
 * What you should already know before tackling this file (if you've proceeded through this project in order, you should have been exposed to all prerequisites.  If you find otherwise, please submit a bug report).
 * - Intro to WTF even *is* a program?  [src/com/cblades/oop/] 
 *
 * @version 3/17/2017
 * @author cblades
 */
 public class HelloWorld {
    
    /**
     * I will use [1] to indicate that I'm addressing one of the purposes listed at the beginning of the file
     *
     * [1] Ever program will start by invoking the main method, which must be declared exactly as below:
     * public static void main(String[] args) {
     */
    public static void main(String[] args) {
      // [1]  This line is the first one executed in this program, because it is the first line of code in the main method:
      // [2]  This will print "Hello, World!" to the terminal.  
      System.out.println("Hello, World!");
    }
 }
```