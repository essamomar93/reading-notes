### What is Domain Modiling ? 
Domain modeling is the process of creating a conceptual model in code for a specific problem. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.  

### The Tables : 

Basic Table Structure : 
```
<table>
<tr>
<td> 1 </td>
<td> 2 </td>
</tr>
<tr>
<td> 3 </td>
<td> 4 </td>
</tr>
</table>
```
* The `<table>` element is used to create a table. The contents of the table are written out row by row.

* You indicate the start of each row using the opening `<tr>` tag ,It is followed by one or more `<td>` elements.  

* Each cell of a table is represented using a `<td>` element.

* The `<th>` element is used just like the `<td>` element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) 

* The colspan attribute can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across.

* The rowspan attribute can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table.

#### There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).

* `<thead>`: The headings of the table should sit inside the `<thead>` element. 
* `<tbody>`: The body should sit inside the `<tbody>` element. 
* `<tfoot>`: The footer belongs inside the `<tfoot>` element. 
