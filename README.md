Download Link: https://assignmentchef.com/product/solved-csc3320-test-2
<br>
<span class="kksr-muted">Rate this product</span>

<ol>

 <li>Consider the array given below. Write a C program that must be able to sort the elements in the array. You must use pointers in your code to work with the arrays. The sort functionality must be implemented as a separate function named “sort_numeric()”Array for your evaluation[10, 0.25, -2342, 12123, 3.145435, 6, 6, 5.999, -2, -5, -109.56] If given user input A or a: sort in Ascending orderIf given user input D or d: sort in Descending order</li>

 <li>Considerthelistofnamesgivenbelow.WriteaCprogramthatwillfirstcreate a string array that will contain this list and then sort the elements in the array as per alphabetical order. You must use pointers in your code to work with the arrays. The sort functionality must be implemented as a separate function named “sort_alphabetic()”. The program can be case insensitive (i.e. capital or small letters are treated the same).List for your evaluationSystems Programming Deep Learning Internet Things Robotics Course</li>

</ol>

If given user input A or a: sort in alphabetical order (a comes first)If given user input D or d: sort in reverse alphabetical order(z comes first)

<ol start="3">

 <li>Repeat Question 1 or Question 2, considering that the number of elements can potentially increase. That is, the size of the array will be unknown at the start of the program. Note that the requirement of using pointers still holds.Show proof of evaluation of your program being able to work for more than 10 entries. Show 5 evaluation trials in your submission. You can pick any number of entries between 10 and 30 for your trials.(Hint: To solve this, use dynamic memory allocation, where you will NOT treat the input array as a known or finite size. Allocate memory space (e.g. malloc()) as and when the number of elements in the list increases).</li>

 <li>UsingCprogrammingandusingStructuresorUnionsinyourprogram,builda COVID vaccine registration form where any user can register by filling in their First Name, Last Name, Date of Birth (mm/dd/yyyy), Dose number (1 or 2), Date of previous dose, Type of vaccine (e.g. Pfizer, Moderna, Johnson &amp; Johnson etc.), Residential zip code.Upon registration, the system must output a 8 letter alphanumeric code that will be unique to that user. The code is generated as &lt;First letter of First Name&gt;&lt;First Letter of Last Name&gt;&lt;current age of user -as of registration date&gt;&lt;First letter of Vaccine type&gt;&lt;last 3 numbers of zipcode&gt;Add functionality in your program such that it will display all the user’s information on the screen (one item in each line).Show an evaluation trial for registering at least 10 users. For registration, ,for relevant questions, users must choose values based on the options provided. Use pseudo values instead of actual personal details.</li>

</ol>

(Hint: Write a program that contains main(), register(), generate_code() and

retrieve() functions, at the least).

5. Copy the contents of this document into a text file. Make sure the spacings and indentations are included. Write a C program that READS the TEXT file and then outputs

a. the number of characters (space is to be considered a character),b. number of words (a word is any sequence of non-white-space

characters)c. number of lines.

— Each of the functionalities a, b, and c above must be written as FUNCTIONS and passing of arguments MUST be through POINTERS.

— Name the functions problem5char.c, problem5words.c, and problem5lines.c

— Write a Makefile that will execute the main C program to include all these three scripts.

— All these outputs from (number of chars, words and lines) must be saved into ANOTHER text file row-wise. Every execution of your script with a new input must APPEND the outputs to a new row in that text file. You can separate each value in a row using any delimiter of your choice (e.g. comma or semi-colon etc)