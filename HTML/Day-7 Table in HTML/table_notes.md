# Table in HTML:-

1.  It is collection of Rows and Columns.
2.  Table is grid organisez in rows and columns much like in spreadsheet.
3.  To create table in html we use <table></table> tag.
4.  It is container tag and Semantic Tag (Self Explanatory Tag).
5.  Here we are creating table row by row.
6.  To create table row we use <tr></tr> tag.
7.  To create cells, Html provide 2 tags.
    i) <TH></TH> Tag:- It is used to create table heading cells.
    ii) <TD></TD> Tag:- It is used to create table data cells.
8.  To provide title or caption to the table we use <caption></caption> tag.
9.  Syntax:-
    <table border="1" >
    <caption>Employee Salary Table</caption>

                <tr>
                        <th>EMP ID</th>
                        <th>ENAME</th>
                        <th>SALARY</th>
                </tr>
                <tr>
                        <td>101</td>
                        <td>Amit</td>
                        <td>40000</td>
                </tr>
                <tr>
                        <td>102</td>
                        <td>Manoj</td>
                        <td>60000</td>
                <tr>
            </table>

# Cell spanning:-
In html, we have 2 ways to span the cells

1. Rowspan:- Rowspan is an attribute used to span the cells on row basis.
2. colspan:- colspan is an attribute used to span the cells on column basis.

# Attributes of Table Tag:

1. cellpadding:- To create space between cell border and cell content is known as cellpadding.
2. cellspacing:- To create space between outside the cell is known as cellspacing.

3. border:- It is used to provide border.
4. rules=all
5. align=center


# Thead Tag:- 
1. It is container tag.
2. It represents top most part of our table.
3. The top most part of our table we have to write with in <thead></thead> tag.

# Tbody Tag:-
1. It is container Tag.
2. The remaining content of our table we have to write with in <tbody></tbody> tag.

# Tfoot Tag:-
1. It is container Tag.
2. The consclusion or summary of the table we have to write with in <tfoot></tfoot> Tag.
3. It represents bottom most part of our table.

# Note:- 
        Thead,Tbody and Tfoot tag are highly recommended for better explanation to crawler and code understanding purpose.
