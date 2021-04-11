# ETL: what is thing?

According to several sources, **ETL** is an acronym for **Extraction, Transform, Load**, which is the base of a Data Engineering project.

ETL consists in a cycle as follow:
1.  Cycle initiation
2.  Build  [reference data](https://en.wikipedia.org/wiki/Reference_data "Reference data")
3.  Extract (from sources)
4.  [Validate](https://en.wikipedia.org/wiki/Data_validation "Data validation")
5.  Transform ([clean](https://en.wikipedia.org/wiki/Data_cleaning "Data cleaning"), apply  [business rules](https://en.wikipedia.org/wiki/Business_rule "Business rule"), check for  [data integrity](https://en.wikipedia.org/wiki/Data_integrity "Data integrity"), create  [aggregates](https://en.wikipedia.org/wiki/Aggregate_(data_warehouse) "Aggregate (data warehouse)")  or disaggregates)
6.  Stage (load into  [staging](https://en.wikipedia.org/wiki/Staging_(data) "Staging (data)")  tables, if used)
7.  [Audit reports](https://en.wikipedia.org/wiki/Audit_report "Audit report")  (for example, on compliance with business rules. Also, in case of failure, helps to diagnose/repair)
8.  Publish (to target tables)
9.  [Archive](https://en.wikipedia.org/wiki/Archiving "Archiving")