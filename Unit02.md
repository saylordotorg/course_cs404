---
layout: default
title: "CS404: Programming Languages"
course_description: "A detailed exploration of the design space of programming languages, including the functional, imperative, logic and object-oriented programming languages."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Types** <span id="2"></span> 
*In this unit, you will learn about types, a method of enforcing levels
of abstraction in programs.  Data in programs come in many types: real
number, integers, characters, lists, etc.  A type error occurs when an
operation is applied to an inappropriate data type.  A type system
consists of a set of types, and a set of programs to analyze types and
type judgment.  You will also learn about the basics of static typing,
type checking and type inference.*

**Unit 2 Time Advisory**  
This unit should take you 19 hours to complete.  
  
 ☐    Subunit 2.1: 9 hours  
  
 ☐    Subunit 2.2: 4 hours  
  
 ☐    Subunit 2.3: 6 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Explain the major approaches for dealing with type errors.
-   Distinguish between static and dynamic typing.
-   Explain the principles of, type checking and type inference.

**2.1 Principal of Typing** <span id="2.1"></span> 
-   **Reading: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: “Lecture 9: Principles of
    Typing”**
    Link: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: [“Lecture 9: Principles of
    Typing”](http://www.cs.wm.edu/~tdillig/cs312/) (PDF)  
      
     Instructions: Please click on the link above.  Browse to the
    “Syllabus” section.  Download the PDF file for “Lecture 9:
    Principles of Typing” and read the entire lecture.  The lecture will
    define typing, and explain why we need typing and how types
    compute.  What is the difference between dynamic and static typing? 
    Do you know any language with dynamic typing?   
      
     This resource should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Stanford University: Professor John Mitchell’s Lecture
    Notes for CS 242: Programming Languages: “Types and Polymorphism”**
    Link: Stanford University: Professor John Mitchell’s Lecture Notes
    for CS 242: Programming Languages: [“Types and
    Polymorphism”](https://courseware.stanford.edu/pg/courses/lectures/214531)
    (PDF)  
        
     Instructions: Please click on the link above.  Scroll down to
    lecture “Types and Polymorphism” and download the PDF file titled
    “Types and Polymorphism.”  Read the entirety of the file.  This
    reading covers the content of subunits 2.1, 2.2 and 2.3.  Use this
    reading to supplement Professor Dillig’s lecture notes.  This
    lecture will discuss several examples of typing in the context of
    the Haskell language.  
        
     This resource should take approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Stanford University: Professor John Mitchell’s Concepts
    of Programming Languages: “Chapter 6: Type Systems, Type Inference,
    and Polymorphism”**
    Link: Stanford University: Professor John Mitchell’s Concepts of
    Programming Languages: [“Chapter 6: Type Systems, Type Inference,
    and
    Polymorphism”](https://courseware.stanford.edu/pg/file/kfisher@stanford.edu/read/103914/chapter-6-type-systems-type-inference-and-polymorphism)
    (PDF)  
        
     Instructions: Please download Chapter 6 and read the entirety of
    the file.  Use this reading to supplement Professor John Mitchell’s
    Lecture Notes for CS 242: Programming Languages.  This reading
    covers the content of subunits 2.1, 2.2 and 2.3.  More specifically,
    section 6.1 covers the content of subunit 2.1, section 6.1 covers
    the content of subunit 2.2, and sections 6.3 and 6.4 covers the
    content of subunit 2.3.  
                   
     This resource should take approximately 3 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Johns Hopkins University: Scott F. Smith’s Principles of
    Programming Languages: “Chapter 6: Type Systems”**
    Link: Johns Hopkins University: Scott F. Smith’s *Principles of
    Programming Languages:* [“Chapter 6: Type
    Systems”](http://pl.cs.jhu.edu/pl/book/dist/) (PDF)  
        
     Instructions: Note that this chapter is optional, but you may use
    it to supplement the lecture notes above. This chapter provides the
    mathematical foundations for typing. It covers the content of
    subunits 2.1, 2.2 and 2.3.  
      
     This resource should take approximately 3 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2 Type Checking** <span id="2.2"></span> 
-   **Reading: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: “Lecture 10: Basic Typing Rules
    and Proofs”**
    Link: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: [“Lecture 10: Basic Typing
    Rules and Proofs](http://www.cs.wm.edu/~tdillig/cs312/)” (PDF)  
      
     Instructions: Please click on the link above.  Browse to the
    “Syllabus” section and download the PDF file for “Lecture 10: Basic
    Typing Rules and Proofs.”  Read the entirety of these files.  You
    will learn how to construct type systems for multiple languages and
    prove/show soundness of a type system.  
        
     This resource should take approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of Virginia: Wes Weimer’s “Type Checking and
    Static Semantics”**
    Link: University of Virginia: Wes Weimer’s [“Type Checking and
    Static Semantics”](http://www.cs.virginia.edu/~cs415/lectures.html)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to lecture 11
    (Mon Mar 12), and select the hyperlink under the topic column
    entitled, “Type Checking & Static Semantics.”  Please read the
    entirety of this webpage for an additional understanding of typed
    programming languages.   
      
     This resource should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: IIT Delhi: Dr.S.Arun Kumar’s “Lecture - 34 Type
    Checking”**
    Link: YouTube: IIT Delhi: Dr.S.Arun Kumar’s [“Lecture - 34 Type
    Checking”](http://www.youtube.com/course?list=ECF7C73918190889CE)
    (YouTube)  
        
     Instructions: Click on the link above, which will take you to the
    Lecture Series on Programming Languages by Dr. S. Arun Kumar,
    Department of Computer Science & Engineering, IIT Delhi.  Browse
    down and click on “Lecture - 34 Type Checking.”  Please view the
    video in its entirety (53:12 minutes), which introduces you to type
    checking.  
        
     This resource should take approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3 Polymorphic Typing and Type Inference** <span id="2.3"></span> 
-   **Reading: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: “Lectures 11-14”**
    Link: William & Mary College: Professor Thomas Dillig’s CS 312
    Programming Languages Lecture Notes: [“Lectures
    11-14”](http://www.cs.wm.edu/~tdillig/cs312/) (PDF)  
        
     Instructions: Please click on the link above.  Browse to the
    “Syllabus” section and download and read the PDF files for lectures
    11-14.  
      
     This resource should take approximately 4 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Johns Hopkins University: Scott F. Smith’s Principles of
    Programming Languages: “Chapter 6: Type Systems”**
    Link: Johns Hopkins University: Scott F. Smith’s *Principles of
    Programming Languages*: [“Chapter 6: Type
    Systems”](http://pl.cs.jhu.edu/pl/book/dist/) (PDF)  
        
     Instructions: Read section 6.6 and 6.7 of the book.  Use this
    reading to supplement the other readings above.  
        
     This resource should take approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**Unit 2 Assessment** <span id="2.4"></span> 
-   **Assessment: The Saylor Foundation’s “Unit 2 Assessment”**
    Link: The Saylor Foundation’s [“Unit 2
    Assessment”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/12/CS404-Unit-2-Assessment-FINAL.pdf)
    (PDF)  
        
     Instructions: Complete the assessment linked above. When you have
    finished, you may check your answers against the Saylor Foundation’s
    [“Unit 2 Assessment – Answer
    Key”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/12/CS404-Unit-2-Assessment-Answer-Key-FINAL.pdf)
    (PDF).


