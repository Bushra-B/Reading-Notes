# HTML - Tables

**If you want to represent information in a table, you need to think in terms of a *grid* made up of rows and columns.**
\- Grids allow us to understand complex data by referencing information on two axes. 

- tables in HTML are written row by row
- blocks in the grid are called *_cell tables_* 

## Basic HTML table structure:

1. `<table>` element 
    to create a table

2.`<th>` element
     stands for 'table heading', represents the heading for a column or a row

2.`<tr>` element
    stands for 'table row', to indicate the start of a row

3. `<td>` element 
    stands for 'table data', represents table cell, contains the content of the cell between its oppening and closing tags and is place inside a `<tr>` element  

5. `<thead>` element
     


- some browsers automatically draw lines around the table and/or the individual cells

- `colspn` attribute : can be used on a `<th>` or `<td>` element and indicates how many columns that cell should run across

- `rowspan` attribute :  can be used on a `<th>` or `<td>` element to indicate how many rows a cell should span down the table