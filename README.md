Download Link: https://assignmentchef.com/product/solved-assignment-7-the-database-microland-accdb
<br>
The database Microland.accdb is maintained by the Microland Computer Warehouse, a mail-order computer-supply company.  The illustrations below show data in the Customers table and the Orders Table in the database.  The table identifies each customer by an ID number and gives, in addition to the name and address, the total amount of purchases during the current year.  The Order table provides the customer id and the item ordered.

The database that contains the table for this assignment is contained within your Instructions folder and should be placed in your project’s bindebug folder.

**To receive any points for this assignment you must do the following:

For this assignment you will open the attached Microsoft Access file and add your name (Kyle Redd) and your instructors name (Miranda Dyer) in the customers table using the following information:

CustIDNameStreetCityAmtPurchase13Your NameYour StreetYour City100.5014Your teachers NameYour StreetYour City95.25

You must also add the following lines to the Orders table

CustIDitemIDQuantity13HW921314SW1092

Write a Visual Basic program that will:

a.  On the form_load event, display in a listbox the customers’ names that are listed in the Customers table.

b.  When the user selects a customer from the listbox,the customer’s name, street, city, and purchases should be displayed in the textboxes to the right of the buttons as illustrated below.

c.   The customer and the order table are joined and the orders for the customer are displayed in the atagrid.  The datagrid should have headers for the data as shown below.

d.   The purchases should be formatted to be currency

e.   A Display Total Purchases should be included to sum up all of the total purchases for all names listed in the lstOutput.  This information should be displayed in a message box.

f.  A Clear button should be included to clear all of the textboxes and datagrid.  [Note that it should not clear the listbox containing the customers’ names.]

g.    A Close button should be included to exit the application.

As in all of your assignments, make sure that you have used appropriate programming techniques (i.e. naming of controls and variables, form has a title, tab order of controls is appropriate, textboxes used for display purposes are not writeable, internal documentation/comments are clear, formatting of any currency fields, etc.)

Design your form based on the diagram below.