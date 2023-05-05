Download Link: https://assignmentchef.com/product/solved-dbs211-lab3-sql-single-table-queries
<br>
Objectives

The purpose of this lab is to start learning SQL by writing basic DML statements involving a single table.  You will learn to create basic CRUD statements (queries as well as insert, update and delete).

<h1>Setup</h1>

Create a new worksheet in SQL developer and add an appropriate comment header that includes your name, student id, the date and the purpose of the file (i.e. DBS211 – Lab 03).

Immediately under the comment header, enter the following line and then execute it:

SET AUTOCOMMIT ON;

You will need to execute this statement each time you login to the server until the completion of this lab.

Save the script as:  DBS211_L03_LastName_FirstName.sql

<h1>Style Guide</h1>

Your SQL should be written using the standard coding style:

<ul>

 <li>all keywords are to be upper case,</li>

 <li>all user-defined names are to be lower case, (example: table and field names)</li>

 <li>there should be a carriage return before each major part of the SQL statements (i.e. before SELECT, FROM, WHERE and ORDER BY)</li>

</ul>

Using comments to number the question answers, write the SQL code to complete the following tasks.

<strong>Tasks: </strong>

<ol start="12">

 <li>Display the data for all offices.</li>

 <li>Display the employee number for all employees whose office code is 1.</li>

 <li>Display customer number, customer name, contact first name and contact last name, and phone for all customers in Paris. (<strong>hint</strong>: be wary of case sensitivity)</li>

 <li>Repeat the previous Query with a couple small changes:

  <ol>

   <li>The contact’s first and last name should be in a single column in the format “lastname, firstname”.</li>

   <li>Show customers who are in Canada</li>

  </ol></li>

 <li>Display customer number for customers who have payments. Do not included any repeated  (<strong>hints</strong>: how do you know a customer has made a payment? You will need to access only one table for this query)</li>

 <li>List customer numbers, check number, and amount for customers whose payment amount is not in the range of $30,000 to $65,000. Sort the output by top payments amount first.</li>

 <li>Display the order information for all orders that are cancelled.</li>

 <li>The company needs to know the percentage markup for each product sold. Produce a query that outputs the ProductCode, ProductName, BuyPrice, MSRP in addition to

  <ol>

   <li>The difference between MSRP and BuyPrice (i.e. MSRP-BuyPrice) called <em>markup</em></li>

   <li>The percentage markup (100 * calculated by difference / BuyPrice) called <em>percmarkup </em>rounded to 1 decimal place.</li>

  </ol></li>

 <li>Display the information of all products with string ‘<strong><em>co’</em></strong> in their product name. (c and o can be lower or upper case).</li>

 <li>Display all customers whose contact first name starts with letter <strong><em>s</em></strong> (both lowercase and uppercase) and includes letter <strong><em>e</em></strong> (both lowercase and uppercase).</li>

 <li>Create a statement that will insert yourself as an employee of the company.

  <ol>

   <li>Use a unique employee number of your choice</li>

   <li>Use your school email address</li>

   <li>Your job title will be “Cashier”</li>

   <li>Office code will be 4</li>

   <li>You will report to employee 1088</li>

  </ol></li>

 <li>Create a query that displays your, and only your, employee data</li>

 <li>Create a statement to update your job title to “Head Cashier”</li>

 <li>Create a statement to insert another fictional employee into the database. This employee will be a “Cashier” and will report to you.  Make up fake data for the other fields.</li>

 <li>Create a statement to Delete yourself from the database. Did it work?  If not, why?</li>

 <li>Create a statement to delete the fake employee from the database and then rerun the statement to delete yourself. Did it work?</li>

 <li>Create a <strong>single</strong> statement that will insert both yourself and the fake employee at the same time. This time the fake employee will report to 1088 as well.</li>

 <li>Create a <strong>single</strong> statement to delete both yourself and the fake employee.</li>

</ol>


