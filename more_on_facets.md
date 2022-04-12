## More on Facets

As well as ‘Text facets’ Refine also supports a range of other types of facet. These include:

- Numeric facets
- Timeline facets (for dates)
- Custom facets
- Scatterplot facets

**Numeric and Scatterplot** facets display graphs instead of lists of values. The numeric facet graph includes ‘drag and drop’ controls you can use to set a start and end range to filter the data displayed. These facets are explored further in Examining Numbers in OpenRefine

**Custom facets** are a range of different types of facets. Some of the default custom facets are:

* Word facet - this breaks down text into words and counts the number of records each word appears in
* Duplicates facet - this results in a binary facet of ‘true’ or ‘false’. Rows appear in the ‘true’ facet if the value in the selected column is an exact match for a value in the same column in another row
* Text length facet - creates a numeric facet based on the length (number of characters) of the text in each row for the selected column. This can be useful for spotting incorrect or unusual data in a field where specific lengths are expected (e.g. if the values are expected to be years, any row with a text length more than 4 for that column is likely to be incorrect)
* Facet by blank - a binary facet of ‘true’ or ‘false’. Rows appear in the ‘true’ facet if they have no data present in that column. This is useful when looking for rows missing key data.

[Episode 2 exercise 2](episode2_ex2.md)
