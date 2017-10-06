# oochallenge
This is just a programming challenge for fun and learning.

Part I
------
Write a Java program to:
  1. Read the file /SampleInput/input/data.xml.
  2. Generate report files for books, movies, and software records in the xml.
  3. Each report file only contains one type of record.
  4. The report files should be in csv format, use "|" character as field delimiter.
  5. The field order of the reports for each record type is as follow:
    - book: title|authors|hard-cover|category|pages|price
    - movie: title|produce-by|category|length|price
    - software: title|produce-by|category|price
  6. For the "hard-cover" field of book records, write "yes" to the report if the field value is "y", write "no" to the report if the field value is "n"
  7. The first line of each report should be a column header line
  8. Externalize the location of the input and output files as much as possible, as your program will be run in many different servers, and on different OS.

Part II
-------
You boss told you that there will be some changes in the requirement, but he cannot confirm the detail yet, but you must start your work
now to meet the deadline. You boss told you that the upcoming changes will be "minor"...
