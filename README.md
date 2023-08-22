# Data Products CI/CD on Galaxy
This is the central repository for my Starburst Galaxy Data Products

It is meant as a design document on how to pull _DPAF_ off with Galaxy

## What are Data Products in Galaxy (technically)
A Data Product is a schema within a catalog; any kind of catalog
A Data Product has meta data associated with it
A Data Product has datasets, but these are simply the content of the schema
A Dataset can be a Table, View, Materialized View

**Mandatory Metadata:**
- Catalog
- Schema
- Data Products have a name that is unique, but it is not fixed - it can be changed
- It has a Summary (200 chars)
- At least one Contact (email)

**Optional Metadata:**
- Description (3000 chars) -> will be markdown file
- default cluster
- supporting information (a list of links and labels)
- tags

## Difference to Data Products within Starburst Enterprise
- In Galaxy there are no Domains
- 