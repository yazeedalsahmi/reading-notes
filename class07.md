# Tables :
A table represents information in a grid format 
Examples of tables include financial reports, TV 
schedules, and sports results.
**Grids** allow us to understand complex data by referencing information on two axes.
Each block in the grid is referred to as a **table cell**. In HTML a table is written out row by row.
## Table structure :
* <table> : The <table> element is used to create a table. The contents 
of the table are written out row by row.
* <tr> : You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.) 
* <th> : The <th> element is used just like the <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) 

  Ex : 
  ````
  <table>
 <tr>
 <th></th>
 <th>9am</th>
 <th>10am</th>
 <th>11am</th>
 <th>12am</th>
 </tr>
 <tr>
 <th>Monday</th>
 <td colspan="2">Geography</td>
 <td>Math</td>
 <td>Art</td>
 </tr>
 <tr>
 <th>Tuesday</th>
 <td colspan="3">Gym</td>
 <td>Home Ec</td>
 </tr>
</table>
  ````
  ### Long Tables :
  There are three elements that help distinguish between the main content of the table and 
the first and last rows (which can contain different content).
  These elements help people who use screen readers and also allow you to style these sections 
in a different manner than the rest of the table.
  * <thead> : The headings of the table should 
sit inside the <thead> element.
  * <tbody> : The body should sit inside the 
<tbody> element. 
 * <tfoot> : The footer belongs inside the 
<tfoot> element.



  
