Download Link: https://assignmentchef.com/product/solved-cs-570-programming-foundations-homework-assignment-7
<br>
<strong>Note:</strong> This and all assignments given in this course can be and must be solved using <strong>only</strong> the materials that have been discussed in class.  Do not look for alternative methods that have not been covered as part of this course.

<strong> </strong>

<strong>Program (100 points): </strong>




In this assignment, we are going to practice reading from a file and writing the results of your program into a file.  You will also practice catching exceptions.  To that effect, we will “redact” specific words on a data file.




<h1>Program details</h1>




Governments, law firms, and businesses often have sensitive documents with private information.  Occasionally these documents may need to be distributed more widely than was first intended.  This often requires removing names of particular people to protect their privacy.




You are to write a program that removes all occurrences of a certain name from an input text file.  Your program should traverse the document and search for the name to remove. Then the document should be re-written to a new text file with each name occurrence replaced with the word “REDACTED”.




Your program should prompt the user to enter three Strings:




<ul>

 <li>The filename of the original document (this is your input file)</li>

 <li>The name to be removed and replaced (this is a string and it could be one or more words. For example John Smith)</li>

 <li>The output filename where the cleaned document will be stored (this is your output file)</li>

</ul>




Make sure your program handles possible exceptions cleanly.

<strong><em>Hint</em></strong>:  You will need to review String methods discussed in week 3 this term.  In particular, you may find the indexOf and substring methods very helpful:
















Try testing your redaction program on a public domain novel from <a href="https://www.gutenberg.org/">Project</a> <a href="https://www.gutenberg.org/">Gutenberg</a><a href="https://www.gutenberg.org/">.</a> Download a <strong>.txt</strong> version of a short novel you like and try replacing a character’s name using your program.  Alternatively, you can also create your own input file by using a text editor (remember to save your file as a <strong>txt</strong> file).  You can then go to your favorite news site, find an article, and copy and paste the text of the article into your <strong>txt</strong> file.




Here are a couple of sample runs of a typical solution to this problem:




Output File sample:

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Note:  </strong>Please make sure to submit well-written programs for these programming tasks. Good identifier names, useful comments, indentation, and spacing will be some of the criteria that will be used when grading this assignment.


