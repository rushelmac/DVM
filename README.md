# DVM
Digital Voting Machine

##Features :

1)Allows us to set up a flexible and trustworthy voting system

2)Applicable for large as well as small group of people e.g. a batch, a class (Distinguished by unique identifier).

3)The project can handle all the possibilities of spam voters, confidentiality and to an extent, machine failure thereby being an ideal solution for such elections.

##Working of Code:-

###The Header File : ELECTION.H :-

Structure : 

1)CAND : Stores name and vote count

Functions :

1)candname : Use: Stores candidate info in structure as well as file

2)flcreate : Creates ‘count’ no. of files initiates with ‘0’

3)isSpecial : Check for blank PRN from file

4)isAuthentic : PRN Authentication

5)delFromfile : Delete vote by PRN from given file

6)admin :
    1.Election initiation
    2.Election Continuation
    3. Illegal vote deletion
    4. Result Declaration

7)stu : All functions at Voter’s end

### [Note:Compatible Compiler: Turbo C++]

