A very basic and simple ETL pipeline using pyspark and postgre sql.

A table has been created in postgre sql which contains some duplicate data.
Extraction: Pyspark code is extracting the table from postgre.
Transformation: pyspark is checking for duplicate data and dropping it.
Loading: The updated data is being saved into postgre in a new table
