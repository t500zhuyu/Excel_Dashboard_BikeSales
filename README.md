Excel data project portfolio
The next is about what I did to make this final dashboard that can be seen in the Excel file (.xlsx).

1. Create a copy of the dataset into another sheet.

2. Remove duplicates with the tool with the same name in Excel.

3. Replace data using Find and Replace (short code ctrl + h):
In the column Maritial Status there are two data: 'M' and 'S'
We will replace 'M' with 'Married' and 'S' with 'Single'.

4. In the column Gender Status there are two data: 'M' and 'F'
We will replace with 'Male' for 'M' and 'F' with 'Female'

5. We insert a new column: 'Age Brackets' with this column
  We will apply IF formula to divide ages by different ranges as follows:
   - Old for > 54 years old
   - Middle Age for  >=31 years old
   - Adolescent for < 31 years old
 
Next step is to create a pivot table in the sheet called pivot table
The values for the pivot table is income
rows gender column purchaded bike

Another table about purchased Bike
row: Commute distance
column: purchased Bike

Next pivot table about Age Brackets and if these people bought a bike.

Next step was create a chart for each of these pivot tables.

Then copy and paste them in the sheet 'dashboard'.

With those charts in the sheet 'dashboard' now it's time to create a dashboard with them, we will use slicers to filter the information
in automatic way to see our vizualizations more interesting 
In this case we will use the slicers about the married status, region and education.
With all this we finally did an interactive dashboard.
