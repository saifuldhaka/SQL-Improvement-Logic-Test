## Theme
Please suggest what improvements should be done to the query in order to improve its performance.

## Purpose
These are a SQL query that produces a search result. The query produces results in approximately 8 seconds.


## Justification
<p>Doing Inner Join first to fetch Jobs, JobCategories, JobTypes records </p>
<p>2nd LEFT JOIN to fetch additional tables</p>
<p>Remove the redundant join with affiliates table</p>
