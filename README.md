# python_examples

## prior balance pull file

- includes a closest word lookup function that i created in my masters class
- it worked about 95% of the time to convert back pay deduction or benefits to current pay codes 
- pivots row based transactional data and sums data where needed for transactions to combine specific codes 

## EE_main 

- includes multiple merges, pivots and concatenations to provide the right data. 
- Some merges/concatenation could have been done specifically in SQL,but seeing the data laid out in this way helped Stakeholders understand the flow of the data better
- Manipulates strings, numbers, fills in missing cells etc...

## Timesheet configuraiton

- Takes a complex set of worksheets from a workbook and combines them, manipulates them to fill into a import file
- it outputs both the per client files and the full file. This is import to redo any incorrect time information that the client has sent. 
