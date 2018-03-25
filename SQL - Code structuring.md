#SQL coding best practices

<h3>1.	Header – </h3>
Must include details of Author, code creation and modification date, purpose of code(details of project and analysis performed via the code)

<h3>2.	Input checks – </h3>
  a.	List all the tables that shall be used for the analysis
  b.	Check level, duplication, no. of records per week, compliance in YoY trends etc.
  c.	Any joins, filters, aggregation checks, flag definitions should be listed
    i.	Keep track of change in records by joins, filter applications
    ii.	Check if the flag defined was consistent with intended definition of the flag

<h3>3.	Code-</h3>
  a.	Should include the queries which should be executable as Ctrl+A and Alt+X and give me the final deliverable – figure of speech
  b.	Have beautiful indentation
  c.	Do not have complicated subqueries. As a best practice create a new table whenever you reach a 3rd level in the coding ladder
  d.	Have sound aliases for subqueries, details of table, details of column being picked from the table etc.

<h3>4.	Output checks-</h3>
  a.	To QC a set of number obtained from multiple steps in code, apply relevant filters and joins to reproduce a single number, if all data checks are robust recheck the logic
