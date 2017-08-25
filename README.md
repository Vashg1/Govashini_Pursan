# Govashini_Pursan
The programming language I've picked is C#
 
I've used Visual Studio 2010 with Windows forms components. I went with this selection because I am comfortable with these tools and use them in my day to day operations.
The interface is a standard page with a button to process the file.
I implemented the solution using a hash table. This was chosen due to it's efficiency with respect to lookups (Constant time in best case and O(n) in worst case)
I have catered for the possibility that the columns in the file are rearranged making the solution robust.

Assumptions 
Loans.csv is stored in c:/temp
A message will be displayed is no file available
Column names always stay the same

Some error handling that could be considered:
•  More fields sent than required
•  Invalid Characters
•  Missing values and fields

The above error handling could be implemented. 
However, in order to keep the application simple and clean, I've adhered to the requirements of the specification. 
