**Exercise 4.1**

Transform three more columns, no_members, years_liv, and buildings_in_compound, from text to numbers. Can all columns be transformed to numbers? - Try it with village for example.

<details>
<summary>
Solution
  </summary>
Only observations that include only numerals (0-9) can be transformed to numbers. If you apply a number transformation to a column that doesn’t meet this criteria, and then click the Undo / Redo tab, you will see a step that starts with Text transform on 0 cells. This means that the data in that column was not transformed.
</details>
  
---

**Exercise 4.2**

1. For a column you transformed to numbers, edit one or two cells, replacing the numbers with text (such as abc) or blank (no number or text). You will need to change the Data type to text using the drop-down menu.
1. Use the column pulldown menu to apply a numeric facet to the column you edited. The facet will appear in the left panel.
1. Notice that there are several checkboxes in this facet: Numeric, Non-numeric, Blank, and Error. Below these checkboxes are counts of the number of cells in each category. You should see checks for Non-numeric and Blank if you changed some values.
1. Experiment with checking or unchecking these boxes to select subsets of your data.

[Episode 5 Exercise 1](episode5_ex1.md)
