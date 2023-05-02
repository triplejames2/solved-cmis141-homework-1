Download Link: https://assignmentchef.com/product/solved-cmis141-homework-1
<br>
Before attempting this project, be sure you have completed all of the reading assignments, hands-on labs, discussions, and assignments to date.

Write a Java program that prompts a user to enter student EMPLID (e.g., 12389), quiz 1 percentage score (e.g., 89.5), quiz 2 percentage score (e.g., 81.2), quiz 3 percentage score (e.g., 92.5), your age <strong>in months</strong> (e.g. 384)  and the current temperature in degrees Celsius and then displays the data entered along with some conversions and calculations.

A minimum of 3 test cases should be supplied in the form of table with columns indicating the input values, expected output, actual output and if the test case passed or failed. This table should contain 4 columns with appropriate labels and a row for each test case. An example template is shown below.  Note that the actual output should be the actual results you receive when running your program and applying the input for the test record.

The google recommended Java style guide, provided as link in the week 2 content, should be used to format and document your code. Specifically, the following style guide attributes should be addressed:

<ul>

 <li>Header comments include filename, author, date and brief purpose of the program.</li>

 <li>In-line comments used to describe major functionality of the code.</li>

 <li>Meaningful variable names and prompts applied.</li>

 <li>Class names are written in UpperCamelCase.</li>

 <li>Variable names are written in lowerCamelCase.</li>

 <li>Constant names are in written in All Capitals.  Braces use K&amp;R style<strong>.</strong></li>

</ul>

You should capture and label screen captures associated with compiling your code, and running each of your 3 test cases.

You should use the command prompt and not a GUI for data entry and display.  Here is a sample run:

Enter your Student EMPLID (0 – 999999): 43023

Enter your quiz1 percentage score (0.0 – 100.0):  80.6

Enter your quiz2 percentage score (0.0 – 100.0):  82.6

Enter your quiz2 percentage score (0.0 – 100.0):  92.1

Enter your age in months (0-1440): 384

Enter the current Temperature in degrees Celsius: 19.0

*** Thank you ***

Student EMPLID:  43023

Quiz 1 Score: 80.6

Quiz 2 Score: 82.6

Quiz 3 Score: 92.1

Average quiz score: 80.0

Age in months: 384

Age in years: 32

Temperature in Celsius: 19.0

Temperature in Fahrenheit:  66.2




Note the following for the output for this application:

<ol>

 <li>Degrees Celsius has been converted to degrees Fahrenheit on the output.</li>

 <li>The temperature output provides the degrees symbol (°). (Hint: Use Unicode characters)</li>

 <li>The average quiz score is calculated from the three quiz scores input.</li>

</ol>

<strong>Example test cases: </strong>

<table width="623">

 <tbody>

  <tr>

   <td width="117"><strong>Input </strong></td>

   <td width="237"><strong>Expected Output </strong></td>

   <td width="222"><strong>Actual Output </strong></td>

   <td width="48"><strong>Pass? </strong></td>

  </tr>

  <tr>

   <td width="117">EMPLID: 32012Quiz1: 30.0Quiz2: 20.5Quiz3: 60.2 Age in months: 120Temperature in Celsius: 0.0 </td>

   <td width="237">*** Thank you ***Student EMPLID:  32012Quiz 1 Score: 30.0Quiz 2 Score: 20.5Quiz 3 Score: 60.2Average quiz score: 36.9Age in months: 120Age in years: 10Temperature in Celsius: 0.0Temperature in Fahrenheit:  32.0 <strong> </strong></td>

   <td width="222">*** Thank you ***Student EMPLID:  32012Quiz 1 Score: 30.0Quiz 2 Score: 20.5Quiz 3 Score: 60.2 Average quiz score:Age in months: 120Age in years: 10Temperature in Celsius: 0.0Temperature in Fahrenheit:  32.0 376<strong> </strong></td>

   <td width="48"><strong>Yes </strong></td>

  </tr>

  <tr>

   <td width="117"><strong>Test case 2 here </strong></td>

   <td width="237"><strong> </strong></td>

   <td width="222"><strong> </strong></td>

   <td width="48"><strong> </strong></td>

  </tr>

  <tr>

   <td width="117"><strong>Test case 3 here </strong></td>

   <td width="237"><strong> </strong></td>

   <td width="222"><strong> </strong></td>

   <td width="48"><strong> </strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Submission requirements </strong>

Deliverables include all Java files (.java) and a single word (or PDF) document. The Java files should be named appropriately for your applications. The word (or PDF) document should include screen captures showing the successful compiling and running of each of the test cases. Each screen capture should be properly labeled clearly indicated what the screen capture represents. The test cases table should be included in your word or PDF document and properly labeled as well.

Submit your files to the Homework 1 assignment area no later than the due date listed in your LEO classroom. You should include your name and HW1 in your word (or PDF) file submitted (e.g. firstnamelastnamehw1.docx or firstnamelastnamehw1.pdf)

<strong> </strong>

<strong> </strong>

<strong> </strong>

<strong>Grading Rubric: </strong>

The following grading rubric will be used to determine your grade:

<table width="623">

 <tbody>

  <tr>

   <td width="208"><strong>Attribute </strong></td>

   <td width="208"><strong>Meets </strong></td>

   <td width="208"><strong>Does not meet </strong></td>

  </tr>

  <tr>

   <td width="208">User input</td>

   <td width="208">5 pointsApplication prompts a user to enter student EMPLID, quiz 1 percentage score, quiz 2 percentage score, quiz 3 percentage score, age <strong>in months</strong> and the current temperature in degrees Celsius.Command Line was used for input.</td>

   <td width="208">0 pointsApplication does not prompt a user to enter student EMPLID, quiz 1 percentage score, quiz 2 percentage score, quiz 3 percentage score, age <strong>in months</strong> and the current temperature in degrees Celsius.Command Line was not used for input.</td>

  </tr>

  <tr>

   <td width="208">Application output</td>

   <td width="208">10 pointsApplication correctly displays all data entered by the user along with the calculated output for average quiz, age in years and temperature in Fahrenheit.Command Line was used for output.</td>

   <td width="208">0 pointsApplication does not correctly displays all data entered by the user along with the calculated output for average quiz, age in years and temperature in Fahrenheit.Command Line was not used for output.</td>

  </tr>

  <tr>

   <td width="208">Test Cases</td>

   <td width="208">5 pointsA minimum of 3 test cases was used in the form of table with columns indicating the input values, expected output, actual output and if the test case passed or failed. The table should contains 4 columns with appropriate labels and a row for each test case.Test cases were included in the supporting word or PDF documentation.</td>

   <td width="208">0 pointsNo test cases were provided.</td>

  </tr>

  <tr>

   <td width="208">Documentation and Style guide</td>

   <td width="208">5 pointsScreen captures were provided and labeled for compiling your</td>

   <td width="208">0 pointsNo documentation included</td>

  </tr>

  <tr>

   <td width="208"> </td>

   <td width="208">code, and running each of your 3 test cases.Header comments include filename, author, date and brief purpose of the program.In-line comments used to describe major functionality of the code.Meaningful variable names and prompts applied.Class names are written in UpperCamelCase.Variable names are written in lowerCamelCase.Constant names are in written in All Capitals.Braces use K&amp;R style<strong>.</strong></td>

   <td width="208">Java style guide was not used to prepare the Java code.</td>

  </tr>

 </tbody>

</table>


