# apexSalesforce

/* notes about Salesforce important details */

--> SOQL vs SQL

- SOQL 
doesn't have other statements besides SELECT
(there is no insert, update, delete)

- There's no SELECT * (all)
- There's no JOIN


--> SOSL

* matches zero or more characters at the middle or end of
the search term;
? matches only one character at the middle or end of the search 
term.

We use SOSL when we don't know which field or object
contains the information we want to return, or when
there's no relationship between the objects. 

- DML

--> Aura Components
Applications with aura components have a unique page, and they're
called SPA or single-page applications.
We shouldn't treat a component as a page.
