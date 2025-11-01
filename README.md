###  Java bug catalog with  structured Knowledge about mistakes (KM) and Knowledge about how to proceed (KH) feedback.
### Bug types
1.  == versus .equals (faulty string comparisons)
2.  = versus ==
3. Misuse of { }, [ ], ( ), “ ”, and ‘ ’
    
4.  Incorrect semi-colon after an if selection structure before the if statement or after 
    the  for or while repetition structure before the respective for or while loop
5.  Wrong separators in for loops (using commas instead of
    semi-colons)"
6.  An if followed by a bracket instead of by a parenthesis
7.  Using keywords as method names or variable names
8.  Invoking methods with wrong arguments
9.  Incorrect semicolon at the end of a method header 
10. Leaving a space after a period when calling a specific method
11. Using => or =< instead of >= and <=
12. Invoking class method on object
13. Constructor call to non-existent copy constructor
14. invoking a non-void method in a statement that requires a return value
15. forgetting parentheses after method call
16. Flow reaches end of non-void method
17. Misunderstanding object references
18. Incompatibility between the declared return type of a method and in its invocation 
19. class declared abstract because of missing function
20. Trying to invoke a non-static method as if it was static.
21. Field Not Found
22. Use of non-static Variable Inside the static method
23. Type mismatch
24. Using a non-initialised variable
25. Operator missing
26. Method name not found
27. Variable not declared
28. ; missing
29. Variable name written incorrectly
30. Missing break in switch
31. Misconceptions related to  object arrays 
32. Missing parentheses for constructor call 
33. Unhandled exception
34. : in place of ;
35. Miconceptions related to inheritance
36. class or interface expected 
37. Keyword written incorrectly
38. Misconceptions about access modifiers
39. Identifier expected
40. Mispeling printLine
41. Misconceptions related to polymorphic collection
42. Missing closing curly brace at end of class
43. Method call targeting wrong type  
44. not a statement
45. Pre/Post Increment-Decrement Misuse
46. Missing operator between expression elements
47. Incorrect use of && vs & and || vs |
48. Misunderstanding type casting between objects
49. Array used in place of array element
50. Missing closing curly brace after control stmt body 
51. Linked list based Queue and Stack  implementation errors 
52. Constructor parameter number mismatch
53. Class not defined
54. Infix Operator Precedence
55. Method declaration:no type specified for parameter 
56. Method duplicate exactly 
57. Statement outside method
58. Comment incorrectly written
59. Local variable declaration with illegal modifier
60. Assignment to a collection element
61. Call to ’super’ in constructor not first statement
62. Collection used in place of element
63. Constructor call attempted using variable name 
64. Constructor is declared to return ’void
65. Method call: missing comma between parameters
66. Method declaration: semicolon in place of comma
67. Missing space after ’new
68. Constructor call without using “new
69. Custom doubly linked list implementation errors
70. Value from raw collection must be cast
71. Variable declaration: name and type in wrong order
72. Type mismatch: arithmetic performed on String; use length
73. Misunderstanding of loops
74. Failing to choose an appropriate loop construct in a specific context
75. Method declaration: missing method body
76. For loop is not inclusive so sum excludes the last element"
77. Not realising that division of two integers returns the floor of the division, not a    
    double.
78. Accessing an element outside an array. Usually a result of using ≤ instead of <
79. Class should be declared to implement interface
80. Using .length as a field
81. Missing this
82. Misconceptions in recursion
83. Mis-capitalized toString
84. Array-based stack implementation errors 
85. Custom linked list implementation errors
 


 The following research papers were reviewed to identify the common student programming errors. 
 
 - Amjad Altadmri and Neil C.C. Brown. 2015. 37 Million Compilations: Investigating Novice Programming Mistakes in Large-Scale Student Data. In Proceedings of the 46th ACM Technical Symposium on Computer Science Education (SIGCSE '15). Association for Computing Machinery, New York, NY, USA, 522–527. https://doi.org/10.1145/2676723.2677258
-  Marzieh Ahmadzadeh, Dave Elliman, and Colin Higgins. 2005. An analysis of patterns of debugging among novice computer science students. SIGCSE Bull. 37, 3 (September 2005), 84–88. https://doi.org/10.1145/1151954.1067472

- McCall, D. and Kölling, M. 2014. Meaningful categorisation of novice programmer errors. In Proceedings of the 2014 IEEE Frontiers in Education Conference (FIE). IEEE, Madrid, Spain, 1–8. DOI: https://doi.org/10.1109/FIE.2014.7044420
 - Davin McCall and Michael Kölling. 2019. A New Look at Novice Programmer Errors. ACM Trans. Comput. Educ. 19, 4, Article 38 (December 2019), 30 pages. https://doi.org/10.1145/3335814
 - Neil C.C. Brown and Amjad Altadmri. 2014. Investigating novice programming mistakes: educator beliefs vs. student data. In Proceedings of the tenth annual conference on International computing education research (ICER '14). Association for Computing Machinery, New York, NY, USA, 43–50. https://doi.org/10.1145/2632320.2632343

- Maria Hristova, Ananya Misra, Megan Rutter, and Rebecca Mercuri. 2003. Identifying and correcting Java programming errors for introductory computer science students. In Proceedings of the 34th SIGCSE technical symposium on Computer science education (SIGCSE '03). Association for Computing Machinery, New York, NY, USA, 153–156. https://doi.org/10.1145/611892.611956

- Paul Denny, Andrew Luxton-Reilly, and Ewan Tempero. 2012. All syntax errors are not equal. In Proceedings of the 17th ACM annual conference on Innovation and technology in computer science education (ITiCSE '12). Association for Computing Machinery, New York, NY, USA, 75–80. https://doi.org/10.1145/2325296.2325318

- Yizhou Qian and James Lehman. 2017. Students’ Misconceptions and Other Difficulties in Introductory Programming: A Literature Review. ACM Trans. Comput. Educ. 18, 1, Article 1 (March 2018), 24 pages. https://doi.org/10.1145/3077618

 - Andrew Ettles, Andrew Luxton-Reilly, and Paul Denny. 2018. Common logic errors made by novice programmers. In Proceedings of the 20th Australasian Computing Education Conference (ACE '18). Association for Computing Machinery, New York, NY, USA, 83–89. https://doi.org/10.1145/3160489.3160493
 - Just, N., Siegmund, J. and Schantong, B., 2025. From Bugs to Breakthroughs: Novice Errors in CS2. arXiv preprint arXiv:2502.14438.
 - J. Jackson, M. Cobb, and C. Carver. 2005. Identifying Top Java Errors for Novice Programmers. In Proceedings of the 35th Annual Frontiers in Education Conference (FIE ’05). IEEE, Indianapolis, IN, USA, T4C–T4C. https://doi.org/10.1109/FIE.2005.1611967
 - Ian Finlayson and Stephen Davies. 2024. Jguardrail: A Framework for Identifying Possible Errors in Student Java Code. J. Comput. Sci. Coll. 40, 3 (October 2024), 322–333.
 


 