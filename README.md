Download Link: https://assignmentchef.com/product/solved-cse-522-assignment2-part1
<br>
An important technique in the study of Object-Oriented Programming is the use of <em>delegation</em> to replace <em>class inheritance</em>.   A systematic approach for this transformation was given in Lecture 5.

Apply this approach to the program Delegation.java located at Piazza à Resources à Assignments.  This program defines classes A, B, C, D, E, and F.  The result of your transformation should be classes called A2, B2, C2, D2, E2, and F2 which correspond to classes A, B, C, D, E, and F respectively, but do not make  use of class inheritance.

In order to develop the transformation, you need to define one interface for each class.  Name these interfaces IA, IB, IC, ID, IE, and IF.   Classes A2, B2, C2, D2, E2, and F2 must implement interfaces IA, IB, IC, ID, IE, and IF respectively.  As noted in Lecture 5, you may use optimize the interfaces to remove redundancies.

The file Delegation.java contains the definitions of classes A … F and also a driver class called Delegation.  It also contains the outline of the classes A2 … F2.   Define the interfaces IA … IF and the classes A2 … F2 in the same file.    Run the program through JIVE and save the object and sequence diagrams as files named A2_obj1.png and A2_seq1.png respectively.   For the object diagram, choose the ‘Objects with Tables’ option.




<strong><em>Important</em></strong><em>:  Full credit will be given only if the transformation is done in a systematic way: In addition to the definition of the interfaces, the delegation hierarchy should be defined; new variables this2 and super2 should be introduced to model this and super respectively; and, delegation and protected abstract methods should be implemented as required. </em>